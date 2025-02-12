# Portfolio Risk Analysis

This project assesses the risk of a diversified portfolio using Value at Risk (VaR) and other risk metrics. It includes historical simulation, Monte Carlo simulation, and stress testing.

## Key Features
- **Portfolio Construction**: A diversified portfolio of 20 stocks and 1 ETF.
- **Risk Metrics**:
  - 1-day 95% VaR (Historical Simulation): $25,094.20
  - 1-day 95% VaR (Monte Carlo Simulation): $25,456.83
  - 1-day 95% VaR (Variance-Covariance): $25,698.38
  - Stress Test 1-day 95% VaR (20% crash): $20,075.36
  - 1-day 95% CVaR: $39,576.99
  - Sharpe Ratio: 0.04
  - Maximum Drawdown: -32.09%
- **Visualizations**: Interactive plots using Plotly.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yashberi-08/Portfolio_Risk_Analysis.git
