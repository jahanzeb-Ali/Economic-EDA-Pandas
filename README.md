# 📊 US Economic Analysis with FRED API

A data analysis project exploring key US economic indicators using the **Federal Reserve Economic Data (FRED) API**. Built with Python and Pandas as part of my Data Science learning journey.

---

## 🔍 Project Overview

This project fetches and analyzes real macroeconomic data directly from the Federal Reserve's FRED API — no pre-cleaned datasets. The goal was to understand unemployment trends, labor force participation, and market performance across all 50 US states, with a focus on the COVID-19 period (2020–2022).

---

## 📈 Key Analyses

### 1. S&P 500 Historical Performance
- Fetched and visualized the full S&P 500 price history using FRED series `SP500`

### 2. State-Level Unemployment Rates
- Retrieved monthly, seasonally adjusted unemployment rates for all 50 US states
- Ranked states by unemployment rate as of **May 2023** using a horizontal bar chart

### 3. Labor Force Participation Rates by State
- Pulled monthly participation rate data for each state
- Cleaned and mapped FRED series IDs to state names

### 4. Unemployment vs. Participation — COVID-Era Comparison (2020–2022)
- Built **dual-axis charts** for all 50 states showing unemployment and participation rates side by side
- Key insight: States with the sharpest unemployment spikes also saw the steepest drops in participation — meaning people weren't just losing jobs, they were **leaving the workforce entirely**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Static visualizations |
| Plotly Express | Interactive charts |
| FRED API (`fredapi`) | Live economic data |
| NumPy | Numerical operations |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/jahanzeb-Ali/Economic-EDA-Pandas.git
cd economic-analysis-fred
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib plotly fredapi
```

### 3. Get your FRED API Key
- Sign up for a free API key at [fred.stlouisfed.org](https://fred.stlouisfed.org/docs/api/api_key.html)
- Replace the `fred_key` variable in the notebook with your key

### 4. Run the notebook
```bash
jupyter notebook Economic_Analysis_with_Pandas.ipynb
```

---

## 📊 Sample Visualizations

> *Add screenshots of your charts here — e.g., the 50-state bar chart and the dual-axis COVID comparison*

---

## 💡 Key Findings

- **COVID impact was uneven**: Some states (e.g., Hawaii, Nevada) saw unemployment spike above 20% in 2020, while others remained relatively stable
- **Participation rate lag**: Even as unemployment recovered by 2022, participation rates in many states had not fully rebounded — indicating lasting workforce changes
- **S&P 500 resilience**: Despite the unemployment shock of 2020, the market recovered rapidly, diverging from labor market trends

---

## 📁 Project Structure

```
economic-analysis-fred/
│
├── Economic_Analysis_with_Pandas.ipynb   # Main analysis notebook
└── README.md                             # Project documentation
```

---

## 🌱 About This Project

This is one of my first independent data analysis projects, built while enrolled in a Data Science & Machine Learning course. I chose to work with live API data instead of a static dataset to practice real-world data wrangling — messy data, missing values, and all.

**Currently learning:** Machine Learning | **Completed:** Pandas, EDA

---

## 📬 Connect

Feel free to connect on [LinkedIn](https://www.linkedin.com/in/jahanzeb-soomro-214a5226a/) or reach out if you have feedback!

---

*Data sourced from the [Federal Reserve Bank of St. Louis (FRED)](https://fred.stlouisfed.org/)*
