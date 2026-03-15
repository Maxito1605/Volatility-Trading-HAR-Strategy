# Volatility Trading Strategy: The HAR Model Approach 📈

## Overview
This project focuses on forecasting **Realized Volatility** and implementing a systematic trading strategy on the S&P 500. The core of the research is the application of the **HAR (Heterogeneous Autoregressive) model** developed by **Fulvio Corsi**, which is widely recognized for its ability to capture the multiscale nature of financial markets.

## Key Methodology
The analysis leverages the **Heterogeneous Market Hypothesis**, which assumes that market participants have different investment horizons:
* **Short-term (Daily):** Captures the impact of high-frequency traders.
* **Medium-term (Weekly):** Reflects the behavior of portfolio managers.
* **Long-term (Monthly):** Represents the perspective of institutional investors.

By comparing the HAR model forecasts with the **Implied Volatility (VIX)**, we identify mispricing in the options market to execute **Straddle and Strangle** strategies.

## Project Structure
* 📄 **[Technical_Report_HAR.pdf](./Technical_Report_HAR.pdf)**: The complete academic report detailing the mathematical framework, regression results, and strategy performance.
* 💻 **[Volatiliy_Trading_Strategy.ipynb](./Volatiliy_Trading_Strategy.ipynb)**: Jupyter Notebook containing the Python implementation (Data cleaning, HAR model estimation, and Backtesting).
* 📊 **[Project_Presentation.pptx](./Project_Presentation.pptx)**: Executive summary of the project goals and findings.


## Tools & Libraries
* **Language:** Python
* **Libraries:** Pandas, NumPy, Statsmodels (for OLS regressions), Matplotlib/Seaborn.
* **Models:** HAR-RV (Corsi, 2009), Ordinary Least Squares (OLS).
