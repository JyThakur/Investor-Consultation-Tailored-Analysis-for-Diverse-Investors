# Finance-Risk-Analysis-on-NYE
## **Problem Statement**
> The given task is to provide consultation to two different investors, Mr Patrick Jyenger and Mr Peter Jyenger based on their requirements and financial objectives.

## **<u>Steps performend</u>**
1. Importing Necessary Liberaries
2. Importing, Cleaning and Understanding Dataset
  * Importing Dataset (.csv file) to Dataframe
    * Merging all files to create a final dataframe
    * Creating a pivot table for visualization
    * Creating new column to understand Day-to-Day chnages in stocks
  * Cleaning dataframe
    * Replacing all NULL/NA values with 0 (as for stock analysis each and every data row of data is important)
    * Checking for abnormal data types for coulmns
3. Visualization
  * Visualzing stocks of different Industry uisng Pair plot based on Returns of each stocks
  * Visualization of stocks using Line Graph based on Return of stocks
  * Visualizing distribution of stocks using Distribution plot based on Return from stocks
  * Visualizing correlation between stocks using Heatmap Subplots based on Return
  * Visualizing Trend Type of stocks using Candelstick
    * Uptrend
    * Downtrend
    * Sideways Trend
  * Visualizing data statistically based on Retuns of each stocks
4. Profiling
  * Profile 1 -> Patrick
    * Creating new dataframe and finding Correlation between stocks using Heatmap
    * Calculating cumulative return of the stocks selected for Patrick
    * Statistical understanding based on Cumulative Retuns of each stocks selected for Patrick
  * Profile 2 -> Peter
    * Creating new dataframe and finding Correlation between stocks using Heatmap for Peter
    * Calculating cumulative return of the stocks selected for Peter
    * Statistical understanding based on Cumulative Retuns of each stocks selected for Peter
