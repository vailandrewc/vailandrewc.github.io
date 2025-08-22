# Andrew Vail - Quantitative Finance Portfolio
Investment analysis portfolio featuring equity research reports, financial models, and quantitative studies by Andrew Vail

**www.linkedin.com/in/andrewcvail**

MSc Financial Management, Investment Analysis, Boston University | Former Professional Baseball Player

## Featured Analysis

### [Sweetgreen Inc. (NYSE: SG) - Equity Research Report](./Sweetgreen_Investment_Thesis_Report.pdf)
**Investment Recommendation: SHORT | DCF Implied Price: $10.47**
- DCF analysis with EV/Revenue multiple validation (1.56x vs. 2.23x market)
- 30% discount to market multiple reflects G&A leverage execution risk
- Scenario analysis weighted by G&A scaling probability (Bear 50%, Base 35%, Bull 15%)
- Short thesis based on unproven automation scalability, published 07/23/25

  **[Financial Model (Excel)](./Sweetgreen_Valuation_Model.xlsx)**

  **[Full Report (PDF)](./Sweetgreen_Investment_Thesis_Report.pdf)**

## Additional Case Studies

### [Apple Inc. (AAPL) - Financial Analysis](./Apple_Financial_Analysis.pdf)
**Multi-year fundamental analysis with investment recommendation**
- Comprehensive ratio analysis across liquidity, profitability, and solvency
- 3-year trend analysis of ROI (27.50%), ROE (171.95%), and P/E ratios
- Peer benchmarking against Microsoft and S&P 500 averages
- Investment thesis supporting $10,000 position based on strong capital efficiency

**[Full Report (PDF)](./Apple_Financial_Analysis.pdf)**

### Fama-French Factor Analysis
- Applied 3- and 5-Factor models in R and Excel to forecast global mutual fund returns
- Computed and visualized factor loadings, alpha, and t-statistics using robust OLS regression
- Presented equity curves and correlation heatmaps across market-neutral portfolios.

### [Low Volatility Anomaly Study](./Low_Volatility_Anomaly_Analysis.html)
**Comprehensive quantitative research validating the low volatility anomaly across 360 S&P stocks (2002-2021)**

**Key Findings:**
- **Anomaly confirmed** in 60% of time periods analyzed (3 of 5 subsets)
- **Optimal portfolio** identified in mid-volatility range (Portfolio 5: 1.05% returns, 1.07 beta)
- **High-beta underperformance**: Portfolio 10 (highest vol/beta) consistently delivered lowest returns
- **CAPM breakdown**: Traditional risk-return relationship failed in majority of periods

**Research Methodology:**
- **360-stock universe** sorted into 10 decile portfolios (36 stocks each)
- **Multi-period validation** across 5-year subsets (2002-2006, 2007-2011, 2012-2016, 2017-2021)
- **Comprehensive risk metrics**: Beta calculations via OLS regression, portfolio variance using covariance matrices
- **Sector analysis**: Individual stock examples (AMD β=2.37, Southern Company β=0.23)

**Investment Implications:**
- **Behavioral explanations**: Investor biases toward "lottery" stocks, institutional constraints
- **Risk management**: Volatility drag effects on compounded returns
- **Portfolio construction**: Evidence against high-beta strategies, support for defensive positioning

**[View Complete Analysis (HTML)](./Low_Volatility_Anomaly_Analysis.html)** 

### [Asian vs European Option Pricing](./Asian_vs_European_Option_Pricing(1).html)

This project compares the pricing of Asian and European call and put options using a combination of Monte Carlo simulation and the Black-Scholes-Merton analytical model. It highlights the effects of path dependence and averaging on option valuation.

**Overview:**

- **European options** are priced using the Black-Scholes-Merton formula.
- **Asian options** (arithmetic average) are priced via Monte Carlo simulation.
- The simulation explores both standard geometric Brownian motion and jump diffusion dynamics.

**Contents:**

- Simulation of GBM and jump-diffusion asset paths
- Black-Scholes functions for analytical option pricing
- Monte Carlo simulation for Asian call and put options
- Pricing comparison across strike prices
- Visualization and interpretation of results

**Key Insights:**

- Asian options are consistently less expensive than European options due to volatility averaging.
- The gap between Asian and European prices widens for deep in-the-money and out-of-the-money strikes.
- Path-dependent options like Asians exhibit reduced convexity and differ from traditional put-call parity.

**[View Complete Analysis (HTML)](./Asian_vs_European_Option_Pricing(1).html)**

### [Efficient Frontiers and Optimal Risky Portfolios](./Efficient_Frontiers_and_ORPs.html)

This project analyzes the construction of efficient frontiers and optimal risky portfolios (ORPs) using stock return data (AAPL, JPM, NKE, T) from 2010–2019. It combines empirical frontier estimation, out-of-sample testing, and a simulation appendix to illustrate estimation risk.

**Overview:**

- Compute efficient frontiers across three sample windows: 2010–2013, 2014–2017, 2018–2019.
- Identify Optimal Risky Portfolios (maximum Sharpe ratio) and compare weights, expected returns, volatilities, and Sharpe ratios.
- Evaluate earlier ORPs out-of-sample against 2018–2019 data to test robustness.
- Simulate “noisy” frontiers from a known distribution to show how estimation error inflates in-sample Sharpe ratios.

**Contents:**

- Data setup and return splitting across time windows
- Minimum-variance optimization with shorting allowed
- Efficient frontier plots for each sample period
- ORP tables summarizing weights and performance metrics
- Out-of-sample evaluation on 2018–2019 returns
- Appendix: simulated noisy vs. true frontiers
- Interpretation of Sharpe ratio inflation and overfitting

**Key Insights:**

- The 2010–2013 ORP delivered the strongest Sharpe (~1.22) but required shorting JPM.
- The 2014–2017 ORP was fully long and balanced but less efficient (Sharpe ~1.08).
- The 2018–2019 ORP produced the highest return (~30%) at the cost of higher volatility (~24.6%), with a Sharpe of ~1.14 and a short in T.
- Out-of-sample testing showed earlier ORPs remained serviceable but fell below the 2018–2019 frontier, highlighting efficiency loss over time.
- Simulation confirms that estimation noise inflates in-sample Sharpe ratios and explains why historical ORPs degrade out-of-sample.

**[View Complete Analysis (HTML)](./Efficient_Frontiers_and_ORPs.html)**

## Technical Skills
- **Programming**: Python (Pandas, NumPy, Scikit-learn), R, Excel/VBA
- **Financial Modeling**: DCF, 3-Statement Models, Monte Carlo
- **Statistical Analysis**: Factor models, risk modeling, backtesting

## Contact
- **Email**: vailandrewc@gmail.com
- **LinkedIn**: www.linkedin.com/in/andrewcvail
- **Location**: Available for opportunities in NYC, Boston, Philadelphia, Miami, Washington D.C.

---
*This portfolio demonstrates quantitative finance and equity research capabilities through hands-on analysis and modeling projects.*
