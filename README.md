# CFM101-Robo-Advising-Group-Project

This is the final group project for CFM-101. The project goal was to make a program that takes a file of stock tickers as input and uses it to generate a portfolio of stocks under certain criteria. This program used yFinance, numpy, matplotlib, and pandas Python modules. Our group for this project consisted of Arteen Mirzaei, Momina Butt, and I. 

Our team chose to make a safe portfolio of stocks, so our goal was for our portfolio to have a value close to zero after five trading days and deducting the starting investment value of $500 000.

##Code Criteria:

- Code should be dynamic.
- Code should read a .csv file containing a finite number of stock tickers.
- Code should ignore all stocks not denominated in USD (US-listed stocks).
- Code should only include stocks with a minimum average monthly volume of 200 000 shares between January 1, 2022 and October 31, 2022.
- There must be a minimum of 12 and maximum of 25 stocks in the portfolio.
- Each of n number of stocks must take up (100/2n)% of the portfolio when weighted by value.
- An individual stock should not take up more than 25% of the portfolio when weighted by value.
- Fractional shares are allowed and there are no transaction costs.
- The portfolio cannot be changed after it is set.
- Teams can ignore the issue of dividends.

Our team chose to have 25 stocks to increase portfolio diversity. Our code used expected returns. standard deviation, and beta to apply different scores to each stock. Depending on these scores, our code took the stocks with the highest scores and gave them priority in the portfolio. We also tried to have as many US-listed stocks that are in different industries or countries as possible. Our actual procedure and explanation of the code is available in the 

Our final grade was an 87.5%.
