# Geimori 送礼主题规划 v2.0 — 28 篇选题逐条审核矩阵（Audit）

> 站点：mywirsh.com ｜ 审核日期：2026-11-16 ｜ 依据：官网 Shopify JSON 实时核验 + content_publisher.db（216 篇已发布）+ GEO-2026-11-01 基线 + 送礼 SERP/Reddit 证据采集（子 Agent，2026-11-16）
> 结论标注：**VERIFIED**（可追溯证据）/ **ESTIMATED**（明确估算方法）/ **HYPOTHESIS**（待验证判断）/ **BLOCKED**（缺数据或权限）
> 本矩阵覆盖原 28 篇全部选题，逐篇 17 字段。SERP 前 10 明细见 `geimori_gifting_keyword_serp_map.csv`。

---

## 0. 关键背景（审核前必读）

### 0.1 现有内容资产快照（VERIFIED，来源 content_publisher.db 2026-11-16）

- 已发布文章：**216 篇**（coffee-facts / buying-guide / external-reviews / recipes 四类）。
- **承担"型号选择/Finder"功能的现有页**（重要，Gift Finder 决策前提）：
  - `geimori-grinder-flavor-comparison` — "More Body or More Clarity? Which Geimori Grinder Fits Your Taste?"（2026-10-16）
  - `gu38-vs-gu63-vs-t38-plus-review` — "GU38 vs GU63 vs T38 Plus: Which Geimori Grinder Fits Your Workflow?"（2026-09-21）
  - ⚠️ 用户指令提到的 `which-geimori-grinder-is-right-for-you` 在 216 篇库中**未找到该 URL**（VERIFIED：db 无此 slug）；线上若存在则超出本库范围（BLOCKED）。上述两篇实际承担 Finder 功能。
- **送礼/节日现有文**（10+ 篇，多为意式咖啡机视角）：
  - Father's Day Gift Guide（2026-06-12，`coffee-facts/fathers-day-coffee-gift-guide`）
  - Mother's Day Gift Guide（2026-04-30，`coffee-facts/the-perfect-mother-s-day-gift-guide`）
  - The Ultimate Holiday Gift Guide for the Coffee Aficionado（2025-10-25，`coffee-facts/the-ultimate-holiday-gift-guide-for-the-coffee-aficionado`）★A 资产 REFRESH 对象
  - Christmas Gift featuring Wirsh Espresso Machine（2024-12-13）、Thanksgiving（2024-11-21）、Best Father's Day Gift（2024-06-10）、Valentine's ×2（2024-02-05 / 2023-02-04）等旧文
- **高频相关自购指南**（送礼文必须差异化，禁止重复技术内容）：
  - `quiet-coffee-grinder-small-apartment`（2026-11-10）
  - `hand-grinder-vs-electric-grinder-upgrade`（2026-10-06）
  - `when-is-a-grinder-upgrade-actually-worth-it`（2026-10-05）
  - `what-actually-makes-a-coffee-grinder-good-for-espresso`（2026-10-05）
  - `best-coffee-grinder-for-pour-over-what-matters`（2026-11-13）
  - `camping-coffee-setup-guide-fresh-coffee-outdoors-with-geimori-t38...`（2026-06-25，T38 无线便携场景）
  - `flat-burr-grinder-buying-guide-2026`（2026-10-25）、`geimori-gu63-vs-df54-vs-fellow-opus-2-vs-baratza-encore-esp-pro`（2026-10-04，Under $300 自购对比）
  - `where-do-wirsh-geimori-orders-ship-from`（2026-10-31，配送信息参考）

### 0.2 产品事实（详见 `geimori_gifting_product_factcheck.md`，全部 VERIFIED 2026-11-16 官网实时）

GU38 **$179.99**（划线 $249.99）｜GU63 **$269.99**（划线 $299.99）｜GU64 Gen2 **$399.99**（划线 $499.99）｜T38 Plus **$149.99**（划线 $199.99，插电便携电动，非手摇）｜T38 Gen2 **$129.99 预售**（无线电池电动，价格 ESTIMATED / 预售状态 BLOCKED）｜GU78 **停售**。

### 0.3 GEO 基线（详见 `geimori_gifting_geo_baseline.md`）

24 runs / 12 prompts（P01-P12 全购买意图，无送礼）｜Geimori 提及 41.7%（正 2/负 8）｜产品推荐率近 0（GU63 0 / GU64 2 提及 1 推荐）｜竞品 Eureka 14 / DF64 12 / DF54 11 / Baratza 6 — 全部 VERIFIED；原始 run 明细不在本地库（BLOCKED）。

### 0.4 送礼 SERP 与 Reddit 证据（2026-11-16 已回填）

来源：`gift_serp_reddit_evidence_2026-11-16.md`（404 行，90 个真实 URL，子 Agent 采集）+ `geimori_gifting_keyword_serp_map.csv`（19 词 SERP 地图）。

- **SERP 观察（VERIFIED，2026-11-16 采集）**：送礼类 SERP 清单文章占约 7 成，媒体评测次之，品牌博客参与度高；竞品内容站 coffeegrinderguide.com 已收录 Wirsh Geimori GU38（标 $159.99，与官网现价 $179.99 不一致，注意核对）。**编辑机会（全部 HYPOTHESIS，搜索量无证据）**：`coffee gift card vs beans vs grinder`、`what to get someone who already has a coffee grinder`、`coffee gifts for small kitchens`、`coffee gifts for her`、`under $50/$100 专文`、`gift basket DIY`、`home baristas 组合`——以上仅为"SERP 可见结果少/无美国专文"推断，不等同于已验证需求。
- **Reddit 证据（B 级，URL 真实可追溯，正文需二次确认）**：
  - 痛点①（不知对方设备）：r/Coffee `1uzedl9` "Pour Over Coffee - Newbie Gift"（2026-07-18）
  - 痛点②（已有高质量磨豆机）：r/espresso `1tdxyro` "Gifted an incredible machine but can't afford a top tier grinder…[$250]"（2026-05-15，243 分）；r/JamesHoffmann `1v8zqbi`
  - 痛点③（不懂意式/手冲区别）：r/Coffee `1uzedl9`；r/espresso `1t0x6uq`
  - 痛点④（预算有限求实用）：r/espresso `1tdxyro` / `1swo5nc` / `1t8si5e`
  - 痛点⑤（太大/复杂/不兼容）：r/espresso `1ossy47` "Hand Grinder Has to Go…"（2025-11-10）；r/Coffee `1oe6c7p`（噪音敏感）；r/CafelatRobot `1ta7u1p`（小空间）
  - 痛点⑥（旅行/露营供电）：r/espresso `1r4dt9y` "Lightweight travel grinder [$300]"（2026-02-14）；r/AeroPress `1rssdd6`（夏威夷无供电）；r/espresso `1t8si5e`（船上）
  - 痛点⑦（磨豆机/豆子/礼品卡三选一）：r/espresso `1tdxyro`；r/Coffee `1uzedl9`；r/JamesHoffmann `1v8zqbi`（直接帖子证据较弱，内容侧 roastaroma/iniciocoffee 更充分）
  - ⚠️ 使用规则：文章引用以上帖子时须带完整 URL 并按 B 级证据表述（"社区讨论中有…"），不得夸大为其共识或引用原话（未读取原文）。

