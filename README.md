# U.S. Economic Vital Signs: 5 Years of Macro Data

This repository presents a comprehensive analysis of U.S. macroeconomic indicators from **January 2018 to mid-2025**, focusing on trends in inflation, interest rates, and money supply. Through interactive visualizations, statistical methods, and unsupervised machine learning techniques, this project explores how policy responses and economic shocks have shaped the post-pandemic macro environment.

## 📌 Project Objectives

- Analyze the interactions among key economic indicators such as **CPI**, **M2 Money Supply**, **Fed Funds Rate**, **SOFR**, and **10-Year Treasury Yield**
- Identify distinct **monetary policy regimes** using clustering (KMeans)
- Investigate **lag effects** between monetary actions and inflation responses
- Provide **policy-relevant insights** through data visualizations and correlation analysis

## 🧾 Dataset Overview

- **Timeframe:** January 2018 – Mid 2025 (monthly data)
- **Frequency:** Monthly
- **Source:** Public U.S. economic data sources (e.g., FRED, BLS, BEA)
- **Variables:**
  - `Date`
  - `CPI` – Consumer Price Index
  - `Inflation_Rate_%`
  - `Fed Funds Rate`
  - `10Y Treasury Yield`
  - `SOFR` – Secured Overnight Financing Rate
  - `M2_Money_Supply`

## 📈 Key Analyses

### 1. Time Series Visualization
- CPI and inflation rate over time
- Interest rate trends (Fed Funds Rate, SOFR, 10Y Treasury)

### 2. Correlation Matrix
- Quantifies relationships among CPI, M2, interest rates, and inflation

### 3. Regime Clustering (KMeans)
- Identifies 3 distinct monetary policy regimes using CPI and Fed Funds Rate

### 4. M2 vs CPI Comparison
- Visual evidence of money supply influence on long-term price levels

### 5. Policy Timing & Lag Analysis
- Interprets delayed impact of interest rate hikes on inflation outcomes

## 📊 Tools & Technologies

- `Python` (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn)
- `Excel` (data cleaning and initial processing)
- `GitHub` (version control and collaboration)
- `Jupyter Notebooks` (for exploratory analysis and modeling)

## 📚 Folder Structure

```bash
├── data/              # Raw and cleaned macroeconomic data
├── notebooks/         # Jupyter notebooks for analysis and visualization
├── outputs/           # Charts, plots, and exported figures
├── models/            # KMeans clustering results and model objects
├── README.md

Key Insights
Fed interest rate policy followed three distinct regimes tied to economic shocks.

M2 growth and CPI are strongly correlated, supporting monetary theory.

Fed rate hikes in 2022–2023 were sharp, with inflation responding after a delay.

SOFR, Fed Funds Rate, and Treasury Yield are tightly interlinked.

KMeans clustering effectively segments macro conditions for policy interpretation.

📌 Recommendations
Policymakers should account for policy lags and monitor money supply growth closely.

Economic models should incorporate regime-based behavior rather than assume linearity.

Machine learning tools can enhance real-time monitoring and early warning systems.

📬 Contact
For questions or collaboration opportunities, please contact:
📧 your.email@example.com
🔗 LinkedIn: [Your Name]

This repository is for educational and research purposes. Data sources are publicly available and cited in the full report.
