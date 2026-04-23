# Univariate Time Series Analysis: Uganda GDP (2016–2025)

## Executive Summary
This project performs a rigorous univariate time series analysis on Uganda's GDP at Current Market Prices, spanning from **2016 Quarter 1 to 2025 Quarter 2**. Utilizing data from the **Uganda Bureau of Statistics (UBOS)**, the study identifies a significant structural break in the series and implements a seasonal ARIMA model to forecast future economic performance.

### Key Findings
* **Growth Acceleration:** The analysis quantifies a **72.4% nominal growth acceleration** following a identified regime shift.
* **Structural Stability:** A **Chow Test** was employed to statistically validate the presence of a structural break, leading to a bifurcated analysis of the pre-break and post-break periods.
* **Forecasting:** An 8-quarter ahead forecast was generated, providing insight into the expected trajectory of the Ugandan economy through 2027.

---

## Methodology & Tools
The analysis was conducted using **R** within the **RStudio** environment, leveraging the following statistical techniques:

* **Descriptive Statistics:** Initial data exploration and distributional analysis.
* **Stationarity Testing:** Augmented Dickey-Fuller (ADF) tests to determine the order of integration.
* **Model Selection:** Identification of the optimal **SARIMA(1,1,0)(0,1,0)[4]** model based on AIC/BIC criteria.
* **Diagnostics:** Ljung-Box tests and residual analysis (ACF/PACF) to ensure model adequacy.

### Technologies Used
* **R (Tidyverse, ggplot2, forecast, tseries)**
* **SQL** (For initial data cleaning/structured queries)
* **GitHub Actions** (For version control and documentation)

---

## Repository Structure
* `GDP_at_Market_Price__2016_Q1_to_2025_Q2.Rmd`: The primary R Markdown source code.
* `GDP_at_Market_Price__2016_Q1_to_2025_Q2.md`: The rendered report for direct browser viewing.
* `GDP_2016_Q1_to_2025_Q2.csv`: The raw dataset sourced from UBOS.
* `plots/`: Directory containing visualization outputs (ACF, PACF, and Forecast plots).

---

## How to View the Results
To see the full analysis with rendered charts and statistical tables, please open the [**GDP_at_Market_Price__2016_Q1_to_2025_Q2.md**](./GDP_at_Market_Price__2016_Q1_to_2025_Q2.md) file.

---

## About the Author
**Kyagambiddwa J Kelly** *Aspiring Quantitative Economist & Data Scientist* Year 3 Finalist, Bachelor of Statistics  
**Makerere University**