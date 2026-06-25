# Daily Market Insight Report

**Date:** 2026-06-25

**Data label:** Price and volume data uses yfinance when available. Any ticker that fails uses mock fallback data. Company news uses Finnhub when FINNHUB_API_KEY is set. Macro market snapshot uses yfinance when available. Macro event calendar uses FMP when available, official public release schedules when FMP is unavailable, and local YAML as final fallback. Earnings calendar uses yfinance when available. Basic fundamentals use yfinance when available. Analyst interpretation is rule-based and uses available verified price, news, earnings calendar, and basic fundamental inputs. Theme read-throughs are rule-based and use available watchlist price, volume, news, and basic fundamental inputs. Market Risk Dashboard is rule-based and uses available macro market snapshot, watchlist price, volume, news, earnings calendar, and basic fundamental inputs.

**Use note:** This report is general market commentary for learning and research. It is not personalized financial advice.

## Executive Summary

**Facts from current data inputs:**

- Price and volume fields are sourced from yfinance where available, otherwise from mock fallback data.
- Macro market snapshot uses yfinance when available.
- Macro event calendar uses FMP when available, official public release schedules when FMP is unavailable, and local YAML as final fallback.
- Company-specific news is sourced only from Finnhub verified company news when available.
- Theme read-throughs are rule-based and use available watchlist price, volume, news, and basic fundamental inputs.
- Market Risk Dashboard is rule-based and uses available macro market snapshot, watchlist price, volume, news, earnings calendar, and basic fundamental inputs.
- Earnings calendar and basic fundamentals use yfinance when available; AI infrastructure demand, semiconductor capacity, power supply, memory pricing, and internet platform AI usage remain contextual report inputs.

**Interpretation:**

AI infrastructure remains the center of market attention, but investors are also watching power supply constraints, memory pricing, and Treasury yield (美国国债收益率) moves that can pressure long-duration growth stocks (长久期成长股) and trigger valuation compression (估值压缩).

## Macro Market Snapshot

| Indicator | Ticker | Latest value | Daily change | 5-day change | 20-day change | Source | Note |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 10-year Treasury yield proxy (10年期美国国债收益率代理) | ^TNX | 4.45 | -0.3% | -0.3% | -2.6% | yfinance | ^TNX fetched from yfinance and shown as a percentage-style yield proxy. Change values are percentage changes in the proxy level, not basis-point changes. |
| VIX volatility index (VIX波动率指数) | ^VIX | 18.63 | -4.4% | +13.5% | +9.5% | yfinance | VIX fetched from yfinance. |
| Nasdaq Composite | ^IXIC | 25,476.64 | -0.4% | -3.4% | -4.4% | yfinance | Nasdaq Composite fetched from yfinance. |
| S&P 500 | ^GSPC | 7,358.22 | -0.1% | -2.0% | -2.1% | yfinance | S&P 500 fetched from yfinance. |
| US Dollar Index (美元指数) proxy | DX-Y.NYB | 101.56 | -0.1% | +1.5% | +2.4% | yfinance | US Dollar Index (美元指数) proxy fetched from yfinance. |

Rule-based macro read-through: Treasury yield (美国国债收益率) is lower over 20 trading days based on the yfinance proxy; the VIX volatility index (VIX波动率指数) is at 18.63, and volatility pressure (波动性压力) has increased over 20 trading days; Nasdaq and S&P 500 price action points to weaker equity risk appetite (股票风险偏好) over the 20-day window; the US dollar index (美元指数) proxy is higher over 20 trading days.

## Macro Event Calendar

| Date | Time | Country | Event | Category | Importance | Source | Note |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-25 | 8:30 AM | US | GDP | Growth | High | BEA | Official release schedule. No outcome is inferred. |
| 2026-06-25 | 8:30 AM | US | Personal Income and Outlays | Inflation | High | BEA | Official release schedule. No outcome is inferred. |

Source used: official public schedules.

FMP economic calendar was unavailable, so this section uses official public release schedules from the Federal Reserve, BLS, and BEA. It does not infer event outcomes, Fed decisions, inflation direction, or market impact.

This calendar only lists upcoming macro events parsed from official public release schedules. It does not infer event outcomes, Fed decisions, inflation direction, or market impact before the data is released.

## Key Theme Read-Throughs

### AI

- **Headline:** AI: negative sector momentum (板块动量) across 6 stocks
- **Verified input summary:** yfinance price and volume inputs are available for 6 of 6 stocks. Average 5-day change is -4.7%, average 20-day change is -8.0%, 2 stocks show high volatility (波动性), and 18 verified company headlines were available from Finnhub. Basic fundamental snapshot (基本面快照) coverage is 6 of 6 stocks.
- **Interpretation:** Sector momentum (板块动量) is negative, while average relative volume (相对成交量) is 1.04x. Valuation risk (估值风险) remains worth monitoring where P/E or price-to-sales metrics are elevated. Average yfinance revenue growth (收入增长) is 35.5%, and average operating margin in the fundamental snapshot (基本面快照) is 36.0%.

### Semiconductors

- **Headline:** Semiconductors: mixed sector momentum (板块动量) across 4 stocks
- **Verified input summary:** yfinance price and volume inputs are available for 4 of 4 stocks. Average 5-day change is -0.1%, average 20-day change is +2.7%, 2 stocks show high volatility (波动性), and 12 verified company headlines were available from Finnhub. Basic fundamental snapshot (基本面快照) coverage is 4 of 4 stocks.
- **Interpretation:** Sector momentum (板块动量) is mixed, while average relative volume (相对成交量) is 0.86x. Valuation risk (估值风险) remains worth monitoring where P/E or price-to-sales metrics are elevated. Average yfinance revenue growth (收入增长) is 42.8%, and average operating margin in the fundamental snapshot (基本面快照) is 43.5%.

