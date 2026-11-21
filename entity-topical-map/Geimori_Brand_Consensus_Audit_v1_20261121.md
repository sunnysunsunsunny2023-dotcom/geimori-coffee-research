# Geimori Brand Consensus 外部描述一致性快检 v1.0（2026-11-21）

> 目的：对照 Entity Definition 核心声明，审计外部（独立评测/目录/社区）如何描述 Geimori，
> 找出会干扰机器理解（Google/ELLM）与用户认知的不一致点。
> 方法：抓取独立评测 4 篇 + 采购目录 2 篇 + 官网多语言 owner stories，交叉比对技术规格与定位表述。
> 证据标注：每条含来源 URL 与日期；未核验项明确标注。

## 一、结论摘要

> ⚠️ **v1.1 修订（2026-11-21）**：经复核，官网转速口径已统一（以 PDP 为准），原"硬冲突"降级为"外部残留"。

| 维度 | 状态 |
| --- | --- |
| 核心定位（precision coffee grinder brand / Wirsh LLC 运营） | ✅ 外部与 Entity 卡一致 |
| 差异化属性（等离子防静电 / <0.1g 残粉 / 单剂量 / Cold Grind） | ✅ 外部普遍认可 |
| **官网技术规格口径** | ✅ **已统一（PDP 为准）：GU63=80 RPM、GU38=170 RPM，含澄清页** |
| **外部残留旧值** | ⚠️ Amazon 标题 110 RPM / ashgrind 110 RPM / 早期评测 190 RPM |
| **宣传口径风险（retention / 可维修性 / filter 表现）** | ⚠️ 3 项第三方质疑 |
| 产品在售状态（GU78） | ⚠️ 官网页面未清理 vs 外部目录标注 legacy |

---

## 二、✅ 一致项（可放心写进内容）