---

## 1. 逐篇审核（#1–#28）

> 处理建议速览：**REFRESH**=原 URL 更新｜**NEW**=新建 URL｜**MERGE**=并入其他页，不新建｜**DEFER**=暂缓（2027 或视产能）｜**REJECT**=不建。
> 结论锚点：A=年度指南（#2）｜B=预算指南（#3）｜C=已有设备送什么（#5）｜D=便携送礼（#12）｜E=家庭吧台（#13）｜F=新手第一台（#14）。

### #1 Why a Coffee Grinder Is the Best Gift for a Coffee Lover（原🆕）
- **主要搜索意图**：信息型 + 说服型（送礼人找"为什么/值不值得送磨豆机"）
- **主关键词/相关**：coffee grinder gift；is a coffee grinder a good gift；why coffee grinder is a good gift
- **目标读者与场景**：犹豫送磨豆机 vs 其他礼物的送礼人；预算 $100+
- **已有相似文章**：无独立"为什么送磨豆机"页（VERIFIED db）；但 A 年度指南（2025-10-25）与多数清单文必含此论证
- **已有 URL**：无
- **关键词蚕食**：与 #2（A）高重叠——A 若含"为什么磨豆机是好礼物"章节则完全蚕食
- **产品页/Finder 冲突**：无（不涉及型号矩阵）
- **可验证搜索需求**：HYPOTHESIS（子 Agent SERP 采集中；"is a coffee grinder a good gift" 类疑问词证据待回填）
- **SERP 内容类型**：待 CSV（预计问答型/博客型）
- **产品商业相关性**：高（全系入口）
- **内容差异化价值**：低——论证性内容最适合做 A 的开篇章节而非独立页
- **GEO 问答适配度**：高（G07 直接命中）
- **建议处理**：**MERGE 进 A（#2）** 作为开篇章节 + FAQ；仅在 SERP 显示强独立疑问词时再评估
- **推荐目标 URL**：无（并入 A 的 URL）
- **决策理由与证据**：与年度指南同意图、同读者，独立页收益低于模块化；避免同站两页争同一疑问词。证据：db 216 篇无独立页（VERIFIED）；A 为 REFRESH 对象（VERIFIED）

### #2 The Ultimate Coffee Gift Guide 2026–2027（原🔄）
- **主要搜索意图**：商业调查型（年度送礼大清单，Hub）
- **主关键词/相关**：best gifts for coffee lovers；coffee gift guide；christmas coffee gifts（季词）
- **目标读者与场景**：所有送礼人；全预算全场景
- **已有相似文章**：**是** — The Ultimate Holiday Gift Guide for the Coffee Aficionado（2025-10-25）
- **已有 URL**：https://mywirsh.com/blogs/coffee-facts/the-ultimate-holiday-gift-guide-for-the-coffee-aficionado
- **关键词蚕食**：A 与全部送礼页是 Hub 关系，不视为蚕食；但须吸收 #1/#4/#17/#24/#25/#27 的内容点，避免子页重复
- **产品页/Finder 冲突**：无；A 作为 Hub 应链接 Finder 相关页与产品页
- **可验证搜索需求**：VERIFIED（竞品 driproast/RoastyCoffee/Corner Coffee Store 等清单文均在该流量池；详见 CSV）
- **SERP 内容类型**：清单型（媒体/品牌年度指南为主）
- **产品商业相关性**：极高（全系 Hub）
- **内容差异化价值**：高（REFRESH 后成为站点送礼主题枢纽）
- **GEO 问答适配度**：高（G01/G06/G07/G08 的引用来源页）
- **建议处理**：**REFRESH（Immediate 组）** — 原 URL 重写为 2026 版年度送礼指南，保留 slug 不迁移
- **推荐目标 URL**：`https://mywirsh.com/blogs/coffee-facts/the-ultimate-holiday-gift-guide-for-the-coffee-aficionado`（保留原 URL，内容扩展为年度指南）
- **决策理由与证据**：已有排名/外链的旧文优先原 URL 更新（用户规则）；db 确认该 URL 存在且 2025-10-25 发布（VERIFIED）；内容需按 0.2 正确价格重写（v1.0 定价错误修复点）

