# Geimori Research ↔ ChatGPT 协作变更日志

> 用途：让每日 Blog 任务（北京时间 06:00）快速识别"本目录新增/变更了什么、该以什么为准"。
> 读取建议：先看本文件，再按需读对应文档；写博客前用 Shopify 实时内容核实事实。
> 事实优先级：**官网 PDP（产品详情页）> 本文档 > 第三方评测**。清理清单中的待办项 = 待核实，不是已确认错误。

---

## 2026-11-21（首版，4 个 commit）

### 新增文档（entity-topical-map/）
1. **Geimori_Entity_Topical_Map_v1_20261121.md** — Geimori 实体定义 + 7 Universe 主题地图
   - 核心声明：Geimori is a precision coffee grinder brand offering electric conical and flat burr grinders for home espresso and filter coffee.
   - 差异化属性（PDP 口径）：GU63=80 RPM/100W DC、GU38=170 RPM/80W DC、GU64=800-1200 RPM/BLDC、<0.1g 残粉（with bellows）、等离子防静电、单剂量。
   - 覆盖状态：✅ 已有 / 🆕 选题推荐未写 / ⚠️ 缺专文。
2. **Geimori_Brand_Consensus_Audit_v1_20261121.md** — 外部描述一致性审计 v1.1
   - 官网 RPM 口径已统一（PDP 为准），7/27 澄清页已处理 110 RPM 旧值。
   - 外部残留旧值：Amazon 标题仍 110 RPM、ashgrind 9/25 仍 110 RPM、早期评测 190/110 RPM。
   - 写作注意：引用转速一律用 PDP 口径（80/170），不要引用第三方旧值。
3. **Geimori_Cleanup_Checklist_20261121.md** — 官网 + Amazon 清理清单
   - A1-A5（Amazon）：GU63 标题 110→80、GU38 190→170 等（运营待办，未核实前勿当已确认事实写入）。
   - W1-W7（官网）：GU78 停售区块清理、GU38 typo、retention 声明限定、刀盘 FAQ、电机类型、filter 定位。

### 对 Blog 写作的直接要求
- GU63/GU38 转速一律写 **80 RPM / 170 RPM**（PDP）。
- GU78 视为**停售/legacy**，不当作在售产品推荐；若官网页面未清理，以 Shopify 实时状态为准。
- retention 表述建议带限定（"with bellows, on new burrs"），避免绝对化承诺。
- 防重复写作：先对照 Entity Map 的覆盖状态与已有文章列表再动笔。

### 反馈回路
- 写作或核实中发现新的规格冲突 / 官网页面残留旧值 → 反馈给我方，更新本日志与清理清单。
- 本日志每次更新都会 push 到 main，链接不变。

## 2026-11-22（commit 待定）

### 新增：GSC 长查询「顶部直接回答」候选清单（Geimori_GSC_LongQuery_DirectAnswer_20261122.md）
- 技巧：GSC 查询筛选正则 `^(?:\S+\s+){7,}\S+$`（8 词以上长查询 ≈ 用户拿去问 ChatGPT 的问题）。
- 筛选逻辑：挑展示多、点击少的，在已有排名页面顶部直接回答。
- 数据：8856 条 query → 长查询 1546 条 → 高展示低点击候选 43 条 → 匹配已有页面 11 组。
- **对 Blog 写作的直接要求**：
  1. **咖啡因系列（28 条，14,220 imp）不处理、不新建、不优化**（2026-11-22 用户决策：信息型流量，有点击无转换，与磨豆机产品无管理关系）。
  2. 产品/设备相关长查询（stepless 调节、brewing methods、portafilter、espresso beans、descale）**不要重复新建页面**，优先在现有页面顶部补「直接回答」块。
  3. 真正强相关仅 1 条：`is stepless adjustment necessary for dialing in espresso`（228 imp / pos 4.0，已有 stepless 专文）——如有新长查询可补充。
  3. 未匹配的新长问题（如德语/越南语长句）可作新选题。
- 反馈回路：若写作中发现新长查询未覆盖，反馈给我方更新清单。
