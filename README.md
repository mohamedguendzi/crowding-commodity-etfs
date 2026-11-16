# Speculative Crowding and Commodity ETF Strategies

Tests whether a crowding indicator built from weekly CFTC positioning data improves commodity trading strategies:
cross-sectional momentum on 12 commodity ETFs, then long-short portfolios built from Ridge and XGBoost forecasts.
With the paper's timing, the indicator raises the momentum Sharpe ratio from 0.25 to 0.38, but the gain disappears
when only published positions are used. On the machine-learning strategies, it brings no significant alpha.

- Notebook: [`crowding_commodity.ipynb`](crowding_commodity.ipynb)

Course project, *Machine Learning for Portfolio Management and Trading*, with Hafsa El Ibrahimi.
Runs in the environment of the course package [`skfin`](https://github.com/schampon/skfin); data are downloaded when the notebook runs.

Following W. Kang, K. G. Rouwenhorst and K. Tang, *Crowding and Factor Returns*, SSRN working paper, 2021.