### #3 Coffee Gift Guide by Budget: $25 to $500+（原🆕）
- **主要搜索意图**：商业调查型（按预算选礼）
- **主关键词/相关**：coffee gifts by budget；coffee gifts under $100；coffee gifts under $300；coffee gifts under $50
- **目标读者与场景**：预算敏感的送礼人；同事/家人/伴侣分层
- **已有相似文章**：无"送礼预算指南"（VERIFIED）；有自购视角 `best-espresso-grinders-under-300`（2026-10-04，4 款对比，非送礼）与 `how-much-does-a-large-conical-burr-grinder-cost`（2026-10-04）
- **已有 URL**：无
- **关键词蚕食**：v1.0 #24（Under $100）与 #25（Under $300）与 B 完全重叠 → 按用户要求合并进 B，不拆
- **产品页/Finder 冲突**：预算分层须与 0.2 实时价格一致（v1.0 错误：GU38 入 $50-100、T38 Plus 称手摇入 $25-50、GU64 入 $300 档属边界）→ **修正分层**
- **可验证搜索需求**：VERIFIED（预算词在 SERP 高密度，见 CSV）
- **SERP 内容类型**：清单型（媒体预算清单）
- **产品商业相关性**：高（每档对应产品/配件/非品牌选项）
- **内容差异化价值**：高（B 是 A 的核心支持页）
- **GEO 问答适配度**：高（G01/G06 命中）
- **建议处理**：**NEW（B 资产，Immediate 组）**；同时吸收 #24/#25（不拆 Under $100 / Under $300）
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/coffee-gift-guide-by-budget`
- **决策理由与证据**：用户明确"一个预算指南覆盖主要价格层级"；价格档位以 11-16 官网实时价为准（VERIFIED）：<$50（配件/豆/杯/手摇等非品牌）｜$50-100（配件组合/订阅，Geimori 无此档磨豆机，如实写）｜$100-150（T38 Gen2 $129.99 预售、T38 Plus $149.99 下沿）｜$150-200（T38 Plus、GU38 $179.99）｜$200-300（GU63 $269.99）｜$300+（GU64 Gen2 $399.99）

### #4 Coffee Gifts for Every Type of Coffee Drinker（原🆕）
- **主要搜索意图**：信息型（按喝法/身份分类）
- **主关键词/相关**：coffee gifts for coffee snobs；coffee gifts by drinker type
- **目标读者与场景**：不确定收礼人具体需求的送礼人
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 A（按人/喝法速查章节）、#6-9（关系型）重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（"for every type" 类词低频）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中
- **内容差异化价值**：低——分类逻辑是 A 的标准章节
- **GEO 问答适配度**：中
- **建议处理**：**MERGE 进 A（#2）** 的"按喝法/按人"章节；REJECT 独立页
- **推荐目标 URL**：无
- **决策理由与证据**：A 必然包含分类章节；独立页与 A 蚕食且无独立强词（HYPOTHESIS）；用户规则"不以关键词不同作为独立建页理由"

### #5 What to Buy a Coffee Lover Who Already Has Everything（原🆕）
- **主要搜索意图**：商业调查型 + 痛点型（收礼人装备已满）
- **主关键词/相关**：gifts for coffee lovers who have everything；what to buy a coffee lover who has everything；coffee gifts for someone who already has a grinder
- **目标读者与场景**：送礼对象已有设备/高质量磨豆机的送礼人；升级、配件、体验礼
- **已有相似文章**：**部分重叠** — `when-is-a-grinder-upgrade-actually-worth-it`（2026-10-05，自购升级视角）与 `what-actually-makes-a-coffee-grinder-good-for-espresso`（2026-10-05）
- **已有 URL**：见上（自购视角，非送礼）
- **关键词蚕食**：与 upgrade 文在"什么时候值得升级"逻辑上重叠 → 差异化：C 聚焦"送什么"决策，升级技术细节互链引用不重复
- **产品页/Finder 冲突**：无；须避免"所有人都需要升级磨豆机"绝对化（用户规则）
- **可验证搜索需求**：VERIFIED（Reddit 高频痛点"already have everything"，子 Agent 具体帖证据待回填；SERP 词证据见 CSV）
- **SERP 内容类型**：清单型 + 社区讨论
- **产品商业相关性**：高（升级/配件/非磨豆机选项均带转化）
- **内容差异化价值**：高（C 是 6 核心资产之一，直接解决送礼死结）
- **GEO 问答适配度**：极高（G02 直接命中）
- **建议处理**：**NEW（C 资产，Immediate 组）**；吸收 #26（礼品卡 vs 装备）为平衡章节
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/coffee-gifts-for-someone-who-already-has-a-grinder`
- **决策理由与证据**：用户明确 C 为核心资产；Reddit ②痛点需求真实（子 Agent 帖子证据待回填）；与已有 upgrade 文差异化方向明确（送礼决策 vs 自购升级）

### #6 Best Coffee Gifts for Dad（原🔄）
- **主要搜索意图**：商业调查型（关系型送礼）
- **主关键词/相关**：coffee gifts for dad；father's day coffee gifts（季词）
- **目标读者与场景**：给父辈/丈夫送礼
- **已有相似文章**：**是** — Father's Day Gift Guide（2026-06-12，较新）与 Best Father's Day Gift（2024-06-10，旧）
- **已有 URL**：`coffee-facts/fathers-day-coffee-gift-guide`；`coffee-facts/best-father-s-day-gift-gift-idea-for-dad`
- **关键词蚕食**：两篇 Father's 文已互相重叠；再建通用 Dad 页将三重复
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：VERIFIED（"coffee gifts for dad" 为季词，SERP 证据见 CSV）
- **SERP 内容类型**：清单型
- **产品商业相关性**：中-高
- **内容差异化价值**：中（2026-06-12 文较新，更新价值有限）
- **GEO 问答适配度**：中
- **建议处理**：**REFRESH（Holiday 组，可选）** — 更新 2026-06-12 Father's Day 文为通用"父辈咖啡礼物"，保留 URL；旧 2024 文不删（用户禁止删除），不互链主力
- **推荐目标 URL**：`coffee-facts/fathers-day-coffee-gift-guide`（保留）
- **决策理由与证据**：已有较新 URL，避免新建竞争页（VERIFIED）；父情节文是"真正需要年度更新"的类型

### #7 Best Coffee Gifts for Mom（原🔄）
- **主要搜索意图**：商业调查型（关系型送礼）
- **主关键词/相关**：coffee gifts for mom；mother's day coffee gifts
- **目标读者与场景**：给母辈/伴侣送礼
- **已有相似文章**：**是** — Mother's Day Gift Guide（2026-04-30）
- **已有 URL**：`coffee-facts/the-perfect-mother-s-day-gift-guide`
- **关键词蚕食**：与 #6/#8/#9 关系型词族重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：VERIFIED（SERP 证据见 CSV）
- **SERP 内容类型**：清单型
- **产品商业相关性**：中-高
- **内容差异化价值**：中
- **GEO 问答适配度**：中
- **建议处理**：**REFRESH（Holiday 组，可选）** — 更新 2026-04-30 文为通用"母辈咖啡礼物"，保留 URL
- **推荐目标 URL**：`coffee-facts/the-perfect-mother-s-day-gift-guide`（保留）
- **决策理由与证据**：同 #6；保留 URL 更新优先于新建

