# Geimori 送礼主题规划 v2.1 — 内容 Cluster 架构（Gift Content Cluster）· 第三轮审核修正版

> 站点：mywirsh.com ｜ 编制日期：2026-11-16 ｜ 修订：2026-11-16 第三轮审核
> 依据：28 篇审核矩阵（`geimori_gifting_audit_v2.md`）+ 产品事实（`geimori_gifting_product_factcheck.md`）+ SERP/Reddit 证据（`gift_serp_reddit_evidence_2026-11-16.md`）
> 结论标注：**VERIFIED** / **ESTIMATED** / **HYPOTHESIS** / **BLOCKED**
> ⚠️ 本文件只做架构与内链规划；**未经批准不执行 URL 迁移、301、canonical 修改或删除旧文章**。
> ⚠️ 本轮修正范围：① SERP 证据等级重分级 ② 现有页面完整去重矩阵 ③ 预算分层规范 ④ 内链质量门槛 ⑤ 条件化写作原则 ⑥ 效果衡量方案。不新增选题。

---

## 0. 本轮审核修正总览

| 审核意见 | 修正内容 | 位置 |
|---|---|---|
| 1. SERP 证据等级 | 全部"空缺/无专文"降级为 HYPOTHESIS（编辑机会），不再表述为已验证搜索需求；区分「搜索量证据」「SERP 竞争」「编辑机会」三层 | §2 |
| 2. 完整现有页面去重 | 新增逐项去重矩阵（Finder 页 7、自购指南 16、送礼页、Collection 5、PDP 6），对比关键词/意图/目标 URL | §3 |
| 3. 预算分层 | 半开区间定义边界一致、不重叠；长期文章减少硬编码促销价；明确核验日期与更新机制 | §5 |
| 4. 发布优先级 | A Hub REFRESH = 唯一 P0；B-F 排序依据（待 GSC/真实 SERP/库存/商业价值） | §6 + `priority_calendar_2026_2027.md` |
| 5. Brief 预设结论 | 条件化原则：不默认磨豆机最佳、不默认升级值得、不默认意式玩家需要变速/新刀盘 | §8 + A Hub Final Brief |
| 6. 内链质量门槛 | 删除"每个 Spoke 至少回链 1 次"机械规则；链接须解决读者当前问题 | §6 |
| 7. 产品图片规则 | 继续严格执行（禁虚构外观、仅真实核验素材） | §9 |
| 8. 效果衡量 | 新增 GSC + 产品转化追踪 + 归因约束 | §10 |

---

## 1. Cluster 总览（架构批准，保留）

**Gift Content Cluster** 采用 Hub/Spoke 结构：

```
                        ┌────────────────────────────┐
                        │  HUB：A. Ultimate Coffee    │
                        │  Gift Guide（年度指南）      │
                        │  REFRESH 原 Holiday URL     │
                        └─────────────┬──────────────┘
        ┌───────────────┬─────────────┼──────────────┬───────────────┐
        ▼               ▼             ▼              ▼               ▼
   B. Budget      C. Already    D. Portable    E. Home        F. First
   （预算指南）      Have Everything （便携送礼）   Baristas       Grinder Gift
   候选（排序待定） 候选（排序待定）  候选（排序待定）  候选（排序待定） 候选（排序待定）
        └─────── 支持页/互链：现有 Finder / quiet / hand-vs-electric /
                 upgrade / camping / pour-over / under-$300 / shipping ───────┘
```

**原则（修正后）**：
1. Hub（A）承担主流量与主题权威，是唯一确认的第一优先级（P0）。
2. Spoke（B-F）为候选，**排序须在完成 GSC 查询、真实 SERP 复核、当前库存/预售核验、商业价值评估后确定**，不得按序号默认 B>C>D>E>F。
3. 现有相关正文只做互链与差异化引用，不重复技术内容、不改 URL、不删文。

---

## 2. SERP 证据等级（修正）

### 2.1 三层区分（所有关键词一律按此标注）

