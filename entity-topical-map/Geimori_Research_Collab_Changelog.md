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