### Internet Platforms

- **Headline:** Internet Platforms: negative sector momentum (板块动量) across 4 stocks
- **Verified input summary:** yfinance price and volume inputs are available for 4 of 4 stocks. Average 5-day change is -6.6%, average 20-day change is -11.0%, 0 stocks show high volatility (波动性), and 12 verified company headlines were available from Finnhub. Basic fundamental snapshot (基本面快照) coverage is 4 of 4 stocks.
- **Interpretation:** Sector momentum (板块动量) is negative, while average relative volume (相对成交量) is 1.12x. Average yfinance revenue growth (收入增长) is 22.4%, and average operating margin in the fundamental snapshot (基本面快照) is 34.1%.

### Power Supply

- **Headline:** Power Supply: mixed sector momentum (板块动量) across 2 stocks
- **Verified input summary:** yfinance price and volume inputs are available for 2 of 2 stocks. Average 5-day change is +1.3%, average 20-day change is -6.1%, 1 stock shows high volatility (波动性), and 6 verified company headlines were available from Finnhub. Basic fundamental snapshot (基本面快照) coverage is 2 of 2 stocks.
- **Interpretation:** Sector momentum (板块动量) is mixed, while average relative volume (相对成交量) is 0.73x. Average yfinance revenue growth (收入增长) is 53.6%, and average operating margin in the fundamental snapshot (基本面快照) is 24.2%.

### Memory

- **Headline:** Memory: positive sector momentum (板块动量) across 1 stock
- **Verified input summary:** yfinance price and volume inputs are available for 1 of 1 stock. Average 5-day change is +2.7%, average 20-day change is +17.0%, 1 stock shows high volatility (波动性), and 3 verified company headlines were available from Finnhub. Basic fundamental snapshot (基本面快照) coverage is 1 of 1 stock.
- **Interpretation:** Sector momentum (板块动量) is positive, while average relative volume (相对成交量) is 1.20x. Average yfinance revenue growth (收入增长) is 196.3%, and average operating margin in the fundamental snapshot (基本面快照) is 67.6%.

## Analyst View

### AI

- Why this news matters: AI demand is moving from early training clusters toward broader inference usage, which can increase the size of the addressable market.
- Noise or structural trend: Long-term structural trend, with short-term valuation swings.
- Companies that may benefit: NVIDIA, Microsoft, Alphabet, Meta, Broadcom
- Companies that may face pressure: Companies with weak AI products, Cloud customers facing rising AI capex (人工智能资本开支)

### Semiconductors

- Why this news matters: Advanced chips and packaging capacity remain central to the AI supply chain (供应链), so bottlenecks can affect shipment timing and pricing.
- Noise or structural trend: Long-term structural trend, but order timing can create short-term noise.
- Companies that may benefit: TSMC, ASML, NVIDIA, AMD, Broadcom
- Companies that may face pressure: Lagging foundries, Chip customers exposed to supply shortages

### Internet Platforms

- Why this news matters: Large platforms are using AI to defend advertising returns, improve cloud services, and raise user engagement.
- Noise or structural trend: Long-term trend, with quarterly earnings acting as near-term tests.
- Companies that may benefit: Meta, Alphabet, Amazon, Microsoft
- Companies that may face pressure: Smaller ad platforms, Platforms with high spending and weak monetization (商业化变现)

### Power Supply

- Why this news matters: Data centers need reliable electricity, grid connections, and backup systems. Power availability can become a limiting factor for AI infrastructure growth.
- Noise or structural trend: Long-term structural trend, with project approvals creating short-term moves.
- Companies that may benefit: GE Vernova, Constellation Energy, Vistra, Eaton
- Companies that may face pressure: Data center operators in power-constrained regions, Utilities facing delays

### Memory

- Why this news matters: High bandwidth memory (高带宽内存) is a key input for AI accelerators, and stronger pricing can support the memory cycle.
- Noise or structural trend: Cyclical recovery supported by a structural AI demand driver.
- Companies that may benefit: Micron, SK Hynix, Samsung Electronics
- Companies that may face pressure: Customers exposed to rising memory costs, Suppliers with weak HBM (高带宽内存) positioning

### Macro

- Why this news matters: Interest rates and inflation affect discount rates (贴现率), equity multiples (股票估值倍数), and investor risk appetite (风险偏好) across growth sectors.
- Noise or structural trend: Short-term data sensitivity inside a longer monetary policy (货币政策) cycle.
- Companies that may benefit: Cash-rich companies, Defensive sectors during risk-off (避险) periods
- Companies that may face pressure: High-multiple growth stocks, Highly leveraged companies

## Key Focus This Week

- **AI:** AI remains the main earnings and capex (资本开支) debate. Investors will look for evidence that spending is translating into durable revenue.
- **Power Supply:** Power availability is becoming a practical constraint for data center expansion, which can change which suppliers capture value.
- **Macro:** Inflation and Treasury yield (美国国债收益率) moves can quickly change the market's tolerance for high valuation technology stocks.

## Upcoming Catalysts

| Event | Timing | Why it matters |
| --- | --- | --- |
| Federal Reserve (美联储) meeting | Upcoming policy window | Policy guidance can affect Treasury yield (美国国债收益率) direction and growth stock valuations. |
| CPI (消费者价格指数) inflation (消费者价格指数通胀) report | Upcoming inflation print | A hotter or cooler inflation reading can change rate expectations. |
| PCE (个人消费支出) inflation (个人消费支出通胀) data | Upcoming macro release | The Fed (美联储) watches PCE (个人消费支出) closely when judging inflation progress. |
| Nonfarm payrolls (非农就业数据) | Upcoming labor market report | Labor strength or weakness can shift the soft landing (软着陆) debate. |
| Major tech earnings | Upcoming earnings season (财报季) | Investors will test whether AI spending is improving revenue and margins (利润率). |
| Semiconductor earnings | Upcoming earnings season (财报季) | Guidance can confirm or challenge the AI chip and memory cycle story. |
| AI/data center capex (资本开支) announcements | Company update cycle | Large spending plans can help suppliers but may pressure free cash flow (自由现金流). |
| China policy news | Ongoing policy watch | Policy support or trade restrictions can affect semiconductors and internet platforms. |

