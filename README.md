# Project Details
Titled - Analysis of Soybean futures prices using GARCH time series modeling process. \n
(This is work done for the Capstone Project for graduate level course - ST 534 Time Series Analysis.)

In this capstone project we took monthly closing prices of soybean futures traded in the commodities markets and tried to model the price variations as a GARCH (**Generalized Autoregressive Conditional Heteroskedasticity**) time series model.


Generalized AutoRegressive Conditional Heteroskedasticity (GARCH) is a statistical model used in analyzing time-series data where the variance error is believed to be serially autocorrelated. GARCH models assume that the variance of the error term follows an autoregressive moving average process.

Understanding Generalized AutoRegressive Conditional Heteroskedasticity (GARCH)
Although GARCH models can be used in the analysis of a number of different types of financial data, such as macroeconomic data, financial institutions typically use them to estimate the volatility of returns for stocks, bonds, and market indices. They use the resulting information to help determine pricing and judge which assets will potentially provide higher returns, as well as to forecast the returns of current investments to help in their asset allocation, hedging, risk management, and portfolio optimization decisions.


GARCH models are used when the variance of the error term is not constant. That is, the error term is heteroskedastic. Heteroskedasticity describes the irregular pattern of variation of an error term, or variable, in a statistical model.

Essentially, wherever there is heteroskedasticity, observations do not conform to a linear pattern. Instead, they tend to cluster. Therefore, if statistical models that assume constant variance are used on this data, then the conclusions and predictive value one can draw from the model will not be reliable.

The variance of the error term in GARCH models is assumed to vary systematically, conditional on the average size of the error terms in previous periods. In other words, it has conditional heteroskedasticity, and the reason for the heteroskedasticity is that the error term is following an autoregressive moving average pattern. This means that it is a function of an average of its own past values.

History of GARCH
GARCH was developed in 1986 by Dr. Tim Bollerslev, a doctoral student at the time, as a way to address the problem of forecasting volatility in asset prices. It built on economist Robert Engle's breakthrough 1982 work in introducing the Autoregressive Conditional Heteroskedasticity (ARCH) model. His model assumed the variation of financial returns was not constant over time but are autocorrelated, or conditional to/dependent on each other. For instance, one can see this in stock returns where periods of volatility in returns tend to be clustered together.1

Since the original introduction, many variations of GARCH have emerged. These include Nonlinear (NGARCH), which addresses correlation and observed "volatility clustering" of returns, and Integrated GARCH (IGARCH), which restricts the volatility parameter. All the GARCH model variations seek to incorporate the direction, positive or negative, of returns in addition to the magnitude (addressed in the original model).

Each derivation of GARCH can be used to accommodate the specific qualities of the stock, industry, or economic data. When assessing risk, financial institutions incorporate GARCH models into their Value-at-Risk (VAR), maximum expected loss (whether for a single investment or trading position, portfolio, or at a division or firm-wide level) over a specified time period. GARCH models are viewed to provide better gauges of risk than can be obtained through tracking standard deviation alone.

Various studies have been conducted on the reliability of various GARCH models during different market conditions, including during the periods leading up to and after the Great Recession.

**KEY TAKEAWAYS**:
1. GARCH is a statistical modeling technique used to help predict the volatility of returns on financial assets.
2. GARCH is appropriate for time series data where the variance of the error term is serially autocorrelated following an autoregressive moving average process. 
3. GARCH is useful to assess risk and expected returns for assets that exhibit clustered periods of volatility in returns.
