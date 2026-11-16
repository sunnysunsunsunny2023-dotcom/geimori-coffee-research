# Geimori 送礼主题规划 v2.0 — 产品事实核验表（Product Factcheck）

> 站点：mywirsh.com（Shopify）｜ 核验日期：2026-11-16 ｜ 用途：作为全部送礼选题、内容 Brief、GEO 与 CTA 的产品事实依据
> 结论标注：**VERIFIED**（有可追溯证据）/ **ESTIMATED**（明确估算方法）/ **HYPOTHESIS**（待验证判断）/ **BLOCKED**（缺数据或权限，未完成）
> ⚠️ 本文档不是"写文章时再查一遍"的替代品：**任何正文生成前必须重新读取 Shopify 当前数据**（见第 6 节）。

---

## 1. 核验方法与证据来源

| 来源 | 类型 | 采集时间 | 可信度 |
|---|---|---|---|
| mywirsh.com 首页 Shopify JSON（实时价格/划线价/变体 handle） | 官网前台公开数据 | 2026-11-16 | VERIFIED（本表价格以此为准） |
| `sites/mywirsh-audit/upgrade_20261104/product_facts.py` 官方 Product Fact Source | 项目内 11-04 事实模块（规格，非价格） | 2026-11-04 | VERIFIED（规格以此为准） |
| `wirsh-ads/config/products_knowledge_base.json` | 9-21 广告知识库（**价格已过时**） | 2026-09-21 | ⚠️ 价格仅作历史对照，不用于正文 |
| Daily Coffee News 2024-11-12（GU78/GU64 背景） | 独立媒体报道 | 2024-11-12 | VERIFIED（仅背景） |

**关键发现**：官网产品 URL 前缀为 `/products/geimori-*`（如 `geimori-gu38`、`geimori-t38-gen2`），
11-04 事实模块中部分 source_url 旧路径（`/products/t38-battery`）与官网现 handle 不一致，**以官网当前 handle 为准**。

---

## 2. 各型号事实表

### 2.1 GU38 — 38mm 锥刀，紧凑型插电单剂量磨豆机
| 字段 | 值 | 证据 |
|---|---|---|
| 定位 | 紧凑型插电单剂量磨豆机；38mm 锥刀；170 RPM；无级微调 | VERIFIED（product_facts.py；官网名称 "Compact All-Purpose Grinder"） |
| 当前售价 | **$179.99**（Compare-at $249.99） | VERIFIED（官网首页 JSON，2026-11-16） |
| 官网 URL | https://mywirsh.com/products/geimori-gu38 | VERIFIED |
| 变体 | Black（首页 JSON 可见 1 个变体） | VERIFIED（变体完整性 BLOCKED，见 2.6） |
| 预算档位结论 | **不得放入 Under $100**；属 $150–$250 档 | VERIFIED（价格证据） |

### 2.2 GU63 — 63mm 锥刀，80 RPM，意式及滤泡适用
| 字段 | 值 | 证据 |
|---|---|---|
| 定位 | 63mm 锥刀；80 RPM 慢速冷研磨；无级 0-85；等离子防静电；<0.1g 低残粉；静音 <65dB | VERIFIED（product_facts.py） |
| 当前售价 | **$269.99**（Compare-at $299.99） | VERIFIED（官网首页 JSON，2026-11-16） |
| 官网 URL | https://mywirsh.com/products/geimori-gu63 | VERIFIED |
| 变体 | Default Title（首页 JSON 单变体） | VERIFIED（变体完整性 BLOCKED） |
| 预算档位结论 | 属 $250–$300 档；适合 "Under $300" 与中高预算送礼 | VERIFIED |

### 2.3 GU64 Gen2 — 64mm 平刀，变速旗舰磨豆机
| 字段 | 值 | 证据 |
|---|---|---|
| 定位 | 64mm 平刀；可调转速 800-1200 RPM；真无级微调；等离子防静电；<0.2g 残粉；Gen2 结构 | VERIFIED（product_facts.py） |
| 当前售价 | **$399.99**（Compare-at $499.99） | VERIFIED（官网首页 JSON，2026-11-16；变体 "Black / US / Multi-purpose Flat Burrs"） |
| 官网 URL | https://mywirsh.com/products/geimori-gu64 | VERIFIED（Gen2 与 GU64 同系列，官网 handle=geimori-gu64） |
| 预算档位结论 | **不得放入 Under $300**；属 $350–$500 档 | VERIFIED（价格证据） |

### 2.4 T38 Plus — 38mm 锥刀，插电式紧凑电动磨豆机（**不是手摇**）
| 字段 | 值 | 证据 |
|---|---|---|
| 定位 | 插电式（Plug-in）紧凑电动磨豆机；38mm 锥刀；无级微调 | VERIFIED（product_facts.py power=Plug-in；官网名称 "Portable Plug-in Grinder"） |
| 当前售价 | **$149.99**（Compare-at $199.99） | VERIFIED（官网首页 JSON，2026-11-16） |
| 官网 URL | https://mywirsh.com/products/geimori-t38-plus | VERIFIED |
| 禁止表述 | **严禁描述为手摇磨豆机**（官方定位插电电动便携）；严禁称无线/电池供电 | VERIFIED（factcheck 冲突模式 T38 Plus power=battery 即冲突） |
| 预算档位结论 | 属 $100–$200 档；可入 Under $200 | VERIFIED |