### #8 Best Coffee Gifts for Her（原🆕）
- **主要搜索意图**：商业调查型（关系型）
- **主关键词/相关**：coffee gifts for her；coffee gifts for girlfriend；coffee gifts for wife
- **目标读者与场景**：伴侣送礼
- **已有相似文章**：无独立 Her 页（VERIFIED）；但 Valentine's 旧文（2024-02-05/2023-02-04）部分覆盖
- **已有 URL**：无
- **关键词蚕食**：与 #7（Mom）、#9（Him）边界模糊（同一收礼人群体的性别标签）
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（性别标签词 SERP 有量，但价值待确认）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中
- **内容差异化价值**：低（性别标签差异不足以支撑独立页）
- **GEO 问答适配度**：低
- **建议处理**：**MERGE 进 A/B**（A"按收礼人"章节或 B 预算场景）；REJECT 独立页
- **推荐目标 URL**：无
- **决策理由与证据**：关系型词族 4 篇（#6-9）不应各建一页互相蚕食；统一由 A 章节 + B 场景承载（用户规则：不以关键词不同独立建页）

### #9 Best Coffee Gifts for Him（原🆕）
- **主要搜索意图**：商业调查型
- **主关键词/相关**：coffee gifts for him；coffee gifts for boyfriend/husband
- **目标读者与场景**：伴侣送礼
- **已有相似文章**：无独立 Him 页（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 #6/#8 重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（同 #8）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中
- **内容差异化价值**：低
- **GEO 问答适配度**：低
- **建议处理**：**MERGE 进 A/B**；REJECT 独立页
- **推荐目标 URL**：无
- **决策理由与证据**：同 #8；如 SERP 证据强（子 Agent 回填后），最多允许合并为 A 内"伴侣礼物"锚点章节，不新建 URL

### #10 Coffee Gifts for Coworkers & Office Secret Santa（原🆕）
- **主要搜索意图**：商业调查型（低预算交换礼）
- **主关键词/相关**：coffee gift exchange coworker；secret santa coffee gift；coffee gifts under $25
- **目标读者与场景**：办公室交换/同事礼；$25-50 预算
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 B（预算指南）低预算章节重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（低频；子 Agent SERP 待回填）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：低-中（配件为主，磨豆机不入此档）
- **内容差异化价值**：低
- **GEO 问答适配度**：低
- **建议处理**：**MERGE 进 B（#3）** 的"低成本实用礼/办公室交换"章节；REJECT 独立页
- **推荐目标 URL**：无
- **决策理由与证据**：$25-50 档在 Geimori 无磨豆机产品，独立页转化弱；B 章节可承载（ESTIMATED）

### #11 Coffee Gifts for Students & Small Spaces（原🆕）
- **主要搜索意图**：商业调查型（小空间/宿舍）
- **主关键词/相关**：coffee gifts under $100 dorm；coffee gifts for small kitchens；compact coffee grinder gift
- **目标读者与场景**：学生/小厨房收礼人
- **已有相似文章**：**部分重叠** — `quiet-coffee-grinder-small-apartment`（2026-11-10，小空间噪音自购视角）
- **已有 URL**：`buying-guide/quiet-coffee-grinder-small-apartment`
- **关键词蚕食**：与 quiet 文、G08（小厨房）重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（dorm 词低频；G08 需求待验证）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中（T38 系列/GU38 适配小空间）
- **内容差异化价值**：低-中
- **GEO 问答适配度**：中（G08 命中）
- **建议处理**：**DEFER（2027 Evergreen 可选）**；或并入 F（新手小空间章节）；不占 Holiday 产能
- **推荐目标 URL**：暂不分配
- **决策理由与证据**：小空间送礼是真实场景（G08），但独立页与 quiet 文/GEO 测试重叠，优先级低于核心 6 资产（HYPOTHESIS）

### #12 Best Portable Coffee Grinder Gifts for Travelers & Campers（原🆕）
- **主要搜索意图**：商业调查型（场景型送礼）
- **主关键词/相关**：portable coffee grinder gift；travel coffee gifts；best portable electric coffee grinder；camping coffee grinder
- **目标读者与场景**：给旅行者/露营者/通勤者送礼；供电受限场景
- **已有相似文章**：**部分重叠** — `camping-coffee-setup-guide`（2026-06-25，T38 系列露营自购/使用视角）；`geimori-t38-reviews-portable-grinder-video-tests`（2026-07-22）
- **已有 URL**：`buying-guide/camping-coffee-setup-guide-fresh-coffee-outdoors-with-geimori-t38-geimori-t38-plus-citaly-go-1`
- **关键词蚕食**：与 camping 文场景重叠 → D 聚焦"送礼决策"（送谁/送哪款/三类型区别），技术内容互链
- **产品页/Finder 冲突**：无；**必须正确区分**：T38 Gen2=无线电池电动（$129.99 预售）、T38 Plus=插电便携电动（$149.99）、真手摇=非品牌（如 1Zpresso）——v1.0 把 T38 Plus 称手摇为严重错误，本页是纠错主阵地
- **可验证搜索需求**：VERIFIED（portable/travel 词 SERP 证据见 CSV；Reddit ⑥供电限制痛点）
- **SERP 内容类型**：清单型 + 评测
- **产品商业相关性**：高（T38 双型号）
- **内容差异化价值**：高（D 是 6 核心资产之一 + 产品定位纠错）
- **GEO 问答适配度**：极高（G05 直接命中）
- **建议处理**：**NEW（D 资产，Immediate 组）**；吸收 #19（三类型对比）为章节
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/portable-coffee-grinder-gifts-for-travelers-campers`
- **决策理由与证据**：用户明确 D 为核心资产；T38 系列便携定位（VERIFIED：官网 "Portable Plug-in Grinder" / 2025-08-08 官方发布文无线电动）；Reddit ⑥供电限制真实帖（r/espresso `1r4dt9y` "Lightweight travel grinder [$300]" 2026-02-14 + r/AeroPress `1rssdd6` 夏威夷无供电 + `1t8si5e` 船上，B 级）；SERP `best portable electric coffee grinder for travel` 高度聚合供给充足=品牌站直接参与空间小，须送礼场景差异化

### #13 Coffee Gifts for Home Baristas & Espresso Enthusiasts（原🆕）
- **主要搜索意图**：商业调查型（意式用户送礼）
- **主关键词/相关**：espresso grinder gift；gifts for home barista；coffee gifts for espresso lovers；best espresso grinder gift
- **目标读者与场景**：给已有意式机/拉花玩家送礼；升级与兼容性
- **已有相似文章**：**部分重叠** — `is-the-gu63-the-right-grinder-for-your-home-espresso-setup`（2026-07-27）、`best-coffee-grinder-for-lattes`（2026-11-12）、`what-actually-makes-a-coffee-grinder-good-for-espresso`（2026-10-05，均自购视角）
- **已有 URL**：见上
- **关键词蚕食**：与意式自购指南重叠 → E 聚焦"送意式玩家的升级/兼容"送礼决策，技术细节互链
- **产品页/Finder 冲突**：无；兼容性提醒（收礼人已有机器/手柄/刀盘）
- **可验证搜索需求**：VERIFIED（espresso 送礼词 SERP 证据见 CSV；EgCoffee "espresso gifts under $100" 竞品存在）
- **SERP 内容类型**：清单型
- **产品商业相关性**：高（GU63/GU64 主力）
- **内容差异化价值**：高（E 是 6 核心资产之一）
- **GEO 问答适配度**：极高（G04 直接命中）
- **建议处理**：**NEW（E 资产，Immediate 组）**
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/coffee-gifts-for-home-baristas-espresso-lovers`
- **决策理由与证据**：用户明确 E 为核心资产；G04 问题在 AI 问答中高频（ESTIMATED）；差异化方向明确

