# portfolio-optimization-methods

This project studies how different portfolio allocation strategies perform
when realistic constraints, transaction costs, and walk-forward rebalancing
are taken into account.

## Objective

The goal is to answer the following question:

**Can portfolio optimization methods (e.g. minimum variance, maximum Sharpe)
consistently outperform a naive Equal-Weight portfolio once realistic
constraints and out-of-sample testing are applied?**

To do so, the project:
- compares several allocation methods,
- enforces long-only and weight constraints,
- applies rolling walk-forward backtesting,
- evaluates performance using risk-adjusted metrics.

## Results (snapshot)

Baseline Equal-Weight portfolio (gross returns):

![Equity Curve](reports/figures/equity_curve.png)

## Methodology & Details

All data processing, portfolio construction, optimization, and performance
analysis are documented step by step in the main notebook:

- `notebooks/01_portfolio_optimization_walkforward.ipynb`

## Repository Structure

- `notebooks/` : documented analysis and experiments
- `src/` : reusable portfolio and backtesting functions
- `data/` : raw and processed market data
- `reports/figures/` : exported figures used in the README