## Stock Watchlist with Investment View

The labels below are rule-based research-style views for learning and research. They are not personalized financial advice or trading instructions.

| Ticker | Company | Theme | Data source | Latest price | Daily change | 5-day change | 20-day change | Trading volume | Average 20-day volume | Relative volume | Volatility | Rule-based view label |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NVDA | NVIDIA | AI / Semiconductors | yfinance | $199.00 | -0.5% | -4.1% | -7.4% | 150.8M | 169.0M | 0.89x | High | Watch |
| AMD | Advanced Micro Devices | AI / Semiconductors | yfinance | $519.74 | -0.0% | +2.5% | +3.1% | 26.5M | 31.1M | 0.85x | High | High risk speculative |
| TSM | Taiwan Semiconductor Manufacturing | Semiconductors | yfinance | $440.83 | +1.0% | +3.5% | +6.9% | 9.9M | 13.8M | 0.72x | Medium | Accumulate on weakness |
| ASML | ASML Holding | Semiconductors | yfinance | $1,762.77 | -0.9% | -2.3% | +8.0% | 2.0M | 2.1M | 0.98x | Medium | Watch |
| MSFT | Microsoft | AI / Internet Platforms | yfinance | $365.46 | -2.3% | -7.2% | -12.2% | 44.3M | 41.2M | 1.07x | Medium | Watch |
| GOOGL | Alphabet | Internet Platforms / AI | yfinance | $345.29 | -0.2% | -7.5% | -11.2% | 44.8M | 35.6M | 1.26x | Medium | Watch |
| AMZN | Amazon | Internet Platforms / AI | yfinance | $234.27 | +0.1% | -4.8% | -11.7% | 70.1M | 49.0M | 1.43x | Medium | Watch |
| META | Meta Platforms | Internet Platforms / AI | yfinance | $557.67 | -0.8% | -7.1% | -8.9% | 13.9M | 19.4M | 0.72x | Medium | Watch |
| MU | Micron Technology | Memory | yfinance | $1,048.51 | -0.3% | +2.7% | +17.0% | 66.7M | 55.7M | 1.20x | High | High risk speculative |
| CEG | Constellation Energy | Power Supply | yfinance | $267.97 | -0.8% | -0.0% | -11.1% | 2.7M | 4.3M | 0.62x | Medium | Accumulate on weakness |
| VST | Vistra | Power Supply | yfinance | $162.87 | +0.3% | +2.7% | -1.0% | 3.7M | 4.4M | 0.84x | High | Avoid for now |

## Single Stock Analysis

Price and volume fields use yfinance when available. Tickers marked mock fallback use sample values. Company news uses Finnhub when available. Earnings calendar and basic fundamentals use yfinance when available. Analyst interpretation is rule-based and uses available verified inputs.

### NVDA - NVIDIA

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $199.00; daily change -0.5%; 5-day change -4.1%; 20-day change -7.4%; trading volume (成交量) 150.8M; average 20-day volume (20日平均成交量) 169.0M; relative volume (相对成交量) 0.89x; volatility (波动性) level High.
- **Latest verified company news:**
  - 2026-06-25 | Yahoo | Better Buy After the Chip Sell-Off: Nvidia or AMD? | https://finnhub.io/api/news?id=4f378031e4360e143d3584be5c7af1c5d563453551847f2cb5b52cfaa1799a29
  - 2026-06-25 | Yahoo | Nasdaq, S&P 500, Dow Futures Rise As Micron, Qualcomm Calm AI Jitters: Why WEN, SPCX, NVDA Stocks Are Also In Focus | https://finnhub.io/api/news?id=f699482746515c968954379e8ae7f848dd44a33d922a7787e68e779585a34238
  - 2026-06-25 | Yahoo | Could a $25,000 Investment in Nvidia Stock Make You a Millionaire? | https://finnhub.io/api/news?id=92dd30f2247eeaa4d1f87245e43539afd6e5dbfc1c7cb7b82378160e05f800e3
- **News-based analyst note:** Verified headlines point to AI positioning. Price action shows negative short-term momentum (短期动量) with high volatility (波动性) and 0.89x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-08-27. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $4819.98B
  - Trailing P/E (过去市盈率): 30.47
  - Forward P/E (预期市盈率): 15.63
  - Price-to-sales (市销率): 19.01
  - Revenue growth (收入增长): 85.2%
  - Gross margin (毛利率): 74.1%
  - Operating margin (经营利润率): 65.6%
  - Profit margin (净利润率): 63.0%
  - Free cash flow (自由现金流): $46.34B
  - Total cash (现金及等价物): $53.17B
  - Total debt (总债务): $12.81B
- **Risk and volatility (波动性):** Volatility level is High. Macro sensitivity: Medium sensitivity to Treasury yield (美国国债收益率) moves because the market prices in high future growth.
- **Analyst interpretation:** Price action shows negative momentum (动量), high volatility (波动性), and 0.89x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 30.5x, forward P/E 15.6x, and price-to-sales 19.0x; yfinance revenue growth (收入增长) is 85.2%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows cash above debt; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-08-27.
- **Investment view:** Watch
- **What to watch next:** More balanced valuation or clearer evidence of durable inference demand.

