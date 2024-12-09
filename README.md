# **Volatility Risk Premium in US Equity Options**

This project investigates the volatility risk premium in US equity options by analysing the relationship between implied and realized volatility across different times to expiration. The analysis focuses on at-the-money call options for the 200 most liquid US stocks over a recent two-year period, examining expirations of 1, 2, 3, and 4 months. Implied volatility was calculated using the Black-Scholes model, while realised volatility was derived from historical price data.

To assess the predictive accuracy of implied volatility, a Heterogeneous Autoregressive (HAR) model was trained using lagged implied volatility features. The project identifies patterns of mispricing and explores how deviations between implied and realised volatility vary across time horizons.

The primary limitation is the restricted two-year dataset, which may not capture long-term trends or volatility behavior across varying market conditions. Nonetheless, the project provides valuable insights into the volatility risk premium and enhances quantitative finance expertise.