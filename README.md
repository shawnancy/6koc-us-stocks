# 6 大美股研究 KOC 观点档案

> 6 个 X (Twitter) KOC 关于美股的全部观点，按 ticker 聚合，含「首次提及→现价」收益率追踪。
> 数据源: twitterapi.io + yfinance · 抓取窗口: 2026-02 ~ 2026-05

## 档案目录

- [@qinbafrank — 美股+加密交叉/RWA代币化](qinbafrank.md)
- [@aleabitoreddit — 光通信/半导体设备小盘股深潜](aleabitoreddit.md)
- [@jukan05 — 半导体硬件 (台积/英特尔/美光/AMD)](jukan05.md)
- [@nft_hu — 半导体 + 卫星/航空航天 (RKLB)](nft_hu.md)
- [@LinQingV — 半导体 + 宏观](LinQingV.md)
- [@starzq — 加密相关美股 (TSLA/CRCL/HOOD/COIN)](starzq.md)

---

## 6 人概览

| KOC | 风格 | 抓取量 | 美股相关 | Ticker 数 | TOP3 picks (含收益率) |
|---|---|---|---|---|---|
| [@qinbafrank](qinbafrank.md) | 美股+加密交叉/RWA代币化 | 500 | 294 | 34 | NVDA (🟢 +16.4%) / GOOGL (🟢 +15.9%) / MSFT (🔴 -2.7%) |
| [@aleabitoreddit](aleabitoreddit.md) | 光通信/半导体设备小盘股深潜 | 519 | 448 | 236 | SIVE (无数据) / LITE (🟢 +7.7%) / AAOI (🟢 +64.5%) |
| [@jukan05](jukan05.md) | 半导体硬件 (台积/英特尔/美光/AMD) | 500 | 215 | 32 | TSM (🟢 +12.1%) / INTC (🟢 +72.1%) / MU (🟢 +82.3%) |
| [@nft_hu](nft_hu.md) | 半导体 + 卫星/航空航天 (RKLB) | 500 | 264 | 102 | NVDA (🟢 +5.6%) / MU (🟢 +82.3%) / INTC (🟢 +44.2%) |
| [@LinQingV](LinQingV.md) | 半导体 + 宏观 | 500 | 164 | 31 | TSM (🟢 +12.1%) / INTC (🟢 +72.1%) / AMD (🟢 +74.5%) |
| [@starzq](starzq.md) | 加密相关美股 (TSLA/CRCL/HOOD/COIN) | 500 | 176 | 54 | TSLA (🔴 -3.8%) / CRCL (🔴 -5.6%) / NVDA (🟢 +5.6%) |

**总抓取成本**: $0.453 (twitterapi.io 按推文计费, yfinance 免费)

---

## 字段说明

每个 KOC 的 `.md` 文件包含：

1. **元数据**: 抓取窗口 / 推文总数 / 美股相关占比 / 覆盖 ticker 数
2. **🧠 选币/选股策略 (人工总结区)**: 留白，等人工读完推文后提炼
3. **📊 Ticker 提及频次 + 首提以来收益率**: 按提及次数倒序，含 yfinance 验证
4. **每个 ticker section**: 按时间倒序排所有相关推文，含原推链接 + 互动数
5. **🌐 宏观/板块**: 不含具体 ticker 的美联储/CPI/纳指等宏观观点

## 收益率口径

- **首提日**: 该 KOC 在抓取窗口内最早提及该 ticker 的推文日期
- **当日开盘**: yfinance 拉取的首提日开盘价 (跳过周末/节假日则取下一交易日)
- **最新收盘**: 最近一个交易日收盘价
- **收益率**: `(最新收盘 - 首提日开盘) / 首提日开盘 × 100%`
- **无数据**: OTC 票/海外票/已退市，yfinance 取不到

## 已知局限

- 仅抓 X 公开时间线 **最近 500 条** (不含回复)，更久远观点需扩大 max_tweets
- 推文「美股相关」判定基于关键词 + ticker 正则，可能漏掉隐式讨论
- 收益率只算「首提→现价」，不反映该 KOC 是否在跌的时候继续推荐/止损
- 无法识别讽刺/反向观点，需读全文判断

## 复刻方法

```bash
cd /Users/shaw/.openclaw/workspace/sanliu/koc_us_stocks
python3 fetch_koc.py <handle> 500   # 抓推文
python3 build_md.py <handle>        # 生成 markdown
```

_最后更新: 2026-05-28_