| 层级 | 定义 | 本 Cluster 的用法 |
|---|---|---|
| **搜索量证据** | 有可靠工具（GSC/AAHrefs/SEMrush）测得的月搜索量 | 当前**全部缺失** → 不写任何月搜索量数字（BLOCKED） |
| **SERP 竞争** | 实际搜索采集到的前 10 位页面类型与数量（2026-11-16 采集，可见条数如实标注） | 有证据，可描述竞争格局（VERIFIED 于采集记录） |
| **编辑机会** | 基于「结果少 / 无专文 / 非美国结果多」推断的切入空间 | 全部为 **HYPOTHESIS**，不得写成已验证需求 |

**规则**：
- 任何"空缺""无专文""供给稀薄"表述必须带 **HYPOTHESIS** 标签，并说明推断依据（采集日期、可见条数、被污染结果）。
- 不得把「搜索结果少」推断为「搜索量低」；也不得把「搜索量证据缺失」推断为「搜索量高」。
- 证据等级记录以 `geimori_gifting_keyword_serp_map.csv`（2026-11-16 采集）为准；写作与内链决策引用时附 HYPOTHESIS 标签。

### 2.2 各候选词的证据状态（摘要）

| 关键词 | SERP 竞争（VERIFIED 2026-11-16） | 搜索量 | 编辑机会（HYPOTHESIS） |
|---|---|---|---|
| coffee gifts for coffee lovers | 清单文章约 7 成，头部媒体+品牌站 | BLOCKED | Hub 主词，竞争已充分，靠内容质量+内链 |
| what to buy a coffee lover who has everything | 3 条可见，被通稿覆盖 | BLOCKED | 无美国专文 → 有切入空间（HYPOTHESIS） |
| portable electric coffee grinder | 4 条可见，内容站高度聚合 | BLOCKED | 品牌站直接参与空间小，需送礼场景差异化 |
| first coffee grinder for beginners | 5 条可见，磨豆机站最拥挤词之一 | BLOCKED | 靠送礼视角差异化（F），非流量缺口 |
| coffee gift card vs beans vs grinder | 3 条可见，无美国专文 | BLOCKED | 决策型长尾，切入空间（HYPOTHESIS） |
| coffee gifts for small kitchens | 3 条间接命中，无专文 | BLOCKED | 切入空间（HYPOTHESIS） |
| coffee gifts for her | 无独立可见结果 | BLOCKED | 细分空缺（HYPOTHESIS），并入 A/B 章节 |
| under $50 / under $100 | 各 4 条可见，含大量非美国结果 | BLOCKED | 美国供给稀疏（HYPOTHESIS），并入 B |
| coffee gift basket ideas | 4 条可见，美国供给稀薄 | BLOCKED | DIY 篮子差异化（HYPOTHESIS），2027 候选 |
| christmas gifts for coffee lovers | 6 条可见，品牌站+清单站竞争激烈 | BLOCKED | 旺季窗口，不独立建页（并入 A Holiday 版） |

---

## 3. 现有页面完整去重矩阵（第三轮新增，逐项核对）

> 核对对象：content_publisher.db 216 篇已发布 + 官网首页可见 Collection/PDP（2026-11-16 VERIFIED）。比较维度：关键词 / 搜索意图 / 目标 URL / 承担功能 / 与本 Cluster 的冲突与差异化。

### 3.1 Finder / 型号选择类（7 页，承担"选哪台"功能）