### AMD - Advanced Micro Devices

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $519.74; daily change -0.0%; 5-day change +2.5%; 20-day change +3.1%; trading volume (成交量) 26.5M; average 20-day volume (20日平均成交量) 31.1M; relative volume (相对成交量) 0.85x; volatility (波动性) level High.
- **Latest verified company news:**
  - 2026-06-25 | Yahoo | AMD vs. Marvell Technology: Which Will Be the Next Trillion-Dollar Stock? | https://finnhub.io/api/news?id=fe8700987460b4ca28168d8d9c4537a977e0a221a3a12517f319e5e6584c4d12
  - 2026-06-25 | Yahoo | Better Buy After the Chip Sell-Off: Nvidia or AMD? | https://finnhub.io/api/news?id=4f378031e4360e143d3584be5c7af1c5d563453551847f2cb5b52cfaa1799a29
  - 2026-06-25 | Yahoo | WDC, STX, SNDK, INTC, AMD: Chip Stocks Rally After Micron's Stellar Q3 Earnings | https://finnhub.io/api/news?id=57993665d5c199d0b950a7e4027b370efffe73e454389f0b5204d99f03d31644
- **News-based analyst note:** Verified headlines point to company-specific headline risk (标题风险). With mixed price momentum (动量), high volatility (波动性), and 0.85x relative volume (相对成交量), the read-through is useful for sentiment (市场情绪) monitoring but not enough to change the research label.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-08-05. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $847.49B
  - Trailing P/E (过去市盈率): 172.67
  - Forward P/E (预期市盈率): 39.47
  - Price-to-sales (市销率): 22.63
  - Revenue growth (收入增长): 37.8%
  - Gross margin (毛利率): 53.1%
  - Operating margin (经营利润率): 14.4%
  - Profit margin (净利润率): 13.4%
  - Free cash flow (自由现金流): $7.17B
  - Total cash (现金及等价物): $12.35B
  - Total debt (总债务): $3.87B
- **Risk and volatility (波动性):** Volatility level is High. Macro sensitivity: Medium sensitivity to risk appetite (风险偏好) and semiconductor cycle expectations.
- **Analyst interpretation:** Price action shows mixed momentum (动量), high volatility (波动性), and 0.85x relative volume (相对成交量); valuation risk (估值风险) remains important given trailing P/E 172.7x, forward P/E 39.5x, and price-to-sales 22.6x; yfinance revenue growth (收入增长) is 37.8%; the margin profile (利润率结构) is thin. The balance sheet (资产负债表) shows cash above debt; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-08-05.
- **Investment view:** High risk speculative
- **What to watch next:** Clearer evidence of sustained AI GPU share gains and margin improvement.

### TSM - Taiwan Semiconductor Manufacturing

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $440.83; daily change +1.0%; 5-day change +3.5%; 20-day change +6.9%; trading volume (成交量) 9.9M; average 20-day volume (20日平均成交量) 13.8M; relative volume (相对成交量) 0.72x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-24 | Benzinga | B of A Securities Maintains Buy on Taiwan Semiconductor, Raises Price Target to $590 | https://finnhub.io/api/news?id=32c6ad1cd74ccc666b59a0c22c533f6453e893a96aed6e445129bff503f3616d
  - 2026-06-24 | SeekingAlpha | Taiwan Semiconductor: The AI Toll Road Keeps Widening | https://finnhub.io/api/news?id=de72a39f37aac00106a92acfe74f2f6f1d0eb76ba777e726ad186934edc49707
  - 2026-06-23 | Benzinga | Taiwan Semiconductor VP Trades $79K In Company Stock | https://finnhub.io/api/news?id=67ee663624760d07a6eed5564333cc9d043cd158481f5f186156a2e755052d45
- **News-based analyst note:** Verified headlines point to AI positioning. Price action shows positive short-term momentum (短期动量) with medium volatility (波动性) and 0.72x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-07-16. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $2286.35B
  - Trailing P/E (过去市盈率): 38.04
  - Forward P/E (预期市盈率): 22.08
  - Price-to-sales (市销率): 0.56
  - Revenue growth (收入增长): 35.1%
  - Gross margin (毛利率): 61.9%
  - Operating margin (经营利润率): 58.1%
  - Profit margin (净利润率): 46.5%
  - Free cash flow (自由现金流): $719.16B
  - Total cash (现金及等价物): $3383.60B
  - Total debt (总债务): $1094.37B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to global growth and geopolitical risk (地缘政治风险).
- **Analyst interpretation:** Price action shows positive momentum (动量), medium volatility (波动性), and 0.72x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 38.0x, forward P/E 22.1x, and price-to-sales 0.6x; yfinance revenue growth (收入增长) is 35.1%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows cash above debt; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-07-16.
- **Investment view:** Accumulate on weakness
- **What to watch next:** A major geopolitical shock or signs of weaker leading-edge demand.

### ASML - ASML Holding

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $1,762.77; daily change -0.9%; 5-day change -2.3%; 20-day change +8.0%; trading volume (成交量) 2.0M; average 20-day volume (20日平均成交量) 2.1M; relative volume (相对成交量) 0.98x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-24 | Yahoo | ASML Holding (ASML): The Best All-Time High Stock with Legs to Rally Further | https://finnhub.io/api/news?id=3218f9f092d3dce2c511b64566bad6b078bbf5f6cf28950c7d94baa70dfbaa5b
  - 2026-06-24 | Yahoo | ASML Holding N.V. (ASML) Is One Of Billionaire David Tepper’s Longest Held AI Stocks | https://finnhub.io/api/news?id=5538ab1983fbf3286cfc1ab51720dae3a364451ec9e2dca77aa176f85fdf3ccd
  - 2026-06-24 | Yahoo | ASML Faces New China Risk as 19% Sales Market Comes Under Pressure | https://finnhub.io/api/news?id=091a9318e40fe39bf7dd7b871d065c297f2e108cdfafe42a68ef381eae66edde
