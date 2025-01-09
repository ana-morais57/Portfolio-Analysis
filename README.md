# Portfolio Analysis Project

Welcome to the **Portfolio Analysis Project**! This project was a practical challenge designed to enhance my financial data analysis skills using Python.
---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Analysis Steps](#analysis-steps)
3. [Visualizations and Insights](#visualizations-and-insights)
4. [Technologies Used](#technologies-used)

---

## About the Project

### Objective

The Portfolio Analysis Project aims to evaluate a set of financial assets using Python. It envolved:
- Data preprocessing and cleaning
- Asset performance evaluation through returns and volatility calculations
- Portfolio performance analysis via visualizations
- Risk and return assessment based on annualized metrics

---

## Analysis Steps

### 1. Data Cleaning

- Standardized column names for uniformity.
- Replaced empty spaces with `NaN` values and applied forward fill to handle missing data.
- Aligned datasets to ensure matching indices for accurate calculations.

### 2. Financial Metrics Calculation

- Calculated **daily percentage returns** for each asset.
- Evaluated **cumulative returns**, **annualized returns**, and **annualized volatility** to measure portfolio performance.

### 3. Visualizations

- Created time-series plots to visualize normalized asset prices.
- Developed area charts to depict portfolio weights by asset and by category.
- Ploted historical cumulative returns to assess growth trends.

---

## Visualizations and Insights

### Key Visualizations

1. **Portfolio Asset Weights Over Time**  
   - Highlights changes in asset weights, showcasing allocation shifts during the COVID-19 pandemic.

2. **Historical Cumulative Returns**  
   - Demonstrates consistent growth with a sharp dip in early 2020 possibly due to the COVID-19 pandemic.

3. **Category-Based Area Chart**  
   - Displays portfolio diversification across categories like equities, fixed income, and alternatives.

### Insights

- **Strategy during the Pandemic**  
  - Increased fixed income dominance and reduced equity weights, reflecting a conservative approach.

- **Cumulative Returns**  
  - A positive return of **38.57%** highlights the portfolio's ability to grow, even during turbulent times.

- **Annualized Metrics**  
  - **Return**: A strong **11.69%**, suggesting effective strategies.  
  - **Volatility**: A moderate **8.58%**, indicating controlled risk.

- **Diversification**  
  - Balanced category weights underscore effective risk management.

---

## Technologies Used

- **Python Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for data visualization.
- **Jupyter Notebook** for interactive analysis.