| 现有 URL（VERIFIED） | 承担功能 | 主关键词（HYPOTHESIS，无 GSC） | 搜索意图 | 与本 Cluster 的关系 |
|---|---|---|---|---|
| `buying-guide/geimori-grinder-flavor-comparison`（2026-10-16） | 按口味选型 | which geimori grinder / body vs clarity | 自购：选适合自己喝法的型号 | 与 A"选型模块"互链；**不新建 Gift Finder URL** |
| `external-reviews/gu38-vs-gu63-vs-t38-plus-review`（2026-09-21） | 按工作流选型 | gu38 vs gu63 vs t38 plus | 自购：对比三型号工作流 | 同上；Gift 视角差异化在"收礼人画像"而非型号对比 |
| `buying-guide/geimori-gu64-gen1-vs-gen2-differences`（2026-11-11） | GU64 内部对比 | gu64 gen1 vs gen2 | 自购：Gen2 是否值得 | A/E 引用，不重复 |
| `buying-guide/geimori-gu64-mp-burr-vs-f-burr...`（2026-09-06） | GU64 刀盘对比 | gu64 mp vs f burr | 自购：刀盘选择 | E 兼容性引用 |
| `buying-guide/geimori-gu38-coffee-grinder-compact-single-dose...`（2026-06-29） | GU38 单品适用性 | is gu38 right for me | 自购 | B/F 引用单品定位 |
| `buying-guide/is-the-geimori-t38-plus-the-right-coffee-grinder-for-your-home-setup`（2026-06-24） | T38 Plus 单品适用性 | is t38 plus right for me | 自购 | D 引用插电定位 |
| `buying-guide/is-the-gu63-the-right-grinder-for-your-home-espresso-setup`（2026-07-27） | GU63 单品适用性 | is gu63 right for home espresso | 自购 | E 引用 |

**结论**：现有 7 页全部是"自购选型"意图；本 Cluster 的 A-F 全部是"送礼决策"意图（收礼人画像→预算→风险），意图层面不冲突。但型号对比内容高度重叠 → A 的选型模块**只链接不重复对比**，B-F 不写"哪台最好"型号横评，只按预算/场景给"候选+适用条件"。**未核验**：上述页真实排名词（GSC BLOCKED）——若上线后 GSC 显示某送礼页与 Finder 页抢词，按 GSC 数据再调整。

### 3.2 Grinder 自购指南类（16 页，全部自购意图，不建送礼替代）

| 现有 URL（VERIFIED） | 搜索意图 | 与本 Cluster 的关系 |
|---|---|---|
| `buying-guide/geimori-gu63-vs-df54-vs-fellow-opus-2-vs-baratza-encore-esp-pro`（2026-10-04） | 自购 $300 内对比 | B 的 $200–299 档互链；E 意式对比引用 |
| `buying-guide/how-much-does-a-large-conical-burr-grinder-cost`（2026-10-04） | 价格认知 | B 成本段互链 |
| `buying-guide/flat-burr-grinder-buying-guide-2026`（2026-10-25） | 平刀自购 | E 变速/平刀引用（**不预设意式玩家需要平刀**） |
| `buying-guide/hand-grinder-vs-electric-grinder-upgrade`（2026-10-06） | 手摇 vs 电动自购 | D 三类型互链 |
| `buying-guide/quiet-coffee-grinder-small-apartment`（2026-11-10） | 静音自购 | B 静音 FAQ 互链；D 体积/噪音引用 |
| `buying-guide/when-is-a-grinder-upgrade-actually-worth-it`（2026-10-05） | 升级决策自购 | C 升级逻辑互链（**C 不重复升级技术，只给送礼建议**） |
| `buying-guide/what-actually-makes-a-coffee-grinder-good-for-espresso`（2026-10-05） | 意式原理 | E 引用 |
| `buying-guide/best-coffee-grinder-for-lattes-cappuccinos`（2026-11-12） | 奶咖自购 | E 引用 |
| `buying-guide/best-coffee-grinder-for-pour-over-what-matters`（2026-11-13） | 手冲自购 | B/E 手冲送礼场景互链 |
| `buying-guide/how-long-should-a-coffee-grinder-last`（2026-11-14） | 耐用性 | B 预算段引用（耐用性考虑） |
| `coffee-facts/geimori-coffee-grinding-guide`（2026-09-09） | 磨豆教程 | F 新手入门互链 |
| `buying-guide/camping-coffee-setup-guide-fresh-coffee-outdoors-with-geimori-t38...`（2026-06-25） | 露营使用 | D 露营场景互链（不重复设备清单） |
| `coffee-facts/why-hopper-grinders-can-cost-you-freshness-the-single-dose-alternative`（2026-08-24） | 单剂量 vs 料斗 | B 引用单剂量价值（**不预设所有人适合单剂量**） |
| `buying-guide/how-rpm-can-influence-grind-quality-flow-and-flavor`（2026-06-26） | RPM 原理 | E 引用（**不预设意式玩家需要变速**） |
| `buying-guide/geimori-amazon-vs-official-website`（2026-11-12） | 购买渠道 | A 购买 CTA 引用（渠道差异） |
| `buying-guide/where-do-wirsh-geimori-orders-ship-from`（2026-10-31） | 配送信息 | A/B/C/D/E/F 圣诞配送风险段落引用 |

