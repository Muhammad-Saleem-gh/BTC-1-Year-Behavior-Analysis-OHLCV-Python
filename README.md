# BTC-1-Year-Behavior-Analysis-OHLCV-Python
Comprehensive step-by-step workflow for **analyzing market behavior** using OHLCV data (Open, High, Low, Close, Volume).  
This repository is designed for **data analysts, quantitative researchers, and portfolio managers** to extract actionable insights from raw price and volume data.

---

## **Features / Modules**

### 1️⃣ Market Context & Trend Detection
- Detect overall market trend: **uptrend, downtrend, sideways**  
- Analyze high-level **price path, volume behavior, and liquidity patterns**  
- Identify if market moves **linearly** or operates in **distinct regimes**

### 2️⃣ Descriptive Analysis (KPIs & Pressure)
- Compute **key metrics**: Avg Close, Max High, Min Low, Avg Range (High-Low)  
- Determine **buying vs selling pressure** using Open vs Close  
- Visualize **distribution of price, volume, and candle body size**  
- Analyze **liquidity patterns** and detect high/low-volume windows

### 3️⃣ Candlestick Psychology
- Engineer candlestick features: **BodySize, Upper Wick, Lower Wick**  
- Classify candles: **Bullish, Bearish, Doji**  
- Detect **potential reversals / traps**  
- Visualize **body vs wick ratios**, showing market hesitation vs commitment

### 4️⃣ Volatility & Risk Characterization
- Compute **absolute and relative volatility** (High-Low, % change)  
- Rolling volatility: 3H, 6H, 24H windows  
- Identify **risk clusters** and high-risk periods  
- Visualize volatility trends and **volume-risk confirmation plots**

### 5️⃣ Time-Based Patterns
- Extract **hour, day of week, month** from timestamps  
- Visualize **hourly volume, volatility, candle type distribution**  
- Detect **predictable intraday, weekly, and monthly patterns**  
- Identify **high-risk vs safe execution windows**

### 6️⃣ Year-Long Regime Detection
- Classify each candle into **Trending, Ranging, High-Risk regimes**  
- Use **volume, body size, wick size, and volatility** for regime logic  
- Visualize **timeline and heatmaps** for regimes  
- Compute **% of time spent in each regime**  


```bash
pip install pandas matplotlib seaborn numpy mplfinance
