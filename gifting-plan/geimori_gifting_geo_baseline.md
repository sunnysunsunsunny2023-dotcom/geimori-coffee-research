# Geimori 送礼主题规划 v2.0 — Gifting GEO 研究基线（GEO Baseline）

> 站点：mywirsh.com ｜ 编制日期：2026-11-16 ｜ 用途：① 核实旧基线数字 ② 定义送礼意图 GEO 测试组（G01-G08）与复测方案
> 结论标注：**VERIFIED** / **ESTIMATED** / **HYPOTHESIS** / **BLOCKED**

---

## 1. 旧基线数字核实（GEO-2026-11-01）

| 指标 | 原报告数值 | 本次核验结果 | 证据 |
|---|---|---|---|
| run 总数 | 24 | **VERIFIED 24**（12 prompts × 2 runs） | `.mywirsh_local/data/geo_dashboard.json` baseline P01-P12 每条 runs=2 |
| prompt 数 | 12 | **VERIFIED 12**（P01-P12） | 同上 |
| Geimori 提及率 | 41.7% | **VERIFIED 41.7%**（正 2 / 负 8） | `.mywirsh_local/data/geo_baseline.json` brand_stats |
| 产品推荐率 | 接近 0 | **VERIFIED**：GU63 mentioned 0 / recommended 0；GU64 mentioned 2 / recommended 1；GU38/T38/GO1 全 0 | 同上 product_stats |
| 竞品高频 | Eureka 14 / DF64 12 / DF54 11 / Baratza 6 / Mazzer 6 / Niche Zero 5 / Fellow Opus 4 / 1Zpresso 4 / Timemore 4 | **VERIFIED** | 同上 top_competitors |
| 测试设置 | en_us_semantic；模型 deepseek-flash；平台 DeepSeek；search_modes count=8 | **VERIFIED** | geo_dashboard.json baseline 各条 |
| 送礼意图覆盖 | 无 | **VERIFIED 无任何送礼词**（gift/present/someone/what to buy 等均未出现于 P01-P12） | 12 条 question 全量文本检查 |
| 原始 run 明细 | 未提供 | **BLOCKED**：本地 `blog_intel.db` 的 geo_provider_runs / geo_prompts / geo_checks 表均为 0 行；仅存汇总 JSON。如需逐条 run 原文须回到 2026-11-01 采集脚本/阿里云侧数据 | 本地 DB 查询 |

**结论**：旧基线的"24 runs / 12 prompts / 41.7% / 推荐率近 0 / 无送礼意图"数字均可溯源（VERIFIED）。
但不能据此声称"Geimori 在送礼类 AI 回答中完全缺席"——原测试根本没测送礼意图（这是空白，不是缺席）。

---

## 2. 新 Gifting GEO 测试组（G01–G08）

### 2.1 Prompt 集（固定，按用户指定）

| ID | Prompt（英文，固定原文） | 对应内容资产 |
|---|---|---|
| G01 | What are the best gifts for coffee lovers under $200? | B 预算指南 / T38 Plus、GU38、配件 |
| G02 | What should I buy someone who already has a good coffee grinder? | C 已有设备 / 升级、配件、体验礼 |
| G03 | What is a good first coffee grinder to give as a gift? | F 新手第一台 / GU38、GU63 |
| G04 | What coffee grinder should I gift someone who makes espresso at home? | E 家庭吧台 / GU63、GU64 Gen2 |
| G05 | What is a good portable electric coffee grinder for travel? | D 便携 / T38 Gen2（无线）、T38 Plus（插电） |
| G06 | What are the best coffee gifts under $300? | B 预算指南 / GU63（$269.99） |
| G07 | Is a coffee grinder a good gift for someone who loves coffee? | A Hub / 定位文 |
| G08 | What coffee gifts are useful for someone with a small kitchen? | C/F 小空间 / T38 系列、GU38 |

### 2.2 固定测试设置（与旧基线保持一致或明确记录差异）