### #14 Coffee Gifts for Beginners: The First Grinder Gift（原🆕）
- **主要搜索意图**：商业调查型（新手送礼）
- **主关键词/相关**：first coffee grinder gift；beginner coffee gifts；best first coffee grinder；coffee grinder for beginners gift
- **目标读者与场景**：给从预磨粉/刀片机起步的新手送礼
- **已有相似文章**：db 无 "first grinder" 指南（VERIFIED）；`topic_history.json` 有"第一台磨豆机"选题评分 82.6（周报候选，非已发布文章，BLOCKED 线上确认）；`what-actually-makes-a-coffee-grinder-good-for-espresso`（2026-10-05）部分概念重叠
- **已有 URL**：无
- **关键词蚕食**：与 F 与未来可能发布的"第一台磨豆机"自购指南需区分（F=送礼视角；自购=选型视角）——写前复查线上
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：VERIFIED（beginner/first 词 SERP 证据见 CSV；Reddit ⑦新手升级痛点）
- **SERP 内容类型**：清单型 + 指南型
- **产品商业相关性**：高（GU38/GU63 入门定位）
- **内容差异化价值**：高（F 是 6 核心资产之一）
- **GEO 问答适配度**：极高（G03 直接命中）
- **建议处理**：**NEW（F 资产，Immediate 组）**
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/first-coffee-grinder-gift-beginner-guide`
- **决策理由与证据**：用户明确 F 为核心资产；G03 命中；写作前需复查"第一台磨豆机"选题是否已发布（BLOCKED 标注）

### #15 Coffee Gifts for Pour-Over & Filter Lovers（原🆕）
- **主要搜索意图**：商业调查型（手冲送礼）
- **主关键词/相关**：pour over coffee gifts；coffee gifts for pour over lovers；filter coffee gifts
- **目标读者与场景**：给手冲/滤泡爱好者送礼
- **已有相似文章**：**是** — `best-coffee-grinder-for-pour-over-what-matters`（2026-11-13，自购）；`the-art-of-pour-over-coffee`（2025-08-01）
- **已有 URL**：`buying-guide/best-coffee-grinder-for-pour-over-what-matters`
- **关键词蚕食**：与 pour-over 自购指南重叠（送礼 vs 自购意图不同，但型号推荐高度重合）
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：VERIFIED（pour over 词有量，但"送礼"修饰词证据待 CSV）
- **SERP 内容类型**：清单型
- **产品商业相关性**：中-高（GU63/GU64）
- **内容差异化价值**：中（pour-over 送礼角度与 B 场景章节重复）
- **GEO 问答适配度**：中
- **建议处理**：**DEFER（第二轮候选）** — 2027 视产能；或并入 B 场景章节
- **推荐目标 URL**：暂不分配
- **决策理由与证据**：用户第二轮候选含 Pour-Over Coffee Gifts；与 2026-11-13 自购文太近（发布不足一周），短期内做送礼版会蚕食自己（ESTIMATED）

### #16 Quiet Coffee Grinder Gifts for Apartments & Offices（原🆕）
- **主要搜索意图**：商业调查型（静音送礼）
- **主关键词/相关**：quiet coffee grinder gift；quiet coffee grinder for apartment
- **目标读者与场景**：给公寓住户/办公室送礼；噪音敏感
- **已有相似文章**：**是** — `quiet-coffee-grinder-small-apartment`（2026-11-10）
- **已有 URL**：`buying-guide/quiet-coffee-grinder-small-apartment`
- **关键词蚕食**：严重——现有页已覆盖"公寓噪音选磨豆机"；送礼差异仅限 CTA 视角
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（"quiet coffee grinder gift" 低证据）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中（GU63 静音卖点）
- **内容差异化价值**：低
- **GEO 问答适配度**：低
- **建议处理**：**REJECT 独立页 / DEFER**；静音送礼场景并入 B 或 D 的一个 FAQ 段，互链现有 quiet 文
- **推荐目标 URL**：无
- **决策理由与证据**：现有页 2026-11-10 刚发布（VERIFIED），独立送礼页蚕食且证据不足（HYPOTHESIS）

### #17 Christmas Coffee Gift Guide 2026（原🆕）
- **主要搜索意图**：商业调查型（季节性大流量）
- **主关键词/相关**：christmas coffee gifts；coffee gifts for christmas；christmas gift guide coffee
- **目标读者与场景**：圣诞季送礼人（2026-11 底–12 月）
- **已有相似文章**：**是** — Holiday Gift Guide（2025-10-25，A 对象）；Christmas 旧文（2024-12-13，意式机视角）
- **已有 URL**：`coffee-facts/the-ultimate-holiday-gift-guide-for-the-coffee-aficionado`；`coffee-facts/how-to-choose-the-perfect-christmas-gift-a-guide-featuring-the-wirsh-espresso-machine`
- **关键词蚕食**：A（REFRESH 为 2026 年度版）与 Christmas 2026 页高度重叠——A 的 Holiday 版即可承接圣诞意图
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：VERIFIED（christmas coffee gifts 为强季词；SERP 证据见 CSV）
- **SERP 内容类型**：清单型（媒体圣诞指南）
- **产品商业相关性**：极高（全系 + 组合礼）
- **内容差异化价值**：高（但可由 A 承载）
- **GEO 问答适配度**：中（季词在 AI 问答低频）
- **建议处理**：**MERGE 进 A（Holiday 版）** — 在 11 月底前以"2026 Holiday/Christmas 版"刷新 A，不新建独立 Christmas URL；若 SERP 证据显示 christmas 独立词量远超 A 现有排名，再在 12 月评估独立页
- **推荐目标 URL**：A 的 URL（暂不新建）
- **决策理由与证据**：避免 A 与 Christmas 页互相蚕食；A 的 slug 已含 holiday（VERIFIED）；2026 圣诞内容的即时性由 A 的 Holiday 版满足（HYPOTHESIS 待 SERP 最终确认）

### #18 12 Days of Coffee Gifts: A Gift Ideas Advent Calendar（原🆕）
- **主要搜索意图**：娱乐/内容营销型（低 SEO 价值）
- **主关键词/相关**：coffee advent calendar gift ideas（低频）
- **目标读者与场景**：圣诞内容读者
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：无（但无需求支撑）
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（advent calendar 词与"咖啡倒计时日历"混淆，非送礼决策词）
- **SERP 内容类型**：清单型
- **产品商业相关性**：低（12 个点子稀释转化）
- **内容差异化价值**：低（制作成本高、季节窗口窄）
- **GEO 问答适配度**：低
- **建议处理**：**REJECT**（本批不建；无证据支撑独立页）
- **推荐目标 URL**：无
- **决策理由与证据**：制作成本/收益比差；与送礼决策意图脱节（ESTIMATED）；用户规则"不为凑篇数制造文章"

### #19 Electric vs Manual Grinder: Which Makes a Better Gift?（原🆕）
- **主要搜索意图**：商业调查型（类型对比送礼）
- **主关键词/相关**：electric vs manual grinder gift；electric vs plug-in vs manual grinder
- **目标读者与场景**：送礼人分辨三种便携类型
- **已有相似文章**：**是** — `hand-grinder-vs-electric-grinder-upgrade`（2026-10-06，自购升级）
- **已有 URL**：`buying-guide/hand-grinder-vs-electric-grinder-upgrade`
- **关键词蚕食**：与手摇/电动对比文重叠（送礼差异弱）
- **产品页/Finder 冲突**：无；**但三类型区分（无线/插电/手摇）是产品教育刚需**（T38 Gen2 vs T38 Plus vs 1Zpresso）
- **可验证搜索需求**：HYPOTHESIS（"electric vs manual" 词 SERP 有量；"gift" 修饰待 CSV）
- **SERP 内容类型**：对比/指南型
- **产品商业相关性**：中-高（T38 双型号）
- **内容差异化价值**：中（类型区分价值 > 送礼决策价值）
- **GEO 问答适配度**：中
- **建议处理**：**MERGE 进 D（#12）** 的"三种便携类型怎么选"章节；REJECT 独立页
- **推荐目标 URL**：无（并入 D）
- **决策理由与证据**：用户第二轮候选虽含该主题，但类型对比是 D 的必要章节，独立页与已有 hand-vs-electric 文蚕食（ESTIMATED）

### #20 Single-Dose Grinder as a Gift: Why Low Retention Wins（原🆕）
- **主要搜索意图**：产品卖点翻译型（牵强）
- **主关键词/相关**：single dose grinder gift（低频）
- **目标读者与场景**：被"单剂量"卖点吸引的送礼人
- **已有相似文章**：**是** — 单剂量内容大量存在（retention/anti-static 主题多篇）
- **已有 URL**：如 `coffee-facts/gu63-review`（retention）等
- **关键词蚕食**：与单剂量/残留主题全部重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（"single dose gift" 无证据）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中
- **内容差异化价值**：低（卖点翻译不适合独立页）
- **GEO 问答适配度**：低
- **建议处理**：**REJECT 独立页**；"单剂量为什么适合送礼"一句话融入 B/A 产品段落
- **推荐目标 URL**：无
- **决策理由与证据**：无独立搜索意图（HYPOTHESIS）；用户规则禁止卖点堆砌文

### #21 How to Build a Coffee Gift Basket with a Grinder（原🆕）
- **主要搜索意图**：商业调查型（礼物篮组装）
- **主关键词/相关**：coffee gift basket ideas；coffee gift basket with grinder；build a coffee gift basket
- **目标读者与场景**：送礼人组装篮子（配件+豆+杯+小型磨豆机）
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 B（配件组合）部分重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：VERIFIED（coffee gift basket 为真实搜索词，SERP 证据见 CSV）
- **SERP 内容类型**：清单型（媒体/博客）
- **产品商业相关性**：中（配件为主，可含 T38/GU38 小机器）
- **内容差异化价值**：中-高（basket 是独立需求场景）
- **GEO 问答适配度**：中
- **建议处理**：**DEFER（第二轮候选 / Evergreen 2027）** — 若 SERP 证据强则提前；产品植入以配件+小型磨豆机为主
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/how-to-build-a-coffee-gift-basket`（2027 分配）
- **决策理由与证据**：真实搜索需求（VERIFIED）但非 6 核心资产；Holiday 产能优先 A-F；2027 Evergreen 做（ESTIMATED）

