# Geimori 官网 + Amazon 清理清单（2026-11-21）

> 来源：Brand Consensus 审计 v1.1（2026-11-21）。
> 原则：**以 PDP 为唯一权威口径**（GU63=80 RPM/100W DC，GU38=170 RPM/80W DC）。
> 每条含：位置、现状、应改为、依据、优先级。

---

## 一、Amazon（最高优先，消费者直接可见）

| # | 位置 | 现状 | 应改为 | 依据 | 优先级 |
| --- | --- | --- | --- | --- | --- |
| A1 | **GU63 商品标题**（Amazon listing 标题） | 含 "…110 RPM Cold Grind, Low Retention Grinder…" | "80 RPM Cold Grind" | bestproducts.reviews 2026-11-15 聚合的 Amazon 标题原文；官网 PDP=80 RPM | **P0** |
| A2 | **GU63 五点/描述** | 若含 110 RPM 或 96/100W 电机数字，需同步 | 80 RPM / 100W DC（与 PDP 一致） | lukemakescoffee 写 "96W/100W Brushed DC"（旧值）；以 PDP 为准 | P0 |
| A3 | **GU38 商品标题/五点/描述** | 若含 "96W DC motor at 190 RPM"（coffeegrinderguide 2026-06-03 聚合的 Amazon 文案） | 80W DC · 170 RPM | 官网 GU38 PDP=80W/170 RPM | P0 |
| A4 | **GU38 电子说明书（Amazon 附件）** | manuals.plus 收录旧版手册写 "96W High-efficiency DC motor, 190 RPM" | 更新为 80W/170 RPM 版本手册 | 官网 PDP=170 RPM | P1 |
| A5 | **GU63/GU38 商品标题品牌口径** | 标题写法多样（"Wirsh Geimori…"） | 统一 "Geimori" 品牌名 + 型号，口径与官网一致 | Brand Consensus：precision coffee grinder brand（Wirsh LLC 运营） | P2 |

---

## 二、官网（mywirsh.com）

### 2.1 产品状态类

| # | 位置 | 现状 | 应改为 | 依据 | 优先级 |
| --- | --- | --- | --- | --- | --- |
| W1 | **which-geimori 对比页**（/pages/which-geimori-grinder-is-right-for-you）"High-demand workflow" 区块 + 对比表 GU78 行 | 仍展示 GU78 "Best for cafés…" 并链接 /products/geimori-gu78 | 下架该区块/行，或标注 **"Discontinued"** | product_factcheck（11-16）：GU78 已停售；espressooutlet 目录标 legacy | P1 |
| W2 | **GU78 产品页**（/products/geimori-gu78） | 页面仍可访问并展示 "$1,037.07" 价格（若产品确已停售） | 停售页加 "Discontinued / Out of stock" 状态，不展示可购价格 | product_factcheck（11-16） | P1 |

### 2.2 文案/规格类

| # | 位置 | 现状 | 应改为 | 依据 | 优先级 |
| --- | --- | --- | --- | --- | --- |
| W3 | **GU38 PDP 规格表第 03 项** | "Stepless · marked scale from 0 through **5**" | "0 through **65**"（0–65） | 对比页/三方对比表/其他页面均写 0–65；明显 typo | P1（顺手） |
| W4 | **GU63 PDP 规格表（电机）** | "100W DC motor · 80 RPM"，未写电机类型 | 补一句类型（如有刷/无刷），消除与第三方 "Brushed DC" 描述的猜测差 | lukemakescoffee 写 Brushed DC；GU78 是 BLDC 需防混淆 | P2 |
| W5 | **GU63 产品定位文案** | 广泛表述 "espresso and filter" | filter 部分收敛为 "conical 风味取向（body/甜感）"，light-roast clarity 场景引导 GU64 | lukemakescoffee：filter/light roast 3.5/5 | P2 |

### 2.3 宣传口径类

| # | 位置 | 现状 | 应改为 | 依据 | 优先级 |
| --- | --- | --- | --- | --- | --- |
| W6 | **GU38 产品页 "Zero-Retention" 宣传 + <0.1g 声明** | 无时间/使用条件限定 | 加限定："with bellows, on new burrs"；FAQ 强化定期清理可恢复说明 | thewaytocoffee（8/4）：retention 数月后升高，"accurate out of the box rather than accurate forever" | P1 |
| W7 | **GU38 替换刀盘/维修支持 FAQ** | 无相关说明 | 确认是否提供替换刀盘/维修；有 → 补 FAQ；无 → 如实说明 | brewingcoffeemanually（7/2）："not repairable and Wirsh does not offer replacement burrs" | P1（需先与产品确认事实） |

---

## 三、执行分工建议

- **Amazon 类（A1-A5）**：电商运营在 Seller Central 后台改（标题/五点/描述/附件手册）；建议优先 A1/A3，可同日处理。
- **官网类（W1-W7）**：官网/Shopify 后台改；W1/W2 需先与产品确认 GU78 是否永久停售；W7 需与产品确认刀盘政策后决定文案。
- 改完可在 geimori-coffee-research 仓库审计报告中勾选状态，形成闭环。

---

## 版本记录
- v1.0（2026-11-21）：由 Brand Consensus 审计 v1.1 派生，形成可执行清理清单。
