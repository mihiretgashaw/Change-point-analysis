📌 Project Title:

Change point analysis and statistical modeling of time series data

📖 Overview
This project applies Bayesian inference, ARIMA modeling, and GARCH volatility analysis to historical Brent oil prices. The goal is to detect structural changes in price behavior, forecast future trends, and understand risk dynamics over time.

Implementation:

🧠 Bayesian Change Point Detection using PyMC

📈 ARIMA Forecasting

📊 GARCH Volatility Modeling

🧮 Statistical testing & time series diagnostics

📉 An interactive dashboard (optional) for business stakeholders

🎯 Objectives

Understand historical shifts in Brent oil returns.

Detect statistically significant change points.

Forecast short-term returns using classical time series methods.

Model volatility to analyze risk exposure over time.

Deliver insights with a clear narrative and visual outputs.

🔍 Key Insights
Detected a significant regime shift in volatility/mean returns using Bayesian methods.

ARIMA(1,0,1) model captured short-term return dynamics reasonably well.

GARCH(1,1) model revealed clear volatility clustering, common in oil markets.

Combined, these models inform better risk-aware forecasting strategies for policy or investment purposes.

🛠 Tools & Technologies

| Tool                | Purpose                        |
| ------------------- | ------------------------------ |
| PyMC                | Bayesian change point modeling |
| ARIMA (statsmodels) | Time series forecasting        |
| ARCH (arch package) | Volatility modeling            |
| Matplotlib/Seaborn  | Visualization                  |
| Pandas/NumPy        | Data manipulation              |
| Jupyter             | Exploratory data analysis      |

📂 Project Structure

├── data/
│ └── brent_prices.csv
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_bayesian_model.ipynb
│ ├── 03_exploratory_analysis.ipynb
│ ├── 04_timeseries_analysis.ipynb # Includes ARIMA & GARCH
├── outputs/
│ ├── model_results/
│ └── timeseries_analysis/
├── dashboard/ (optional)
├── README.md
