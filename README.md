# Quant_analysis
Exploring financial data 

Data Retrieval:
Utilizing pandas_datareader and yfinance, the project collects financial data for symbols "CMG," "MCD," "AAPL," and "TSLA."

Data Cleaning and Resampling:
The obtained data is refined by dropping unnecessary columns and resampling to monthly frequencies for better analysis.

Custom Resampling:
A custom resampling function is implemented, returning the first value of each period, adding flexibility to the analysis.

Handling Time Zones:
Time zone conversions are performed, transforming the data to the 'US/Eastern' time zone.

Filling Missing Values:
Techniques like filling NaN values with the mean and backfilling are employed to address missing data.

Statistical Analysis:
Descriptive statistics, including mean, standard deviation, and summary statistics, provide insights into the data.

Price Modification:
Prices are modified by doubling and subtracting 10, demonstrating the flexibility in data manipulation.

Introducing Noise:
Noise is added to the data, simulating a more realistic and dynamic financial scenario.

Returns Calculation:
Both additive and multiplicative returns are calculated, offering different perspectives on stock performance.

Visualizations:
Various visualizations, including line charts, rolling mean comparisons, and multiplicative returns, contribute to a comprehensive understanding of the financial dynamics.

Symbol Selection and Extraction:
Specific date ranges and individual stock closing prices are extracted, contributing to a focused analysis.

Analysis of Multiplicative Returns:
The project concludes with a less noisy visualization of multiplicative returns, enhancing the interpretability of the financial data.
