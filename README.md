# Gold Price & Inflation Analysis

![screenshot-localhost_8888-2025 03 31-12_51_25](https://github.com/user-attachments/assets/79704c66-0c23-460d-ba12-e53701207385)

## Overview

This project analyzes the relationship between gold prices and inflation to assess gold’s effectiveness as an inflation hedge. Using historical gold price data (1979–2021) and Consumer Price Index (CPI) data, the analysis explores correlations, trends, and statistical measures to determine whether gold protects against rising inflation.

### Dataset

The project uses two primary datasets:

- Gold Price Data: Contains daily gold prices from 1979 to 2021, collected from global financial sources.
- Consumer Price Index (CPI) Data: Retrieved from the Federal Reserve Economic Data (FRED), measuring inflation trends over time.

### Methods & Features

The project performs the following analyses:

1. Gold Data Cleaning & Preprocessing: Standardizes column names, handles missing values, and ensures proper date indexing.

2. Feature Engineering: Calculates gold price returns, moving averages, volatility metrics, and lagged values to detect trends.

3. Inflation Analysis: Computes annual inflation rates using the CPI dataset and aligns them with gold price trends.

4. Statistical Analysis

### Visualizations

The project includes several plots to illustrate findings:

- Gold vs. CPI Trend: Compares historical price movements.
- Gold Returns vs. Inflation Scatter Plot: Shows the relationship between inflation and gold price changes.
- Rolling Correlation: Tracks how gold’s relationship with inflation evolves over time.
- Gold Performance in Different Inflation Regimes: Highlights gold returns during deflation, low, moderate, and high inflation periods.

Gold is not a perfect inflation hedge in the short term, but it offers strong long-term wealth preservation and reacts well to extreme inflation periods.

### Key Findings

- Gold’s Correlation with Inflation: 0.081 (weak positive correlation)
- Inflation Beta: 5.824 (gold reacts strongly to inflation spikes)
- Gold’s Long-Term Return: ~10% annually, indicating value preservation
- Inflation Rate: Averaged 0.08% monthly in the dataset

### Future Work

- Expand analysis to include real interest rates and monetary policy effects.
- Compare gold’s performance to other inflation hedges (e.g., TIPS, real estate, commodities).
- Extend analysis to other economic periods, such as the 1970s stagflation and the 2008 financial crisis.

### Conclusion

This project provides data-driven insights into gold’s role as an inflation hedge. While gold does not perfectly track inflation, it remains a valuable asset for long-term wealth preservation. Future studies can refine this analysis by incorporating broader economic indicators and alternative assets for comparison.

### Source

![Gold Price 1979 to Present from Kaggle](https://www.kaggle.com/datasets/jishnukoliyadan/gold-price-1979-present)
