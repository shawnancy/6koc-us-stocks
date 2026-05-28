---
type: research
tags: [美股, KOC研究, X观点, 半导体, 光通信, AI算力]
aliases: [6KOC美股, 美股KOC观点, 6 KOC US stocks]
created: 2026-05-28
updated: 2026-05-28
github: https://github.com/shawnancy/6koc-us-stocks
data_window: 2026-02-22 ~ 2026-05-27
total_tweets: 3019
us_related: 1561
cost_usd: 0.453
---

# 📊 6 大美股研究 KOC 观点档案

> 6 位 X (Twitter) KOC 关于美股的全部观点，按 ticker 聚合 + 首提以来收益率追踪 + LLM 策略画像。
> 🔗 **GitHub 分享**: https://github.com/shawnancy/6koc-us-stocks

---

## 🎯 一句话画像

| KOC | 一句话定性 | 杀手锏 | 最大盲点 |
|---|---|---|---|
| [[qinbafrank\|@qinbafrank]] | AI 算力主线趋势把握王 | $MU +125% / $ARM +80% / $INTC +72%（卡脖子识别） | 加密+股交叉判断弱 ($CRCL/$MSTR) |
| [[aleabitoreddit\|@Serenity]] | CPO 光通信极早期布局神算子 | $AXTI +144% / $AEHR +125%（FUD 时建仓） | 单一 thesis 极度集中，无对冲 |
| [[jukan05\|@Jukan]] | 韩国/台湾产业链信息差套利者 | $INTC +72% / $MU +82% / $AMD +74% | 过度依赖 sell-side spin 信源 |
| [[nft_hu\|@Fiona]] | 太空+光通信跨界主题嗅觉 | $RKLB +75% / $ASTS +62% / $MUU +200% | 102 ticker 太散，深度不足 |
| [[LinQingV\|@Macro_Lin]] | 半导体技术工艺级深度分析 | EMIB-T vs CoWoS 工程级拆解能力 | 短期波段不准，纯研究无操作纪律 |
| [[starzq\|@Star]] | 7 巨头长持 + 段永平跟单 | 长期持有 $MU +266% / $AMD +144% | 短期判断弱，商务推广多 |

---

## 💰 加密货币立场速览

> 每个 KOC 档案里新增「🎯 核心观点」+「💰 喊过的加密货币」两区。关键发现：**这波是美股火、币不火**，BTC 从 1 月高点 -20%。半导体派几乎不碰币，碰币的也是宏观/AI叙事视角，不是炒币。

| KOC | 喊过的币 | 加密定性 |
|---|---|---|
| qinbafrank | BTC(+8%) / ETH(-16%) | 价值储存 + 稳定币基础设施叙事，非炒币 |
| Serenity | 几乎不碰 | 纯光通信美股，加密是边角料 |
| Jukan | **0 加密** | 唯一纯半导体、零加密的 KOC |
| Fiona | ETH(-16%) / BTC(-7%) / HYPE | AI+crypto 叙事边角料 |
| Macro_Lin | ETH 仅 1 次 | 加密不在研究半径 |
| Star | **BTC(-20%)** / ETH(+1.4%) / TAO / SOL | 加密属性最强，BTC 是核心底仓(今年拖后腿) |

---

## 📂 档案目录

- [[qinbafrank|@qinbafrank — 美股+加密交叉/RWA 代币化]]
- [[aleabitoreddit|@Serenity — 光通信/半导体设备小盘股深潜]]
- [[jukan05|@Jukan — 半导体硬件 (台积/英特尔/美光/AMD)]]
- [[nft_hu|@Fiona — 半导体 + 卫星/航空航天]]
- [[LinQingV|@Macro_Lin — 半导体技术深度 + 宏观]]
- [[starzq|@Star — 加密相关美股 + 长持 7 巨头]]

---

## 📈 6 人数据概览

| KOC | 抓取量 | 美股相关 | Ticker 数 | TOP3 picks |
|---|---:|---:|---:|---|
| qinbafrank | 500 | 294 (59%) | 34 | NVDA 🟢+16.4% / GOOGL 🟢+15.9% / MSFT 🔴-2.7% |
| Serenity | 519 | 448 (86%) | 236 | SIVE — / LITE 🟢+7.7% / AAOI 🟢+64.5% |
| Jukan | 500 | 215 (43%) | 32 | TSM 🟢+12.1% / INTC 🟢+72.1% / MU 🟢+82.3% |
| Fiona | 500 | 264 (53%) | 102 | NVDA 🟢+5.6% / MU 🟢+82.3% / INTC 🟢+44.2% |
| Macro_Lin | 500 | 164 (33%) | 31 | TSM 🟢+12.1% / INTC 🟢+72.1% / AMD 🟢+74.5% |
| Star | 500 | 176 (35%) | 54 | TSLA 🔴-3.8% / CRCL 🔴-5.6% / NVDA 🟢+5.6% |

**总计**: 3019 条推文 / 1561 条美股相关 / 抓取成本 **$0.453**

---

## 📝 字段说明

每个 KOC 的档案 (`<handle>.md`) 包含：

1. **元数据** — 抓取窗口 / 推文总数 / 美股相关占比 / 覆盖 ticker 数
2. **🧠 选币/选股策略** — LLM (Opus 1M) 读完推文后写的 6 维度画像草稿（主攻赛道 / 选股逻辑 / 仓位风格 / 信息源 / 写作模式 / 盲点反例）
3. **📊 Ticker 提及频次 + 首提以来收益率** — 按提及次数倒序，含 yfinance 验证
4. **每个 ticker section** — 按时间倒序排所有相关推文，含原推链接 + 互动数 (❤️🔁👁)
5. **🌐 宏观/板块** — 不含具体 ticker 的美联储/CPI/纳指等宏观观点

## 🧮 收益率口径

- **首提日**: 该 KOC 在抓取窗口内最早提及该 ticker 的推文日期
- **当日开盘**: yfinance 拉取的首提日开盘价（跳过周末/节假日则取下一交易日）
- **最新收盘**: 最近一个交易日收盘价
- **收益率**: `(最新收盘 - 首提日开盘) / 首提日开盘 × 100%`
- **无数据**: OTC 票/海外票/已退市，yfinance 取不到

## ⚠️ 已知局限

- 仅抓 X 公开时间线 **最近 500 条**（不含回复），更久远观点需扩大 max_tweets
- 推文「美股相关」判定基于关键词 + ticker 正则，可能漏掉隐式讨论
- 收益率只算「首提→现价」，不反映 KOC 是否在跌的时候继续推荐/止损
- 无法识别讽刺/反向观点，需读全文判断

## 🔧 复刻 / 刷新数据

```bash
cd /Users/shaw/.openclaw/workspace/sanliu/koc_us_stocks
python3 fetch_koc.py <handle> 500   # 抓推文
python3 build_md.py <handle>        # 生成 markdown

# 推到 GitHub (本目录是 git repo, 远端 = shawnancy/6koc-us-stocks)
cd "/Users/shaw/Documents/Obsidian知识库/日常收集📱/资源库/6KOC-美股观点"
git add -u && git commit -m "update: refresh data" && git push
```

---

## 🔗 跨库跳转

- 上层 → [[../README|资源库]]
- 日常收集顶层 → [[../../README|日常收集📱]]
- GitHub 仓库 → [shawnancy/6koc-us-stocks](https://github.com/shawnancy/6koc-us-stocks)

_最后更新: 2026-05-28_