**结论**：自购指南 16 页全部保留为支持页，A-F 通过互链引用其技术内容，**不复制正文、不抢占其自购关键词**。

### 3.3 现有送礼页（8+2 页）

| 现有 URL（VERIFIED） | 意图 | 与本 Cluster 的关系 |
|---|---|---|
| `coffee-facts/the-ultimate-holiday-gift-guide-for-the-coffee-aficionado`（2025-10-25） | **A Hub 原 URL** | REFRESH 保留 URL；原论点"礼物跟随收礼人喝法"保留，内容升级 |
| `coffee-facts/fathers-day-coffee-gift-guide`（2026-06-12） | 父情节送礼 | Holiday 可选 REFRESH（磨豆机视角补充）；不改 URL |
| `coffee-facts/the-perfect-mother-s-day-gift-guide`（2026-04-30） | 母亲节送礼 | 同上 |
| `coffee-facts/how-to-choose-the-perfect-christmas-gift-a-guide-featuring-the-wirsh-espresso-machine`（2024-12-13） | 圣诞意式机视角（旧） | A Holiday 版互链；不迁移不删 |
| `coffee-facts/how-to-give-the-gift-of-cafe-quality-espresso-this-thanksgiving`（2024-11-21） | 感恩节意式机视角（旧） | 同上 |
| `coffee-facts/best-father-s-day-gift-gift-idea-for-dad`（2024-06-10） | 父情节（旧） | 与 2026-06-12 父情节文并存；暂不处理（REFRESH 时评估是否 canonical 建议，需批准） |
| `coffee-facts/perfect-valentines-day-gift-cool-material-recommends...`（2024-02-05） | 情人节（旧，含过期价格声明） | 只互链，不更新（历史存档性质） |
| `coffee-facts/why-is-an-espresso-machine...`（2023-02-04） | 情人节（旧） | 同上 |
| `buying-guide/must-have-tools-for-espresso-lovers`（2023-06-20） | 意式工具清单 | A/E 引用 |
| `coffee-facts/unique-coffee-recipes-for-coffee-lovers`（2022-03-31） | 食谱 | A 引用（体验礼方向） |

**结论**：现有送礼页 10 篇不删除；A REFRESH 吸收其精华论点；父/母节日文可选 REFRESH；旧圣诞/情人节文保留原 URL（历史定位），A 与之互链。

### 3.4 产品集合页与产品页（2026-11-16 首页 VERIFIED）

| 页面 | URL | 角色 |
|---|---|---|
| Collection：Geimori Coffee Grinder Series | `https://mywirsh.com/collections/geimori-coffee-grinder-series` | A/B/C/E/F 的磨豆机 CTA 汇总目标 |
| Collection：Geimori Accessories | `https://mywirsh.com/collections/geimori-accessories` | C 配件向 CTA 目标 |
| Collection：Accessories | `https://mywirsh.com/collections/accessories` | C/B 配件 CTA 备选 |
| Collection：Best Sellers | `https://mywirsh.com/collections/best-sellers` | B 预算档 CTA 备选 |
| Collection：All | `https://mywirsh.com/collections/all` | 兜底 |
| PDP：GU38 | `/products/geimori-gu38` | $179.99 |
| PDP：GU63 | `/products/geimori-gu63` | $269.99 |
| PDP：GU64 Gen2 | `/products/geimori-gu64` | $399.99 |
| PDP：T38 Gen2 | `/products/geimori-t38-gen2` | $129.99 预售（BLOCKED 状态） |
| PDP：T38 Plus | `/products/geimori-t38-plus` | $149.99 |
| PDP：Wirsh Iced Coffee Maker | `/products/wirsh-iced-coffee-maker` | E 组合大礼备选 |