### #22 Geimori Gift Finder: Which Model for Which Person（原🆕）
- **主要搜索意图**：商业调查型（品牌内选型）
- **主关键词/相关**：geimori grinder which model；which geimori grinder should i buy
- **目标读者与场景**：送礼人（品牌内选型号）——**与自购 Finder 读者不同但内容重叠**
- **已有相似文章**：**是（Finder 功能已存在）** — `geimori-grinder-flavor-comparison`（2026-10-16）与 `gu38-vs-gu63-vs-t38-plus-review`（2026-09-21）承担"买哪款 Geimori"功能
- **已有 URL**：`buying-guide/geimori-grinder-flavor-comparison`；`external-reviews/gu38-vs-gu63-vs-t38-plus-review`
- **关键词蚕食**：高——新 Gift Finder 若仅把型号矩阵换个送礼开头，就是第三个 Finder URL
- **产品页/Finder 冲突**：直接冲突（与现有 Finder 页争 "which geimori grinder" 词）
- **可验证搜索需求**：HYPOTHESIS（品牌词 SERP 由自有页占据；送礼修饰词无外部证据）
- **SERP 内容类型**：品牌导购
- **产品商业相关性**：高（全系）
- **内容差异化价值**：仅当决策树真正以"收礼人画像"为起点（喝法/预算/空间/频率/已有设备 → 送礼推荐）才有独立价值
- **GEO 问答适配度**：中（G01-G08 间接命中）
- **建议处理**：**DEFER 独立 URL** — 送礼选型作为 A（年度指南）的"按收礼人选型"模块实现；同时（规划层面）建议现有 Finder 页增加"送礼者"FAQ 模块（不自动执行）
- **推荐目标 URL**：暂不分配
- **决策理由与证据**：用户明确"新 Gift Finder 必须有真正独立的送礼决策逻辑，否则并入现有页"；现有 Finder 排名词/权重未核验（BLOCKED，无 GSC），新建竞争 URL 风险 > 收益（HYPOTHESIS）；送礼选型模块可在 A 内实现且零额外 URL