1. **品牌归属**：espressooutlet.com 目录明确写 "Geimori is a precision-grinder brand operated by **Wirsh LLC**"（[来源](https://espressooutlet.com/blogs/news/geimori-coffee-grinders-models-history-alternatives)）→ 与 Entity 卡 "precision coffee grinder brand" 及官网品牌归属完全一致。
2. **等离子防静电**：lukemakescoffee（[2026-07-20](https://lukemakescoffee.com/geimori-gu63-review-is-this-250-single-dose-grinder-too-good-to-be-true/)）、ashgrind（[2026-09-25](https://ashgrind.com/vetted/best-single-dose-espresso-grinder-under-1500/)）、官网均确认 plasma ionizer 是核心卖点。
3. **低残粉 <0.1g**：lukemakescoffee "consistently under 0.1 grams"、ashgrind "Retention below 0.1g"、官网 "<0.1 g with bellows" 三方一致。
4. **"Cold Grind" 术语**：lukemakescoffee 用 "Cold Grind" 描述低转速技术，与官网 "Cold Grind Technology" 同一术语。
5. **单剂量定位**：所有来源均把 GU 系列归为 single-dose 磨豆机。
6. **GU64 目录信息**：espressooutlet 与官网一致（64mm flat / 800–1200 RPM / quick-release）。

---

## 三、✅ 已统一：官网技术规格口径（v1.1 复核，PDP 为准）

> 复核结论：官网全部页面已按 PDP 统一，P0 在官网侧已完成，无内部矛盾。

### GU63 转速：官网统一为 80 RPM

| 页面 | 数字 | 日期 |
| --- | --- | --- |
| 官网 mywirsh.com GU63 产品页 PDP（规格表 + FAQ） | **80 RPM**（100W DC motor） | 当前 |
| which-geimori 对比页 | 80 RPM | 当前 |
| geimori.mywirsh.com 三方对比表（GU38 vs GU63 vs T38 Plus） | 100 W DC · 80 RPM | 2026-09-21 |
| 官网 Review Roundup 澄清页 | "The GU63 operates at 80 RPM… If you saw **110 RPM** or another wattage number in older materials, read our GU63 power…" | 2026-07-27 |
| 官网 buying-guide 对比文（vs DF54/Opus2/Encore ESP） | 80 RPM, plasma anti-static | 2026-10-04 |
| 多语言对比页（HU/JA 等） | 80 RPM | 当前 |

### GU38 转速：官网统一为 170 RPM

| 页面 | 数字 | 日期 |
| --- | --- | --- |
| 官网 mywirsh.com GU38 产品页 PDP（规格表） | **170 RPM**（80W DC motor） | 当前 |
| which-geimori 对比页 | 170 RPM | 当前 |
| geimori.mywirsh.com 三方对比表 | 80 W DC · 170 RPM | 2026-09-21 |

### ⚠️ 外部残留旧值（不再算官网内部冲突，但影响 Brand Consensus）

| 残留位置 | 旧值 | 最后观测日期 | 影响与建议 |
| --- | --- | --- | --- |
| **Amazon 商品标题**（bestproducts.reviews 聚合的 Amazon listing 文案） | GU63 "110 RPM Cold Grind" | 2026-11-15 | **最高优先**：消费者直接看到的销售页；建议同步 Amazon 后台标题/五点描述 |
| ashgrind.com 采购目录 | GU63 110 RPM | 2026-09-25 | 在官网 7/27 澄清之后仍未更新；可联系更新或忽略（低流量） |
| lukemakescoffee.com 评测 | GU63 110 RPM | 2026-07-20 | 历史文章（早于澄清页）；官网 roundup 已兜底；如需可协商加更正注 |
| thewaytocoffee.com / wearethemouth.com / coffeegrinderguide.com / manuals.plus | GU38 190 RPM | 2026-04~08 | 历史评测/手册；官网 roundup 已兜底 |
| GU38 PDP 规格表 typo | "marked scale from 0 through **5**"（应为 0–65） | 当前 | 官网内部小笔误，顺手修 |

> 处理原则：**以 PDP 为唯一权威口径**。官网侧已一致；外部残留分两类——销售页（Amazon）应主动同步，历史评测文章由 roundup 页兜底即可，不必逐一追改。

---

## 四、⚠️ 宣传口径风险（第三方实测 vs 官方宣传）

### 风险 1：GU38 "zero/low retention" 宣传 —— 第三方实测随时间升高

- thewaytocoffee（2026-08-04）："Retention was close to the claim when new, though it climbed noticeably over a couple of months of daily use… read the zero-retention claim as accurate **out of the box rather than accurate forever**."
- 影响：用户按官方 "low retention" 预期购买，数月后体验下降 → 差评风险 + 语义矛盾。
- 建议（P1）：官方文案给 retention 声明加时间/使用条件限定（如 "with bellows, on new burrs"），或在 FAQ 补充保养说明（定期清理可恢复），回应实测路径。

### 风险 2：GU38 可维修性 —— 第三方点名批评

- brewingcoffeemanually.com（2026-07-02）："It is also **not repairable and Wirsh does not offer replacement burrs**."
- 影响：这是购买决策负面信号，且与 GU64 "quick-release burr platform" 的生态叙事形成反差。
- 建议（P1）：确认 GU38 是否提供替换刀盘/维修支持；若有 → 更新官网 FAQ + 联系该评测补充；若确实无 → 在购买页如实说明，避免"惊喜"差评。

### 风险 3：GU63 filter 表现 —— 第三方认为 conical 偏弱

- lukemakescoffee：Filter/Light Roast **3.5/5**，"conical burrs favor body and sweetness over razor-sharp flavor separation"，建议 clarity-chaser 选平刀。
- 影响：官网定位 GU63 "espresso **and filter** coffee"，第三方实测 filter 只是"respectable"。轻微定位张力，但不算事实冲突。
- 建议（P2）：内容侧把 GU63 filter 表述从"全能"收敛为"conical 风味取向（body/甜感）"，顺势引流平刀 GU64。

---

## 五、目录/社区描述（Brand Consensus 侧面）

| 来源 | 描述 | 与 Entity 卡一致性 |
| --- | --- | --- |
| espressooutlet.com 目录 | 四模型 GU64/GU63/GU38/T38 Plus；GU78 标注 "development/legacy campaign; **not current store model**" | ⚠️ 与官网 which-geimori 页仍展示 GU78 矛盾（呼应 factcheck 已停售；官网页面未清理） |
| ashgrind.com | GU63 入选 "13 Best Single Dose Espresso Grinders Under $1500"、"Best Premium Build" | ✅ 正面背书 |
| owner stories（多语言） | GU63 用户好评（对比 Weber Key/EG1 等 "endgame" 机型）；噪音实测 **86 dB**（西语用户） | ⚠️ 与官网 FAQ "<65dB" 冲突（待核验：可能测量条件不同） |

- GU78 清理建议（P1）：which-geimori 对比页仍有 GU78 "Best for cafés" 区块，与停售事实矛盾；建议下架或标注 "discontinued"。

---

## 六、对 Entity 卡 / 内容系统的落地动作

| 优先级 | 动作 | 负责面 | 状态 |
| --- | --- | --- | --- |
| P0 | 核实 GU63（80 vs 110 RPM）与 GU38（170 vs 190 RPM）实测值，统一官网全部页面口径，同步修正 Entity 卡差异化属性 | 产品 + 官网 | ✅ **已完成（v1.1 复核）：官网已统一为 PDP 值（80 / 170），含 7/27 澄清页；Entity 卡 80 RPM 与官网一致，无需改** |
| P0 | **同步 Amazon 商品标题/五点描述：GU63 仍写 110 RPM** | 电商运营 | ⏳ 待办（最高优先） |
| P1 | 官网 which-geimori 页清理 GU78 区块（停售标注） | 官网 | ⏳ 待办 |
| P1 | retention 宣传加时间/使用条件限定；确认 GU38 替换刀盘支持并补 FAQ | 官网 | ⏳ 待办 |
| P1 | 修 GU38 PDP 规格表 typo（"0 through 5" → 0–65） | 官网 | ⏳ 待办（顺手项） |
| P2 | GU63 电机类型补说明；GU63 filter 定位表述收敛（conical 风味取向） | 内容 | ⏳ 待办 |
| P2 | 与已合作第三方（lukemakescoffee / thewaytocoffee）同步口径修正 | PR | ⏳ 待办 |

---

## 七、版本记录

- v1.0（2026-11-21）：首版快检。来源：4 篇独立评测 + 2 篇目录 + 官网多语言页 + 官网产品页/对比页。未做：Reddit/YouTube 社区全量审计（可由 Reddit Pulse 数据补充）、Amazon 评论聚合。
- v1.1（2026-11-21）：复核官网口径——确认 P0 已统一（PDP 为准：GU63=80 RPM、GU38=170 RPM，含 7/27 Review Roundup 澄清页）；原"硬冲突"降级为"外部残留"，新增 Amazon 标题 110 RPM 残留为最高优先待办；顺手发现 GU38 PDP 规格表 typo。