- **News-based analyst note:** Verified headlines point to China chip restriction headline risk (标题风险), AI positioning. Price action shows mixed price momentum (动量) with medium volatility (波动性) and 0.98x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-07-15. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $679.40B
  - Trailing P/E (过去市盈率): 59.53
  - Forward P/E (预期市盈率): 36.97
  - Price-to-sales (市销率): 20.16
  - Revenue growth (收入增长): 13.2%
  - Gross margin (毛利率): 52.6%
  - Operating margin (经营利润率): 36.0%
  - Profit margin (净利润率): 29.7%
  - Free cash flow (自由现金流): $8.24B
  - Total cash (现金及等价物): $8.38B
  - Total debt (总债务): $2.71B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to semiconductor capital spending (资本支出) cycles.
- **Analyst interpretation:** Price action shows mixed momentum (动量), medium volatility (波动性), and 0.98x relative volume (相对成交量); valuation risk (估值风险) remains important given trailing P/E 59.5x, forward P/E 37.0x, and price-to-sales 20.2x; yfinance revenue growth (收入增长) is 13.2%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows cash above debt; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-07-15.
- **Investment view:** Watch
- **What to watch next:** Stronger bookings visibility or reduced export-control uncertainty.

### MSFT - Microsoft

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $365.46; daily change -2.3%; 5-day change -7.2%; 20-day change -12.2%; trading volume (成交量) 44.3M; average 20-day volume (20日平均成交量) 41.2M; relative volume (相对成交量) 1.07x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-25 | Yahoo | FPT Expands Strategic Collaboration with Microsoft to Advance AI Frontier Innovation Across Asia | https://finnhub.io/api/news?id=00bd9736bb511579eb062ae1fde4c9c00999647e0bfa07bbfbf0836acf9bf67b
  - 2026-06-24 | Yahoo | Microsoft Corporation (MSFT) Is One Of Billionaire David Tepper’s Oldest AI Stocks | https://finnhub.io/api/news?id=59d2b662a87c5e9b9ef9466660ae9a846284a7fe857c6b4d5639cc6c8e06d51d
  - 2026-06-24 | Yahoo | Retail Investors Sold NVIDIA, Microsoft, and Oracle to Fund SpaceX Buys. What’s the Next ‘Mega-Cap Tech Stock?’ | https://finnhub.io/api/news?id=c29e36a266d2960ceee9ea280bf2d2cd76b33b3855d9eab07f91c67325130d78
- **News-based analyst note:** Verified headlines point to broader market positioning, AI positioning. Price action shows negative short-term momentum (短期动量) with medium volatility (波动性) and 1.07x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-07-30. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $2714.80B
  - Trailing P/E (过去市盈率): 21.79
  - Forward P/E (预期市盈率): 18.89
  - Price-to-sales (市销率): 8.53
  - Revenue growth (收入增长): 18.3%
  - Gross margin (毛利率): 68.3%
  - Operating margin (经营利润率): 46.3%
  - Profit margin (净利润率): 39.3%
  - Free cash flow (自由现金流): $37.01B
  - Total cash (现金及等价物): $78.23B
  - Total debt (总债务): $125.43B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to discount rates (贴现率) and enterprise spending.
- **Analyst interpretation:** Price action shows negative momentum (动量), medium volatility (波动性), and 1.07x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 21.8x, forward P/E 18.9x, and price-to-sales 8.5x; yfinance revenue growth (收入增长) is 18.3%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows debt above cash; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-07-30.
- **Investment view:** Watch
- **What to watch next:** Better visibility on AI monetization (商业化变现) versus infrastructure spending.

### GOOGL - Alphabet

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $345.29; daily change -0.2%; 5-day change -7.5%; 20-day change -11.2%; trading volume (成交量) 44.8M; average 20-day volume (20日平均成交量) 35.6M; relative volume (相对成交量) 1.26x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-25 | Yahoo | I Correctly Predicted Alphabet Would Join the Dow Jones Industrial Average in June. Here's What the Index Shake-Up Means for Investors. | https://finnhub.io/api/news?id=21986ae9af25a11eee7673aec99b583a70f5c5efa78dc819a2cbda193cf33191
  - 2026-06-24 | Yahoo | S&P 500, Nasdaq Close Lower On Tech Weakness But Recover After-Hours On Strong Micron Earnings — MU, AVGO, GOOGL In Focus | https://finnhub.io/api/news?id=7fae973942e40553c863d0377f9820d34aa88257f0b102b0fb76172cd9aeb69e
  - 2026-06-24 | Yahoo | Should Berkshire’s US$10 Billion Alphabet Bet and Tech Tilt Require Action From Berkshire Hathaway (BRK.A) Investors? | https://finnhub.io/api/news?id=c5de9135c1f6c3a06ffb65fed8e2155a4871017d34d65fb9e0b1e2ea58ebad70
- **News-based analyst note:** Verified headlines point to company-specific headline risk (标题风险). Price action shows negative short-term momentum (短期动量) with medium volatility (波动性) and 1.26x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-07-24. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $4213.43B
  - Trailing P/E (过去市盈率): 26.32
  - Forward P/E (预期市盈率): 23.73
  - Price-to-sales (市销率): 9.97
  - Revenue growth (收入增长): 21.8%
  - Gross margin (毛利率): 60.4%
  - Operating margin (经营利润率): 36.1%
  - Profit margin (净利润率): 37.9%
  - Free cash flow (自由现金流): $27.92B
  - Total cash (现金及等价物): $126.84B
  - Total debt (总债务): $95.88B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to advertising demand and regulatory pressure (监管压力).