### #23 Espresso Machine + Grinder: The Ultimate Gift Combo（原🆕）
- **主要搜索意图**：商业调查型（组合大礼）
- **主关键词/相关**：espresso machine and grinder gift；coffee combo gift；gift set espresso machine grinder
- **目标读者与场景**：高预算送礼（结婚/圣诞大礼/新居）
- **已有相似文章**：无组合礼页（VERIFIED）；有 Wirsh 咖啡机旧文（2024-2025 多篇，意式机视角）
- **已有 URL**：无
- **关键词蚕食**：与 E（#13）部分重叠（E 可含组合章节）
- **产品页/Finder 冲突**：无；需 Wirsh 咖啡机当前产品/价格核验（BLOCKED）
- **可验证搜索需求**：HYPOTHESIS（combo 词有量；"gift" 修饰待 CSV）
- **SERP 内容类型**：清单型/品牌
- **产品商业相关性**：高（AOV 最大化）
- **内容差异化价值**：中-高（组合礼是真实送礼场景）
- **GEO 问答适配度**：中（G04 相关）
- **建议处理**：**DEFER（Evergreen 2027 可选）** 或作为 E 的"组合大礼"章节；Holiday 2026 产能不足时不做
- **推荐目标 URL**：`https://mywirsh.com/blogs/buying-guide/espresso-machine-grinder-gift-combo`（2027 分配）
- **决策理由与证据**：商业价值高但依赖 Wirsh 咖啡机当前数据（BLOCKED）；非用户指定核心资产；优先级低于 A-F（ESTIMATED）

### #24 Best Coffee Gifts Under $100（原🆕）
- **主要搜索意图**：商业调查型（预算锚点）
- **主关键词/相关**：coffee gifts under 100；best coffee gifts under $100
- **目标读者与场景**：$100 内送礼
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 B（#3）完全重叠——B 已按用户要求覆盖所有价格层级
- **产品页/Finder 冲突**：v1.0 错误（GU38 $179.99 被放入 Under $100）——若独立页必再错
- **可验证搜索需求**：VERIFIED（under $100 为高量词，SERP 证据见 CSV）
- **SERP 内容类型**：清单型
- **产品商业相关性**：中（配件/T38 边界）
- **内容差异化价值**：低（B 的锚点章节即可承接）
- **GEO 问答适配度**：高（G01 相关）
- **建议处理**：**MERGE 进 B（#3）** — 不拆独立 Under $100 页（用户明确）
- **推荐目标 URL**：无（并入 B）
- **决策理由与证据**：用户明确"一个预算指南覆盖主要价格层级，先不拆 Under $100 和 Under $300"；独立页将制造同站预算词蚕食

### #25 Best Coffee Gifts Under $300（原🆕）
- **主要搜索意图**：商业调查型（预算锚点）
- **主关键词/相关**：coffee gifts under 300；best coffee gifts under $300
- **目标读者与场景**：$300 内送礼
- **已有相似文章**：**部分重叠** — `geimori-gu63-vs-df54-vs-fellow-opus-2-vs-baratza-encore-esp-pro`（2026-10-04，标题含 Under $300 但为自购对比）
- **已有 URL**：`buying-guide/geimori-gu63-vs-df54-vs-fellow-opus-2-vs-baratza-encore-esp-pro`
- **关键词蚕食**：与 B 重叠；与已有 Under $300 自购页标题词重叠
- **产品页/Finder 冲突**：v1.0 错误（GU64 $399.99 被放入 Under $300）——B 修正后 GU63 $269.99 是唯一 <$300 磨豆机
- **可验证搜索需求**：VERIFIED（under $300 高量词；SERP 证据见 CSV）
- **SERP 内容类型**：清单型
- **产品商业相关性**：中-高
- **内容差异化价值**：低（B 锚点章节）
- **GEO 问答适配度**：高（G06 相关）
- **建议处理**：**MERGE 进 B（#3）** — 不拆独立页
- **推荐目标 URL**：无（并入 B）
- **决策理由与证据**：同 #24；用户明确不拆；GU64 不得入 Under $300（VERIFIED $399.99）

