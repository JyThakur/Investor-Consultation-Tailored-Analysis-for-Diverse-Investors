# Financial Risk Analysis on NYSE Dataset
## **Problem Statement**
> This project involves offering consultation services to two distinct investors, namely Mr Patrick Jyenger and Mr Peter Jyenger, tailoring our advice to align with their individual requirements and financial goals. While Mr Patrick Jyenger seeks low-risk investments with satisfactory returns, Mr Peter Jyenger is open to higher-risk stocks that offer potentially greater returns on investment.

## **<u>Steps performend</u>**
1. Importing Necessary Libraries
2. Importing, Cleaning and Understanding Dataset
  * Importing Dataset (.csv file) to Dataframe
    * Merging all files to create a final data frame
    * Creating a pivot table for visualization
    * Creating a new column to understand Day-to-Day changes in stocks
  * Cleaning data frame
    * Replacing all NULL/NA values with 0 (as for stock analysis each and every data row of data is important)
    * Checking for abnormal data types for columns
3. Visualization
  * Visualizing stocks of different Industries using Pair plot based on the Returns of each stock
  * Visualization of stocks using Line Graph based on Return of stocks
  * Visualizing distribution of stocks using Distribution plot based on Return from stocks
  * Visualizing correlation between stocks using Heatmap Subplots based on Return
  * Visualizing Trend Type of stocks using Candlestick
    * Uptrend
    * Downtrend
    * Sideways Trend
  * Visualizing data statistically based on Returns of each stock
4. Profiling
  * Profile 1 -> Patrick
    * Creating a new dataframe and finding Correlation between stocks using Heatmap
    * Calculating cumulative return of the stocks selected for Patrick
    * Statistical understanding based on Cumulative Returns of each stock selected for Patrick
  * Profile 2 -> Peter
    * Creating a new dataframe and finding Correlation between stocks using Heatmap for Peter
    * Calculating cumulative return of the stocks selected for Peter
    * Statistical understanding based on Cumulative Returns of each stock selected for Peter
