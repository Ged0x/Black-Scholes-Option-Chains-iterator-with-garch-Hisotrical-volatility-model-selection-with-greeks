# Black-Scholes-Option-Chains-iterator-with-garch-Historical-volatility-model-selection-with-greeks
**Option Pricing Tool:** Python script with Black-Scholes model for option pricing &amp; Greeks analysis. Choose GARCH/historical volatility. Interactive interface. (This project uses the vanilla Black-Scholes model) (The plotting of the graph of greeks is based on strike price and option price as test, feel free to plot in anyway you desire)


 ![BLACK SCHOLES RAMO](https://github.com/Ged0x/Black-Scholes-Option-Chains-iterator-with-garch-Hisotrical-volatility-model-selection-with-greeks/assets/143278786/1f051d3d-0adb-4f43-a558-0891dbfd8217)


**Option Pricing Tool with Black-Scholes Model**

This Python repository offers a tool for option pricing utilizing the Black-Scholes model, alongside features for analyzing option Greeks and volatility. The Black-Scholes model serves as a fundamental mathematical framework for estimating financial option prices, assuming efficient markets and a geometric Brownian motion for underlying asset prices.

**Key Features:**

- **Option Pricing:** Compute theoretical prices for European call and put options using the Black-Scholes formula, incorporating parameters like asset price, strike price, time to expiration, risk-free rate, and volatility.
  
- **Greeks Analysis:** Visualize the sensitivity of option prices vs strike price to changes in underlying parameters such as price (delta), volatility (vega), time (theta), and more, aiding in risk management and strategy development.

- **Volatility Modeling:** Select between GARCH and historical volatility models to estimate the volatility parameter, crucial for accurate option pricing.

- **Interactive Interface:** Enjoy user-friendly prompts and interactive graphs for seamless analysis and decision-making.

**Usage:**

1. **Input Data:** Run the script and provide the desired ticker symbol for the underlying asset.
  
2. **Option Selection:** Choose the expiration date and type of option (call or put) from the available options chain.
  
3. **Volatility Modeling:** Opt for either the GARCH or historical volatility model to estimate volatility and visualize option prices and Greeks accordingly.

**Dependencies:**
- import numpy as np
- from scipy.stats import norm
- import yfinance as yf
- from volatility_Garch_demo import calculate_GARCH_volatility
- from historical_volatility import calculate_historical_volatility
- from datetime import date, datetime
- import time
- import matplotlib.pyplot as plt
- import mplcursors
**GARCH Model**
- import arch
- import math



**GREEKS PARTIAL DERIVATIVES**

- Delta : Measures the sensitivity of the option price to changes in the underlying asset price (S).
- Theta : Measures the sensitivity of the option price to changes in time to expiration (T)
- Gamma : Measures the rate of change of delta with respect to changes in the underlying asset price.
- Vega :  Measures the sensitivity of the option price to changes in volatility (sigma)
- Rho : Measures the sensitivity of the option price to changes in the risk-free interest rate (r)




**Note:** This tool serves educational and informational purposes exclusively and does not constitute financial advice. Users must conduct thorough research and consult with financial experts before making investment decisions.

Feel free to contribute, suggest enhancements, or report issues to improve the tool's functionality and usability!