**规则**：Cluster 页 CTA 优先链接具体 PDP 或对应 Collection；不重复 Collection 文案；**不新建竞争 Collection/Product 页**。

---

## 4. Hub 与 Spoke 明细（候选，排序见 §6）

### A. Ultimate Coffee Gift Guide（年度 Hub）— P0 REFRESH
| 项 | 值 |
|---|---|
| 现有 URL（保留） | `https://mywirsh.com/blogs/coffee-facts/the-ultimate-holiday-gift-guide-for-the-coffee-aficionado`（2025-10-25 发布，VERIFIED） |
| 原 URL 内容核验 | VERIFIED（db summary）：原论点"礼物跟随收礼人喝法"，与送礼理念一致，REFRESH 保留论点、重写结构与更新数据 |
| 内容范围 | 为什么磨豆机是"有条件地"好礼物（先答问题，附适用条件与例外）｜预算速查（链接 B，不复制档位明细）｜按收礼人速查｜5 步选礼｜避坑清单｜2026 Holiday 版内容（11 月底前上线） |
| 主关键词 | best gifts for coffee lovers；coffee gift guide（搜索量 BLOCKED） |
| 内链 | 见 §6 质量门槛：只链"能解决读者当前问题"的页面 |
| 产品 CTA | 每场景 1 个条件化 CTA（"如果 TA……那么……"）；不重复推荐段落 |
| 更新频率 | 年度（11 月前刷新）+ 节假增量 |

### B. Coffee Gifts by Budget — 候选（P1）
- 建议 URL：`/blogs/buying-guide/coffee-gift-guide-by-budget`
- 主关键词：coffee gifts by budget / under $50 / under $100 / under $300（搜索量 BLOCKED；SERP 竞争 VERIFIED：under 档被 capitolcitycoffee+engadget 主导且混入非美国结果）
- 预算分层：见 §5（半开区间、不重叠、边界一致）
- 内链目标：A、C、D、F、PDP；来源：A
- 更新频率：价格敏感（促销变动后复查；正文用区间+核验日期，不硬编码促销价）

### C. Gifts for Someone Who Already Has a Coffee Grinder — 候选（P1）
- 建议 URL：`/blogs/buying-guide/coffee-gifts-for-someone-who-already-has-a-grinder`
- 主关键词：what to buy a coffee lover who has everything / already has a grinder（HYPOTHESIS 切入空间）
- 内容范围：判断对方设备 → 已有好磨豆机时：豆/秤/课程/杯测/礼品卡（**不默认升级值得**）→ 什么条件下升级才值得（互链 upgrade 文）→ 三选一决策段
- 内链目标：A、B、D、upgrade 文、PDP+配件 Collection
- 更新频率：Evergreen，季度复查

### D. Portable Coffee Grinder Gifts — 候选（P1，依赖 T38 Gen2 预售确认）
- 建议 URL：`/blogs/buying-guide/portable-coffee-grinder-gifts-for-travelers-campers`
- 主关键词：portable coffee grinder gift / best portable electric coffee grinder（SERP 竞争 VERIFIED：高度聚合，需送礼场景差异化）
- 三类型事实（VERIFIED）：T38 Gen2=无线电池（预售 BLOCKED）｜T38 Plus=插电便携（非手摇）｜真手摇=非品牌
- 内链目标：A、C、露营文、T38 PDP；来源：A
- 更新频率：Evergreen + T38 Gen2 交付状态变化时复查

### E. Coffee Gifts for Home Baristas & Espresso Lovers — 候选（P1）
- 建议 URL：`/blogs/buying-guide/coffee-gifts-for-home-baristas-espresso-lovers`
- 主关键词：gifts for home barista / coffee gifts for espresso lovers（SERP 竞争 VERIFIED：配件向为主，磨豆机组合有差异化空间）
- 内容范围：意式玩家送礼；**条件化**：对方已有意式机时磨豆机是"最常被忽略的升级件"之一，但须看对方现状（已有磨豆机则送配件/豆/体验）；不预设需要变速或新刀盘
- 内链目标：A、F、意式自购指南、GU63/GU64 PDP；来源：A
- 更新频率：Evergreen，季度复查