- **Analyst interpretation:** Price action shows negative momentum (动量), medium volatility (波动性), and 1.26x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 26.3x, forward P/E 23.7x, and price-to-sales 10.0x; yfinance revenue growth (收入增长) is 21.8%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows cash above debt; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-07-24.
- **Investment view:** Watch
- **What to watch next:** Clearer proof that AI search supports monetization (商业化变现) without margin damage.

### AMZN - Amazon

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $234.27; daily change +0.1%; 5-day change -4.8%; 20-day change -11.7%; trading volume (成交量) 70.1M; average 20-day volume (20日平均成交量) 49.0M; relative volume (相对成交量) 1.43x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-25 | Yahoo | Corning (GLW) Lands Amazon Fiber Deal As AI Data Center Demand Builds | https://finnhub.io/api/news?id=b45fb81977542c9eb55fea5f737ff31c6ab9a212825c0681d247320f93ca1ef7
  - 2026-06-25 | Yahoo | Amazon Prime Day launched with tricks few shoppers catch | https://finnhub.io/api/news?id=b9fce0c8adefae88cb5a899c7218e0d7326cd7873eaa6c55ff76adc58e9d1ea4
  - 2026-06-24 | Yahoo | Petco pulls back on what Amazon and Chewy can't match | https://finnhub.io/api/news?id=41fbdea029bebff3afcb5aa2a400592e3fc7bfd9d2a84381746462e0276f8e58
- **News-based analyst note:** Verified headlines point to Prime Day, AI positioning. Price action shows mixed price momentum (动量) with medium volatility (波动性) and 1.43x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-07-31. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $2520.07B
  - Trailing P/E (过去市盈率): 31.66
  - Forward P/E (预期市盈率): 23.71
  - Price-to-sales (市销率): 3.39
  - Revenue growth (收入增长): 16.6%
  - Gross margin (毛利率): 50.6%
  - Operating margin (经营利润率): 13.1%
  - Profit margin (净利润率): 12.2%
  - Free cash flow (自由现金流): $9.81B
  - Total cash (现金及等价物): $143.09B
  - Total debt (总债务): $235.54B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to consumer demand and cloud spending.
- **Analyst interpretation:** Price action shows mixed momentum (动量), medium volatility (波动性), and 1.43x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 31.7x, forward P/E 23.7x, and price-to-sales 3.4x; yfinance revenue growth (收入增长) is 16.6%; the margin profile (利润率结构) is thin. The balance sheet (资产负债表) shows debt above cash; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-07-31.
- **Investment view:** Watch
- **What to watch next:** Sustained AWS acceleration with continued retail margin discipline.

### META - Meta Platforms

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $557.67; daily change -0.8%; 5-day change -7.1%; 20-day change -8.9%; trading volume (成交量) 13.9M; average 20-day volume (20日平均成交量) 19.4M; relative volume (相对成交量) 0.72x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-24 | Yahoo | QCOM Stock Jumps 15% After-Hours — Massive AI Revenue Targets And Meta Deal Power Qualcomm Rally | https://finnhub.io/api/news?id=76d5ff913c7003219fe03cc7f83d6cb8f4665f8d20f5eedf8f239940b2f1d6c1
  - 2026-06-24 | Yahoo | Qualcomm unveils Dragonfly CPU, signs Meta as first data center customer | https://finnhub.io/api/news?id=75ca1a7049bcab9a4e24f268adbb4993a23ab1246ba4536361f660e94f2d5d8f
  - 2026-06-24 | Yahoo | Qualcomm and Meta Announce Strategic Multi-Generation Agreement on Data Center CPUs | https://finnhub.io/api/news?id=b48aa76e6816fc6afad0a273aeea5da7c0aae0168082e9fc076c8365dab63ea2
- **News-based analyst note:** Verified headlines point to AI positioning. Price action shows negative short-term momentum (短期动量) with medium volatility (波动性) and 0.72x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-07-30. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $1415.60B
  - Trailing P/E (过去市盈率): 20.29
  - Forward P/E (预期市盈率): 15.39
  - Price-to-sales (市销率): 6.59
  - Revenue growth (收入增长): 33.1%
  - Gross margin (毛利率): 81.9%
  - Operating margin (经营利润率): 40.6%
  - Profit margin (净利润率): 32.8%
  - Free cash flow (自由现金流): $25.56B
  - Total cash (现金及等价物): $81.18B
  - Total debt (总债务): $86.77B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to ad demand and risk appetite (风险偏好).
- **Analyst interpretation:** Price action shows negative momentum (动量), medium volatility (波动性), and 0.72x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 20.3x, forward P/E 15.4x, and price-to-sales 6.6x; yfinance revenue growth (收入增长) is 33.1%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows debt above cash; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-07-30.
- **Investment view:** Watch
- **What to watch next:** A sharper link between AI capex (人工智能资本开支) and advertising revenue growth (收入增长).

### MU - Micron Technology

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $1,048.51; daily change -0.3%; 5-day change +2.7%; 20-day change +17.0%; trading volume (成交量) 66.7M; average 20-day volume (20日平均成交量) 55.7M; relative volume (相对成交量) 1.20x; volatility (波动性) level High.
- **Latest verified company news:**
  - 2026-06-25 | Yahoo | 4 Blowout Numbers From Micron's Earnings Investors Need To See | https://finnhub.io/api/news?id=b53f0bc6b3bb047de933aa0d5719f6ed6228424875174eeedd4075fa7f467c06
  - 2026-06-25 | Yahoo | Micron Technology Inc (MU) Q3 2026 Earnings Call Highlights: Record Revenue and Strategic ... | https://finnhub.io/api/news?id=3e74716b8418fffb37602106446dcf1f5eabea359f59ec9782a4cc7fb93136ea
  - 2026-06-25 | Yahoo | MRVL Stock Jumps Overnight: MU, QCOM Boost Outweigh CFO’s Share Sale | https://finnhub.io/api/news?id=58db831a62b21c5964ed582af7f4242348c135e1d07018ae6f364066db5f048c