### 2.5 T38 Gen2 — 38mm 锥刀，无线电池供电电动磨豆机（预售待确认）
| 字段 | 值 | 证据 |
|---|---|---|
| 定位 | 无线电池供电电动磨豆机；38mm 锥刀 | VERIFIED（product_facts.py T38 Battery Gen2 power=Battery-powered；官网 handle=geimori-t38-gen2；2025-08-08 官方发布文 "Wireless Electric Portable"） |
| 官网 URL | https://mywirsh.com/products/geimori-t38-gen2 | VERIFIED（首页 handle 确认） |
| 当前售价 | 首页 JSON **price=null**；用户核验参考价 **$129.99（预售页面）** | ESTIMATED（用户 2026-11-16 核验价）+ BLOCKED（产品页限流未二次确认） |
| 预售/库存状态 | 未完成线上核验：产品页连续限流，首页未展示价格（与预售模式一致） | BLOCKED |
| 禁止表述 | 严禁描述为手摇；严禁暗示"圣诞前必到货"（预售交付未确认） | VERIFIED（规则） |

### 2.6 GU78 — 已停售，禁止作为现售产品推荐
| 字段 | 值 | 证据 |
|---|---|---|
| 状态 | **已停止销售（discontinued）**；官网首页无该产品；不得作为当前产品推荐 | VERIFIED（product_facts.py status=discontinued；首页无 handle=geimori-gu78） |
| 背景 | 78mm 平刀、400W 无刷电机、Kickstarter 众筹产品（2024 报道） | VERIFIED（Daily Coffee News 2024-11-12；仅背景，不作为现售依据） |
| 使用限制 | 正文中提及 GU78 必须标注"已停售/已停产"，否则视为事实冲突 | VERIFIED（factcheck 冲突规则） |

---

## 3. 价格对照：9-21 知识库（过时） vs 11-16 官网（当前）

| 型号 | 9-21 知识库参考价 | 11-16 官网当前价 | 结论 |
|---|---|---|---|
| GU38 | 约 $233（原价 $324） | **$179.99**（划线 $249.99） | 知识库过时，以官网为准 |
| GU63 | 约 $385 | **$269.99**（划线 $299.99） | 知识库过时，以官网为准 |
| GU64 Gen2 | 约 $516（原价 $645） | **$399.99**（划线 $499.99） | 知识库过时，以官网为准 |
| T38 Plus | 约 $257 | **$149.99**（划线 $199.99） | 知识库过时，以官网为准 |
| T38 Gen2（Battery） | 约 $141（原价 $219） | $129.99（预售，ESTIMATED） | 方向一致，仍待线上确认 |

> 提示：官网 11-16 显示全部为促销价（均有 Compare-at 划线价，黑五促销已开始）。促销期价格可能随活动变化，正文生成前必须重新读取。

---

## 4. 已知缺口（BLOCKED，未完成）

| 缺失项 | 说明 | 应对 |
|---|---|---|
| 实时库存数量（inventory_quantity） | 无 Shopify Admin 权限；官网前台 JSON 未暴露库存数量 | 所有文章不写"有货/库存 X"，仅在文案中使用"官网下单"中性表述 |
| Active / 可售状态逐变体确认 | 前台 JSON 变体字段多为精简引用（null），完整变体表未取到 | 不承诺"全变体有货"；T38 Gen2 预售状态标 BLOCKED |
| 区域供货（US/DE 等） | 未取得区域库存数据 | 不写区域库存承诺；配送信息引用官网 Shipping 页（另见 priority_calendar） |
| 预计发货/送达时间（圣诞前） | 未取得官方物流承诺；已有文章 `where-do-wirsh-geimori-orders-ship-from`（2026-10-31）可供参考但**不得自行推断最后下单日** | 2026 圣诞内容只写"以官网结算页配送估算为准"，不承诺到货日期 |
| T38 Gen2 预售页确认 | 产品页 2026-11-16 多次抓取均限流（local_rate_limited） | 标注 BLOCKED；写作前需人工打开产品页确认价格/预售文案 |

---

## 5. 事实冲突红线（写作/审核时逐条对照）

1. ❌ 把 T38 Plus 或 T38 Gen2 称为"手摇磨豆机" —— 官方均为电动（插电/无线）
2. ❌ 把 T38 Plus 称为"无线/电池" —— T38 Plus=插电；无线电池版=T38 Gen2
3. ❌ 把 GU38 放入 Under $100 —— 现价 $179.99
4. ❌ 把 GU64 Gen2 放入 Under $300 —— 现价 $399.99
5. ❌ 推荐 GU78 —— 已停售
6. ❌ 编造库存/优惠/配送日期/测试结果/产品性能
7. ❌ 暗示"预售产品圣诞前必到货"
8. ❌ 未核对官网实际售价就写"现在只要 $X"（促销价会变）
9. ⚠️ GU64 平刀 ≠ 锥刀；GU63 锥刀 ≠ 平刀（禁止交叉混淆）

---

## 6. 正文生成前必须执行的数据刷新流程（Checklist）

- [ ] 重新抓取官网首页/各产品页 JSON，记录最新 price + compare_at_price（黑五期间价格可能调整）
- [ ] 确认各产品 handle 仍在线（`/products/geimori-gu38|gu63|gu64|t38-gen2|t38-plus`）
- [ ] 人工确认 T38 Gen2 预售页：价格、预售文案、预计发货说明
- [ ] 确认 GU78 未在任何送礼推荐/集合页中出现
- [ ] 记录核验日期并更新本文档"核验日期"