### F. First Coffee Grinder Gift — 候选（P1）
- 建议 URL：`/blogs/buying-guide/first-coffee-grinder-gift-beginner-guide`
- 主关键词：first coffee grinder gift / best first coffee grinder（SERP 竞争 VERIFIED：最拥挤词之一，靠送礼视角差异化）
- 内容范围：送第一台磨豆机：先问喝法→新手友好度→预算→空间→从预磨/刀片升级的收益（客观表述）；吸收小空间场景
- 内链目标：A、E、新手入门内容、GU38/GU63 PDP；来源：A
- 更新频率：Evergreen，季度复查；写作前复查线上是否已有"第一台磨豆机"主题文

---

## 5. 预算分层规范（第三轮修正）

**原则**：
1. 半开区间 `[下界, 上界)`，边界值全局一致、不重叠、无缝隙。
2. 长期文章**不硬编码单一促销价**：写"当前官网价区间"+核验日期；促销变动只更新核验日期与区间，不重写正文。
3. 核验机制：每次促销/价格变动后复查；正文标注"价格核验于 YYYY-MM-DD，以官网实时价为准"。

**统一档位（2026-11-16 核验价 VERIFIED）**：

| 档位（USD） | 内容策略 | Geimori 适配产品 | 非品牌选项（如实写） |
|---|---|---|---|
| $25 以下 | 配件/豆/杯 | 无磨豆机 | 咖啡豆、杯具、配件小件 |
| $25–49.99 | 配件组合、订阅 | 无磨豆机 | 手摇磨豆机（1Zpresso 等） |
| $50–99.99 | 配件+豆组合 | 无磨豆机 | 手摇/入门电动 |
| $100–149.99 | 便携电动 | T38 Gen2（$129.99 预售，披露交付状态）；T38 Plus 下沿 | 无 |
| $150–199.99 | 紧凑插电单剂量 | T38 Plus（$149.99）；GU38（$179.99） | 无 |
| $200–299.99 | 意式+滤泡 | GU63（$269.99） | Baratza/Fellow（对比引用） |
| $300–399.99 | 平刀升级预备 | 无 Geimori 产品（GU64 在 $399.99） | DF64 等（对比引用） |
| $400+ | 平刀变速旗舰 | GU64 Gen2（$399.99 属 $300–399.99 上沿→实际归入此档边界说明） | 高端他牌 |

> ⚠️ 边界说明：GU64 Gen2 现价 $399.99 位于 $300–399.99 档上沿；为避免歧义，正文表述为"$400 内旗舰"或直接写实价"$399.99"，**禁止放入 $300 以下档**（用户铁律）。档位边界在文章中统一用"under $X"与"$X and up"二选一口径，不在同一文内混用。

---

## 6. 内链质量门槛（第三轮修正，取代"每个 Spoke 至少回链 1 次"）

1. **链接必须解决读者当前问题**：只在读者读到"需要更多信息"的位置放链接（如"预算怎么分→预算指南""对方已有磨豆机→已有什么都有的送法"）。
2. **Hub/Spoke 不机械互链**：删除"每个 Spoke 至少回链 Hub 1 次"要求；B-F 只有在"A 能进一步回答读者问题时"才回链 A；A 内链 B-F 同理。
3. **锚文本自然**：用描述性短语（"我们的预算指南""升级什么时候值得""便携选项说明"），避免精确匹配堆砌。
4. **每页内链上限建议 3–6 个**（正文内），超出即视为凑数，须删除。
5. 引用现有自购指南时只链"读者下一步要读"的那篇，不批量互链。
6. 产品 CTA 与内链分离：CTA 解决"去哪买"，内链解决"我还需要知道什么"。

---

## 7. 产品 CTA 与页面关系

