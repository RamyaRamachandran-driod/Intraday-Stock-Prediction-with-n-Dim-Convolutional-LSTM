In recent years, short-term or intraday stock price prediction has become a critical area of research.
Intraday predictions involve estimating stock price movements within a single trading day. This level
of forecasting is immensely valuable because it offers traders and financial institutions the opportunity
to capitalize on rapid price fluctuations, allowing for optimized buying and selling decisions that
yield profitable returns within a short timeframe.

The novelty in our ConvLSTM model lies in the use of 2D convolutional layers to capture correlations
across stock data with similar financial information and enabling more accurate same-day predictions
in a multidimensional setting. We will incorporate multiple features describing the company financial
performance like the aforementioned "Earnings Per Share (EPS)" and "Price-to-Earnings (P/E) ratio",
along with the regular stock markers like "Open", "High", "Low", "Close", "Adjusted Close" and
"Volume" used across all previous research.

This proposal revolves around the following hypotheses:
*  **Hypothesis 1:** "Introducing multi-dimensional convolutional layers to LSTM architecture
predicts intraday stock price more accurately than traditional LSTM architecture."
* **Hypothesis 2:** "Our multi-dimensional ConvLSTM network performs better in intraday
stock trading strategy of using multi-feature setting in Ghosh u. a. (2022) (adopted from
Krauss u. a. (2017)), providing daily returns greater than that obtained by their LSTM
networks"

More precisely, for hypothesis 1, we will predict stock prices in minute-wise intervals on the same
day and for hypothesis 2, we will select stocks to buy or sell short in a day to maximize returns.
We use Mean Square Error (MSE) as the performance metric for hypothesis 1 and the daily returns
percentage as that for hypothesis 2. 

Data for this project was collected from the U.S. Securities and
Exchange Commission, Kaggle and Github.