- **News-based analyst note:** Verified headlines point to company-specific headline risk (标题风险). Price action shows mixed price momentum (动量) with high volatility (波动性) and 1.20x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-06-25. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $1182.44B
  - Trailing P/E (过去市盈率): 23.70
  - Forward P/E (预期市盈率): 8.11
  - Price-to-sales (市销率): 20.35
  - Revenue growth (收入增长): 196.3%
  - Gross margin (毛利率): 58.4%
  - Operating margin (经营利润率): 67.6%
  - Profit margin (净利润率): 41.5%
  - Free cash flow (自由现金流): $2.89B
  - Total cash (现金及等价物): $14.59B
  - Total debt (总债务): $10.80B
- **Risk and volatility (波动性):** Volatility level is High. Macro sensitivity: High sensitivity to semiconductor cycle and end-market demand.
- **Analyst interpretation:** Price action shows mixed momentum (动量), high volatility (波动性), and 1.20x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 23.7x, forward P/E 8.1x, and price-to-sales 20.3x; yfinance revenue growth (收入增长) is 196.3%; the margin profile (利润率结构) is strong. The balance sheet (资产负债表) shows cash above debt; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-06-25.
- **Investment view:** High risk speculative
- **What to watch next:** More evidence that HBM (高带宽内存) demand can offset broader memory cycle volatility (波动性).

### CEG - Constellation Energy

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $267.97; daily change -0.8%; 5-day change -0.0%; 20-day change -11.1%; trading volume (成交量) 2.7M; average 20-day volume (20日平均成交量) 4.3M; relative volume (相对成交量) 0.62x; volatility (波动性) level Medium.
- **Latest verified company news:**
  - 2026-06-24 | Yahoo | Constellation Energy (CEG) Seen as High-Quality Power Demand Play, but Goldman Flags Valuation | https://finnhub.io/api/news?id=03c711da013b1936e76b0a8cbdce8ded565e7f357392644ea6d464d2f65ea19b
  - 2026-06-23 | Yahoo | Constellation Energy Inks a Nuclear Power Deal with Walmart. Here's What Investors Need to Know. | https://finnhub.io/api/news?id=38d24cc683c72558c43fa329450863445c5f253b72ac1b29af473e241e23db9f
  - 2026-06-23 | Yahoo | Constellation Energy (CEG) Stock After 26% Year-To-Date Slide Is There Still Upside | https://finnhub.io/api/news?id=d058257eebc8a874c89d90b271bd76679932d403fdc37cb09c5d6b16807acab7
- **News-based analyst note:** Verified headlines point to valuation debate. Price action shows negative short-term momentum (短期动量) with medium volatility (波动性) and 0.62x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-08-06. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $95.69B
  - Trailing P/E (过去市盈率): 23.26
  - Forward P/E (预期市盈率): 19.81
  - Price-to-sales (市销率): 3.20
  - Revenue growth (收入增长): 63.8%
  - Gross margin (毛利率): 23.3%
  - Operating margin (经营利润率): 21.9%
  - Profit margin (净利润率): 12.7%
  - Free cash flow (自由现金流): -$4.48B
  - Total cash (现金及等价物): $864.00M
  - Total debt (总债务): $22.47B
- **Risk and volatility (波动性):** Volatility level is Medium. Macro sensitivity: Medium sensitivity to power prices, rates, and policy decisions.
- **Analyst interpretation:** Price action shows negative momentum (动量), medium volatility (波动性), and 0.62x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 23.3x, forward P/E 19.8x, and price-to-sales 3.2x; yfinance revenue growth (收入增长) is 63.8%; the margin profile (利润率结构) is thin. The balance sheet (资产负债表) shows debt above cash; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-08-06.
- **Investment view:** Accumulate on weakness
- **What to watch next:** More long-term power agreements with data center customers.

### VST - Vistra

- **Price and volume signal:** Data source: yfinance (Price and volume data fetched from yfinance.); Latest price $162.87; daily change +0.3%; 5-day change +2.7%; 20-day change -1.0%; trading volume (成交量) 3.7M; average 20-day volume (20日平均成交量) 4.4M; relative volume (相对成交量) 0.84x; volatility (波动性) level High.
- **Latest verified company news:**
  - 2026-06-24 | SeekingAlpha | Vistra: A Solid Utility Story With Limited Margin For Error | https://finnhub.io/api/news?id=aabf76d14f312a32361ace67020b47d0d53b7811dde331a13283b8dc5a8461f5
  - 2026-06-24 | Yahoo | Vistra Corp. (VST) Is a Trending Stock: Facts to Know Before Betting on It | https://finnhub.io/api/news?id=11ac6b7e5a6780baf77cebc826eefa4e86a0322ce77605421a5c8f36f54dfc92
  - 2026-06-23 | Benzinga | Vistra, Generac, Rockwell Automation And A Basic Material Stock: CNBC’s ‘Final Trades’ | https://finnhub.io/api/news?id=1023e372bb9780ad518b4eec7a53d84322f9d15373ca3ce739e867503b239c61
- **News-based analyst note:** Verified headlines point to company-specific headline risk (标题风险). Price action shows mixed price momentum (动量) with high volatility (波动性) and 0.84x relative volume (相对成交量), so the setup remains headline-driven and sentiment (市场情绪)-sensitive.
- **Earnings calendar:**
  - Next verified earnings date (财报日期): 2026-08-06. Data source: yfinance.
