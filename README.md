This project is a demonstration of applying genetic algorithms (GAs) and evolutionary computation techniques to optimize portfolio weights for a selection of 10 assets from various industries. The goal is to find an optimal solution that balances risk and return.

The project utilizes several libraries, including fmsb, caret, ggplot2, GA, quantmod, xts, and zoo, to handle financial data and implement GAs. The selected assets for the portfolio include Vanguard Total Index Funds, Apple Inc., Vanguard Index 500 Funds, Spire Inc., Tesla, Franklin Convey Company, Advanced Micro Devices, Spi Energy Co., Vital Energy, and KB Home.

The project retrieves historical stock data from Yahoo Finance using the quantmod library and calculates daily returns for each asset. The data is then divided into training and testing sets based on the time period. Covariance is calculated to assess the correlation between the assets.

The project includes functions for evaluating portfolio returns and the Sharpe ratio, which is a measure of risk-adjusted returns. The GA algorithm is used to optimize the portfolio weights by maximizing the Sharpe ratio while satisfying constraints such as the sum of weights equaling 1 and individual weights being between 0 and 1.

The results of the optimization process are obtained using the GA function and displayed in a plot showing the cumulative returns of the optimized portfolio compared to the cumulative returns of the individual assets.

Overall, this project demonstrates the application of evolutionary computation techniques to financial portfolio optimization, providing insights into the potential benefits of using GAs in the field of finance and AI.