### #26 Coffee Gift Cards vs Gear: What Coffee Lovers Actually Want（原🆕）
- **主要搜索意图**：信息型/观点型（平衡讨论）
- **主关键词/相关**：coffee gift card vs gear（低频）
- **目标读者与场景**：不确定送豆/卡/装备的送礼人
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 C（#5）"已有设备送什么"重叠（礼品卡是 C 的合理选项之一）
- **产品页/Finder 冲突**：无；品牌立场风险（不能写成"别送礼品卡"营销文）
- **可验证搜索需求**：HYPOTHESIS（gift card vs gear 无独立证据）
- **SERP 内容类型**：观点/问答
- **产品商业相关性**：低-中
- **内容差异化价值**：低（平衡观点章节）
- **GEO 问答适配度**：中（G02 相关）
- **建议处理**：**MERGE 进 C（#5）** 的"礼品卡/豆/体验也是好选项"平衡章节；REJECT 独立页
- **推荐目标 URL**：无
- **决策理由与证据**：C 必须回答"送礼品卡行不行"（用户规则：已有高质量磨豆机的人可能更适合豆/卡/课程）；独立页搜索证据不足（HYPOTHESIS）

### #27 How to Choose a Coffee Gift in 5 Questions（原🆕）
- **主要搜索意图**：工具型/长尾
- **主关键词/相关**：how to choose a coffee gift；coffee gift decision guide
- **目标读者与场景**：需要快速决策框架的送礼人
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 A（决策模块）重叠
- **产品页/Finder 冲突**：与 #22 送礼选型模块重叠
- **可验证搜索需求**：HYPOTHESIS（决策框架词低频）
- **SERP 内容类型**：指南型
- **产品商业相关性**：中
- **内容差异化价值**：低（决策框架是 A 的标准模块）
- **GEO 问答适配度**：低
- **建议处理**：**MERGE 进 A（#2）** 的"5 步选礼"模块 + FAQ；REJECT 独立页
- **推荐目标 URL**：无
- **决策理由与证据**：与 #22 同源问题：决策工具应为 Hub 模块而非独立 URL（HYPOTHESIS）

### #28 Coffee Gifts for Couples & Anniversaries（原🆕）
- **主要搜索意图**：商业调查型（关系型低频）
- **主关键词/相关**：coffee gifts for couples；coffee gifts for anniversary
- **目标读者与场景**：双人/纪念日送礼
- **已有相似文章**：无（VERIFIED）
- **已有 URL**：无
- **关键词蚕食**：与 #8/#9（伴侣）重叠
- **产品页/Finder 冲突**：无
- **可验证搜索需求**：HYPOTHESIS（couples 词低频）
- **SERP 内容类型**：待 CSV
- **产品商业相关性**：中（组合礼）
- **内容差异化价值**：低
- **GEO 问答适配度**：低
- **建议处理**：**DEFER（2027 可选）**；如做则作为 A"按收礼人"章节的延伸
- **推荐目标 URL**：暂不分配
- **决策理由与证据**：低频关系型词，优先级低（HYPOTHESIS）；Holiday/Evergreen 产能优先核心资产

---

## 2. 处理决定汇总

| 处理 | 选题 | 数量 |
|---|---|---|
| **REFRESH（原 URL）** | #2（A Hub）、#6（Dad）、#7（Mom） | 3 |
| **NEW（6 核心资产）** | #3（B 预算）、#5（C 已有设备）、#12（D 便携）、#13（E 家庭吧台）、#14（F 新手） | 5 |
| **MERGE（并入其他页）** | #1→A、#4→A、#8→A/B、#9→A/B、#10→B、#16→B/D、#17→A（Holiday 版）、#19→D、#20→A/B 段落、#24→B、#25→B、#26→C、#27→A | 13 |
| **DEFER（2027 / 视产能）** | #11（F 小空间）、#15（第二轮）、#21（第二轮）、#22（模块化，不建独立 URL）、#23（Evergreen）、#28 | 6 |
| **REJECT（不建）** | #18 | 1 |

> 合计 28 篇全部处理。**第一批净新增 URL：5 个**（B/C/D/E/F）+ **REFRESH：1 个必做（#2 A）**，Dad/Mom REFRESH 可选。这是"由证据决定的篇数"，不是凑数。

---

## 3. 与 6 核心资产 A-F 的对应

| 资产 | 承载选题 | 处理 | 优先级组 |
|---|---|---|---|
| A. Ultimate Coffee Gift Guide（年度 Hub） | #2 + 吸收 #1/#4/#8/#9/#17/#27 | REFRESH | Immediate（11 月底前上线 Holiday 版） |
| B. Coffee Gifts by Budget（单一预算指南） | #3 + 吸收 #10/#16/#24/#25 | NEW | Immediate |
| C. Already Has Everything | #5 + 吸收 #26 | NEW | Immediate |
| D. Portable Coffee Grinder Gifts | #12 + 吸收 #19 | NEW | Immediate |
| E. Home Baristas | #13 | NEW | Immediate |
| F. First Coffee Grinder Gift | #14 + 吸收 #11 | NEW | Immediate |

第二轮候选：#15（Pour-Over）、#21（Gift Basket）、#22（Gift Finder 模块化）、#23（Combo）、#17 独立（仅当 SERP 证据强）——均按证据决定，非强制。

---

## 4. 审核限制与未核验项（诚实声明）

- **GSC 数据**：无 Search Console 访问权限，现有文章的真实排名词、外链、流量**未核验（BLOCKED）**——以上去重判断基于 db 标题/URL/日期与内容主题推断（ESTIMATED），正文层面逐字比对未完成（需人工/后续工具核验正文）。
- **SERP 前 10**：由子 Agent 2026-11-16 采集，部分关键词的"送礼修饰"长尾词证据待回填（HYPOTHESIS）；`keyword_serp_map.csv` 汇总。
- **Reddit 具体帖子**：子 Agent 采集中，本矩阵的痛点关联将按返回 URL 回填（待更新）。
- **T38 Gen2 预售**：产品页限流未二次确认（BLOCKED）。
- **Wirsh 咖啡机当前数据**：未核验（BLOCKED，影响 #23）。
- 所有价格以 `geimori_gifting_product_factcheck.md`（2026-11-16）为准；正文生成前必须重新读取 Shopify。