| 设置项 | 取值 | 说明 |
|---|---|---|
| 模型/平台 | DeepSeek（deepseek-flash） | 与旧基线同源，保证可比；如需多模型对比另建组，不同模型结果**不可直接合并** |
| 地区/语义上下文 | en_us_semantic | 与旧基线一致 |
| 语言 | English (US) | 固定 |
| 每 prompt 运行次数 | **4 runs**（建议；旧基线为 2 runs，送礼组提高样本量） | 记录每次完整输出 |
| search_mode | 沿用 count=8, need_content=false；记录到每条 run | 固定 |
| 采集日期 | **基线：内容上线前**（目标 2026-11-20 前）；复测：上线后 +14 天 / +30 天 | 日期随每次采集记录 |
| 保存 | 每次 run 保存原始回答全文 JSON（含模型版本、时间戳、region） | 建议存 `.mywirsh_local/data/geo_gifting_runs/` |

### 2.3 指标定义（每条 run 记录）

1. **品牌提及**：Geimori 被提及（是/否）+ 正/负/中性（按回答语境判断，标注判断依据）
2. **产品推荐**：Geimori 具体型号被推荐（GU38/GU63/GU64 Gen2/T38 Plus/T38 Gen2/其他）——逐型号计数
3. **正确产品信息**：提及产品时规格/价格/定位是否正确（如 T38 Plus 是否被误称手摇、价格是否过时）
4. **来源引用**：回答是否引用 mywirsh.com URL（具体哪个页面）
5. **购买链接**：是否给出购买/官网链接
6. **竞品提及**：品牌（Eureka/DF54/DF64/Baratza/Mazzer/Niche/Fellow/1Zpresso/Timemore 等）+ 具体型号，逐次记录
7. **错误推荐/过时价格**：任何不准确推荐、错误价格、错误定位都记录（含"无根据说法"）
8. **答案类型**：清单型/比较型/背景型/回避型

### 2.4 输出汇总模板（每次采集出一份）

```json
{
  "batch": "GEO-GIFTING-BASELINE-2026-11-20",
  "generated_utc": "...",
  "model": "deepseek-flash",
  "region": "en_us_semantic",
  "runs_per_prompt": 4,
  "prompt_total": 8,
  "run_total": 32,
  "results": {
    "G01": [
      {"run": 1, "geimori_mentioned": true, "tone": "positive", "model_recommended": ["GU38"], "model_mentioned_competitors": ["Baratza Encore ESP", "Fellow Opus"], "cited_urls": ["https://mywirsh.com/blogs/..."], "has_purchase_link": false, "factual_error": null, "answer_type": "list"},
      ...
    ]
  },
  "summary": {
    "geimori_mention_share": 0.0,
    "model_recommend_share": 0.0,
    "top_competitors": [["Baratza", 12], ...],
    "factual_errors": []
  }
}
```

### 2.5 复测与归因纪律（重要）

- **上线前必须先采集基线**（8 prompts × 4 runs = 32 runs），否则上线后无法判断变化。
- **固定设置**：模型、地区、语言、日期、search_mode、prompt 原文全部不变；升级模型版本时明确标注版本号并视为新基线。
- **多次运行保存完整结果**：禁止只保存汇总，禁止挑选"对品牌有利"的 run。
- **归因限制**：模型回答波动（哪怕同一 prompt 两次不同）不能归因于文章发布；判断发布效果需：
  1. 同一时间窗内基线（对照组，未发布新内容的同意图 prompt）同步复测；
  2. 至少 14 天窗口、多轮复测，观察趋势而非单次波动；
  3. 若仅品牌提及上升但产品信息错误，不视为成功，应计入 factual_error。
- **禁止**：为提高 AI 提及率制造虚假事实、虚构权威引用、机械堆砌问答式段落（由内容审核把关）。

---

## 3. 与内容上线节奏的挂钩

| 阶段 | 时间 | 动作 |
|---|---|---|
| 基线采集 | 内容上线前（目标 2026-11-20） | 跑 G01-G08 × 4 runs，出 baseline JSON |
| 首批内容上线 | 2026-11 底–12 月（按 priority_calendar） | 只发布已审核内容，不改 GEO 设置 |
| 第一次复测 | 上线 +14 天 | 同设置重跑，与基线对比 |
| 第二次复测 | 上线 +30 天 | 同设置重跑，看趋势；如基线对照组同步波动则归因"模型/环境变化" |
| 持续 | 2027 每季度 | 纳入常规 GEO 批次，与购买意图 P01-P12 并行维护 |

> 注：G01-G08 为**独立测试组**，与旧 P01-P12 并行；两者不要混算提及率。