- **Fundamental snapshot:**
  - Data source: yfinance.
  - Market cap (市值): $54.92B
  - Trailing P/E (过去市盈率): 27.24
  - Forward P/E (预期市盈率): 14.83
  - Price-to-sales (市销率): 2.82
  - Revenue growth (收入增长): 43.4%
  - Gross margin (毛利率): 38.6%
  - Operating margin (经营利润率): 26.6%
  - Profit margin (净利润率): 11.5%
  - Free cash flow (自由现金流): $476.88M
  - Total cash (现金及等价物): $658.00M
  - Total debt (总债务): $19.93B
- **Risk and volatility (波动性):** Volatility level is High. Macro sensitivity: High sensitivity to energy prices, rates, and policy intervention.
- **Analyst interpretation:** Price action shows mixed momentum (动量), high volatility (波动性), and 0.84x relative volume (相对成交量); valuation metrics are more moderate, with trailing P/E 27.2x, forward P/E 14.8x, and price-to-sales 2.8x; yfinance revenue growth (收入增长) is 43.4%; the margin profile (利润率结构) is thin. The balance sheet (资产负债表) shows debt above cash; 3 verified company headlines add sentiment (市场情绪) context, and the next earnings calendar (财报日历) date is 2026-08-06.
- **Investment view:** Avoid for now
- **What to watch next:** Lower volatility (波动性) or a more attractive risk/reward (风险回报比) setup after a pullback (回调).


## Market Risk Dashboard

### Macro sensitivity risk

- **Rule-based level:** Medium
- **Verified input basis:** Macro market snapshot inputs from yfinance: 10-year Treasury yield proxy (10年期美国国债收益率代理) latest 4.45, 20-day change -2.6%; VIX volatility index (VIX波动率指数) latest 18.63, 20-day change +9.5%; Nasdaq 20-day change -4.4%; S&P 500 20-day change -2.1%; US dollar index (美元指数) 20-day change +2.4%. Watchlist yfinance price inputs are available for 11 of 11 stocks; average 5-day change is -2.0%, average 20-day change is -2.6%, and 4 stocks show high volatility (波动性).
- **Interpretation:** Nasdaq and S&P 500 price action points to weaker equity risk appetite (股票风险偏好). The VIX volatility index (VIX波动率指数) is higher over 20 trading days, so volatility pressure (波动性压力) is higher. A higher US dollar index (美元指数) proxy can add cross-market sensitivity.

### Valuation risk (估值风险)

- **Rule-based level:** High
- **Verified input basis:** 2 stocks have elevated P/E or price-to-sales metrics within the available yfinance fundamental snapshots. Macro market snapshot shows Nasdaq/S&P 500 average 20-day change -3.3%.
- **Interpretation:** Valuation risk (估值风险) remains worth monitoring because elevated P/E or price-to-sales metrics can be more sensitive when Nasdaq/S&P 500 price action points to weaker equity risk appetite (股票风险偏好).

### Earnings calendar risk (财报日历风险)

- **Rule-based level:** Medium-High
- **Verified input basis:** Verified yfinance earnings calendar (财报日历) dates are available for 11 of 11 stocks.
- **Interpretation:** The dashboard does not infer earnings results; it only flags that upcoming reporting dates can affect sentiment (市场情绪) as companies update investors.

### Volatility risk (波动性风险)

- **Rule-based level:** High
- **Verified input basis:** VIX volatility index (VIX波动率指数) from yfinance: latest 18.63, 5-day change +13.5%, 20-day change +9.5%. 4 stocks show high volatility (波动性) in the watchlist. Average 5-day change is -2.0%, and average 20-day change is -2.6%.
- **Interpretation:** Volatility risk (波动性风险) is more elevated because the VIX volatility index (VIX波动率指数) is higher over 20 trading days, while watchlist stocks marked high volatility (波动性) can amplify sentiment (市场情绪) swings.

### Policy / geopolitical headline risk (政策 / 地缘政治标题风险)

- **Rule-based level:** High
- **Verified input basis:** 15 verified company headlines mention AI, semiconductors, China, export restrictions, or policy-related terms within verified Finnhub headlines.
- **Interpretation:** Policy headline risk (政策标题风险) can affect sentiment (市场情绪) in AI and semiconductor-linked stocks, but the dashboard does not infer policy outcomes or management commentary.


## Watchlist

### Tickers

NVDA, AMD, TSM, ASML, MSFT, GOOGL, META, AMZN, MU, CEG, VST

### Macro Indicators

10-year Treasury yield, CPI inflation, Federal Reserve policy, US dollar, unemployment rate

## Notes

- yfinance is used for real price and volume data when available.
- Macro market snapshot uses yfinance when available.
- Macro event calendar uses FMP when available, official public release schedules when FMP is unavailable, and local YAML as final fallback.
- Finnhub is used for verified company news when FINNHUB_API_KEY is set.
- Earnings calendar uses yfinance when available.
- Basic fundamentals use yfinance when available.
- Theme read-throughs are rule-based and use available watchlist price, volume, news, and basic fundamental inputs.
- Market Risk Dashboard is rule-based and uses available macro market snapshot, watchlist price, volume, news, earnings calendar, and basic fundamental inputs.
- Tickers marked mock fallback use sample price and volume values.
- Analyst interpretation is rule-based and uses available verified price, news, earnings calendar, and basic fundamental inputs.
- No LLM APIs were called.
- Facts from available inputs are separated from interpretation where practical.
- The report is written in English with Chinese translations added for selected difficult terms.
- Single stock analysis uses a real-data-ready model designed for future API integration.
- The stock watchlist uses research-style labels only and does not provide personalized financial advice.