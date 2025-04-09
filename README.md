# Portfolio Optimization with PyPortfolioOpt

## Overview
This project focuses on optimizing a stock portfolio by cleaning financial data, computing optimal portfolio allocations, and visualizing the efficient frontier. The optimization is conducted using the `PyPortfolioOpt` library, with an emphasis on minimum volatility and maximum Sharpe ratio portfolios. Additionally, the project explores advanced techniques such as exponentially weighted covariance matrices and downside risk-adjusted optimization.

## Data Sources
- **Stock Selection:** Retrieved from **[Ansu Invest](https://ansuinvest.com/research-opinion/view/still-thinking-of-last-minute-gifts-for-your-valentine-we-ve-got-you-covered586)**
- **Price Data:** Collected from **[NepseAlpha](https://nepsealpha.com/nepse-data)**, covering the period from 2020-06-29 to 2025-03-25

## Project Workflow
1. **Data Cleaning**
   - Handling missing values
   - Extracting only closing prices for stocks and combining them into a single dataframe
   - Standardizing data formats

2. **Portfolio Optimization**
   - Constructing an optimal portfolio using `PyPortfolioOpt`
   - Computing and plotting the **Efficient Frontier**
   - Finding portfolios with **Minimum Volatility** and **Maximum Sharpe Ratio**

3. **Advanced Portfolio Techniques**
   - Using **Exponentially Weighted Covariance Matrix** for risk estimation
   - Computing **Exponentially Weighted Mean Returns**
   - Incorporating **Downside Risk (Using the semi-covariance function from PyPortfolioOpt)** for portfolio optimization

## Dependencies
To run this project, install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn PyPortfolioOpt
```

## Usage
Run the Jupyter Notebook file (`Portfolio_optimization.ipynb`) to execute the optimization steps and generate visualizations.

## Results
- Optimized portfolio weights
- Efficient frontier visualization
- Comparison of risk-adjusted return strategies

## Author
This project was developed as part of a financial data science initiative. Contributions and feedback are welcome!