- CTA 目标：PDP（geimori-gu38/gu63/gu64/t38-gen2/t38-plus/wirsh-iced-coffee-maker）或对应 Collection（grinder-series / geimori-accessories / accessories / best-sellers），按读者意图就近选择。
- CTA 文案条件化：不写"最佳/最安静/零残留/一定改善风味"；用"适合……场景""如果 TA 主要喝……""预算在……区间可考虑"。
- T38 Gen2 预售：任何 CTA 必须披露预售交付不确定性（BLOCKED 状态未确认），不得暗示圣诞前到货。
- 缺货/下架商品：不得默认提供直接购买推荐（GU78 已停售，禁止推荐）。

---

## 8. 写作质量与条件化原则（第三轮修正预设结论）

所有 Cluster 页写作必须遵守：
1. **不默认磨豆机一定是最佳礼物**：先判断收礼人现状；已有很多设备/不爱动手/只想轻松喝→豆、杯、订阅、礼品卡更合适。
2. **不默认"已有磨豆机=值得升级"**：升级只在对方使用受限（噪音/老机器/手摇想换电动/想玩意式）且预算允许时建议；否则推荐非磨豆机选项。
3. **不默认意式玩家需要变速/平刀/新刀盘**：按对方现有设备与冲煮习惯给条件化建议；引用 RPM/平刀指南时不预设结论。
4. **先答问题再推产品**；允许客观讨论非 Geimori 选项；Reddit 引用带 URL、不引原话、不称共识。
5. 无依据的不写：测试结果、专家意见、用户评价、搜索量、配送日期、促销截止。

---

## 9. 图片与品牌规范（继续严格执行）

1. 禁止 AI 生成或虚构 Geimori/Wirsh 磨豆机外观；禁止用图片修改产品结构/Logo/比例。
2. 只有经过核实的真实产品图可展示产品；没有合适素材时用不含磨豆机的咖啡生活场景。
3. 所有图片提供准确、自然的 alt text。
4. 品牌拼写 Geimori；Wirsh 与 Geimori 归属准确。

---

## 10. 效果衡量方案（第三轮新增）

> 目的：衡量 Cluster 实际效果；**不得把自然流量增长直接归因于 GEO 优化**。

### 10.1 流量与排名（GSC，需开通权限）
- 追踪指标：impressions、clicks、CTR、平均位置
- 维度：query（含送礼词族）、landing page（A Hub 及各 Spoke URL）
- 基线：上线前记录 A Hub 原 URL 过去 90 天 GSC 数据（当前 BLOCKED，无权限）
- 复测：上线后 14/30/60 天对比

### 10.2 站内行为与转化（GA4/Shopify）
- 产品页点击：A Hub/Spoke → PDP 的点击（事件追踪或 GA4 路径）
- 加购：PDP 加购数
- 订单转化：PDP 关联订单数与收入、AOV
- 注意：当前 GA4 收入追踪覆盖率 77.7%（2026-11-14 日报），转化数据以 Shopify 为准

### 10.3 GEO（独立于自然流量）
- 按 `geimori_gifting_geo_baseline.md` 的 G01-G08 测试组：上线前基线 → 上线后 14/30 天同设置复测
- 指标：品牌提及率、产品推荐率、正确信息率、来源引用率、购买链接率、竞品对照
- **归因约束**：GEO 指标变化只能描述"AI 回答层面的变化"；自然流量增长不能归因于 GEO 优化，须用 GSC 数据分别说明

### 10.4 报告节奏
- 每篇上线后 14 天：GSC 快照 + GEO 复测 + 转化初值
- 每月：Cluster 整体复盘（Top queries、转化、内链修正建议）

---

## 11. 未核验项（BLOCKED，不得写成已完成）

- GSC 权限与 90 天基线：BLOCKED
- 现有页真实排名词/权重：BLOCKED（影响内链优先级与 Spoke 排序）
- T38 Gen2 预售/交付状态：BLOCKED（产品页限流，需人工确认）
- 2026 圣诞配送能力/最后下单日：BLOCKED（无物流后台数据；正文只写"以官网结算页配送估算为准"）
- 后台库存数量/区域供货：BLOCKED（无 Shopify Admin 权限）
- 月搜索量数据（全部关键词）：BLOCKED（无可靠工具）
