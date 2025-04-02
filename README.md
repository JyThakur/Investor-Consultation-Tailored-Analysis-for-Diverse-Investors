# NYSE Stock Analysis & Investment Recommendation System  

## Introduction  
This project analyzes historical stock data from the **New York Stock Exchange (NYSE)** to provide tailored investment recommendations for two investor profiles:  
- **Low-risk, moderate-return** (e.g., retirees like *Mr. Patrick Jyenger*).  
- **High-risk, high-return** (e.g., aggressive investors like *Mr. Peter Jyenger*).  

The dataset includes **25 stocks across 6 industries** (Technology, Finance, Aviation, Healthcare, Pharmaceuticals, and S&P500) from 2010–2021, covering metrics like daily prices, returns, and volatility.  

---

## Objective  
1. **Analyze trends** in stock performance using time-series visualization (line plots, candlesticks).  
2. **Evaluate risk-return trade-offs** via statistical metrics (coefficient of variation, standard deviation).  
3. **Recommend optimized portfolios** based on correlation heatmaps and cumulative returns.  

---

## Steps Conducted  
1. **Data Preparation**  
   - Merged multiple CSV files into a unified dataframe.  
   - Cleaned data (handled NULLs, normalized formats).  
   - Calculated derived metrics: *Daily Returns*, *Cumulative Returns*, and *Coefficient of Variation*.  

2. **Exploratory Analysis**  
   - Visualized industry-wise trends using:  
     - **Pair plots** for correlation.  
     - **Heatmaps** for inter-stock relationships.  
     - **Candlestick charts** for price trends (uptrend/downtrend).  

3. **Statistical Profiling**  
   - Ranked stocks by risk (std) and return (mean).  
   - Identified outliers and pandemic-driven anomalies (2020–2021).  

4. **Portfolio Construction**  
   - **Patrick’s Portfolio (Low Risk)**: AAPL, AMZN, JNJ, UNH, LUV.  
   - **Peter’s Portfolio (High Risk)**: AMZN, AAPL, FB, UNH, ALK.  

5. **Validation**  
   - Backtested portfolios using 5-year and 10-year cumulative returns.  

---

## Results  
- **Patrick’s Portfolio**:  
  - **10-Year Return**: ~12% (stable growth, low volatility).  
  - Best performers: *AAPL* (Tech) and *UNH* (Healthcare).  

- **Peter’s Portfolio**:  
  - **10-Year Return**: ~18% (higher volatility, peaks in Tech stocks).  
  - Top asset: *AMZN* (25% return).  

**Key Insights**:  
- Technology and Healthcare outperformed other sectors.  
- Pharmaceuticals and IBM were consistently poor performers.  
- Diversification reduced risk without sacrificing returns.  

---

## Conclusion  
This project demonstrates how data-driven analysis can align investments with risk appetites. By leveraging correlation heatmaps and trend visualizations, we constructed portfolios that balance risk and return effectively.  

---

### Tools Used  
- **Python Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Plotly.  
- **Visualization**: Pair plots, heatmaps, candlestick charts.  
- **Statistical Metrics**: Coefficient of variation, standard deviation.  

**Author**: Jay Thakur

---

Feel free to explore the code, tweak the model, and visualize the results further. Contributions and feedback are welcome!  

---
