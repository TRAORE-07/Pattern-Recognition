# Pattern-Recognition
This repository is an example of Pattern Recognition for financial time series data. In this case, for Stock Market Analysis using the AGIO dataset.
This code employs various algorithmic pattern recognition techniques to identify specific configurations in stock price and volume data.

Here is how it is implemented:
1) Feature Engineering for Pattern Recognition (calculate_indicators function)
2) Explicit Pattern Identification (identify_crosses function)
3) Volume-Based Pattern Recognition (calculate_obv function)
4) Candlestick Pattern Recognition (detect_candlestick_patterns function)
5) Visualization as a Tool for Human Pattern Recognition (plot_patterns function)

Finally, an explicit visualization of the price, MAs, Bollinger Bands, and marking the detected Golden/Death crosses and candlestick patterns.

Example of use:
- A trader can look at the chart and see if these detected patterns align with other observations or fundamental analysis.


RESULTS: Overall Trend and Volatility:
- Fluctuating Price: The "Close Price" (blue line) shows significant fluctuations, indicating that AGIO has been quite volatile over the period from late 2013 to early 2020.
- Major Peaks and Troughs: We can observe distinct periods of strong uptrends (e.g., late 2014 to early 2015, mid-2017 to mid-2018) followed by downtrends (e.g., late 2015, mid-2018 to early 2019).
- Bollinger Bands (Volatility Indicator): The Bollinger Bands (green dashed upper, red dashed lower) visually represent volatility. When the bands are wide, it indicates high volatility (e.g., during rapid price changes in 2015 and 2018). When they narrow, it suggests lower volatility or consolidation (e.g., parts of 2016-2017). Price action often stays within these bands, and breaches can indicate strong moves.
