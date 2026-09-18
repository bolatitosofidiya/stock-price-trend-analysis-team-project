## Introduction

Stock markets generate large volumes of numerical data every trading day, but numbers alone do not tell a story. This report interprets the results produced by the Stock Price Trend Analysis System, built to answer a simple but important question. What happened to ALPHA, BETA, and GAMMA over ten trading days, and what does that movement actually mean.
## What Happened

Over the ten-day observation period, the three stocks moved in noticeably different directions. ALPHA and GAMMA both showed an overall increase during the period. ALPHA started with a closing price of 102 and ended at 115, while GAMMA started at 201 and ended at 215. BETA moved in the opposite direction, starting with a closing price of 153 and ending at 134, showing an overall downward movement.
## Which Stock Performed Strongest?
ALPHA performed the strongest overall. It increased from 102 to 115, giving an overall return of about 12.75%. Unlike GAMMA, which had several sharp ups and downs, ALPHA showed a more consistent upward movement throughout the ten days.
## Which Stock Performed Weakest

BETA had the weakest performance during the ten-day period. Its closing price started at 153 and ended at 134, giving an overall return of approximately -12.42%. Unlike ALPHA and GAMMA, which both ended the period higher than they started, BETA showed an overall downward movement.

## Which Stock Showed the Greatest Volatility

In this project, volatility is measured using the average daily range, which is the average difference between the highest and lowest price of a stock each day.

`daily_range = high - low`

GAMMA had the highest average daily range at 13.80, compared to 6.90 for BETA and 4.90 for ALPHA. This shows that GAMMA experienced larger price movements during the period, making it the most volatile of the three stocks.

## What Surprised Me

One thing that surprised me from the analysis was how differently the three stocks behaved within the same ten-day period. I initially expected that a stock with a positive overall return would have a fairly steady increase. However, GAMMA showed me that this is not always the case. Although it ended the period higher than where it started, its prices moved up and down more noticeably compared to ALPHA.

I also found it interesting that the largest price movement for GAMMA happened towards the end of the period, when its trading volume was also at its highest. This made me realise that looking only at the starting and ending prices would not give the full picture. Looking at the daily changes, percentage changes, and trading volume helped me understand that a stock can have a positive overall result while still experiencing significant daily fluctuations.

## What This Dataset Cannot Tell Us

The dataset shows us what happened to the stock prices and trading volumes during the ten-day period, but it does not explain why those changes happened. For example, we cannot tell whether a price went up because of investor confidence, company news, market conditions, or some other reason. We also cannot use this small dataset to predict what will happen to the stocks in the future.

Another limitation is that ALPHA, BETA, and GAMMA are simulated stocks, so there is no real company information behind them. This means the analysis does not cover things like company financial performance, management decisions, economic events, or investor sentiment. The results should therefore be seen as an analysis of the data provided and not as investment advice or a prediction of future performance.

## Why This Matters to Africa

I think this type of project is relevant to Africa because financial and market data is becoming increasingly important as more people become interested in investing and understanding financial markets. Being able to take raw data and turn it into information that is easier to understand is a useful skill for students, analysts, researchers, and investors.

For me, this project also showed that you do not always need a complicated system to start working with data. Using basic Python concepts, I was able to work with stock data, calculate daily changes, identify trends, and present the results in a more understandable way. With real data from African markets such as the Nigerian Exchange, this type of analysis could be developed further and used for learning, research, and financial data analysis. It also shows why developing data and analytical skills is important as African financial markets continue to grow.
## Conclusion

Given sixty seconds to summarize this analysis to a decision maker, the answer would be this. Across the ten days measured:
1. ALPHA grew steadily and consistently.
2. BETA declined steadily and consistently.  
3. GAMMA grew overall but with far more volatility and trading activity than the other two, especially toward the end of the period. 
These are patterns the data clearly supports. What caused them, investor behavior, external news, or something else entirely, is something this dataset cannot answer, and any decision maker acting on this report should treat these findings as a description of what happened, not an explanation of why, and certainly not a prediction of what happens next.

