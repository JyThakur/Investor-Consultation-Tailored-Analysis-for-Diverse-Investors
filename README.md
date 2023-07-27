# Personalized Investment Consultation: Catering to Diverse Financial Goals using Exploratory Data Analysis
## **Problem Statement**
<p align="justify">This academic endeavour entails providing personalized consultation services to two separate investors, namely Mr Patrick Jyenger and Mr Peter Jyenger, catering to their distinct financial objectives and preferences. Mr Patrick Jyenger is inclined towards low-risk investments with reasonable returns, while Mr Peter Jyenger is open to higher-risk stocks offering potentially higher returns on investment. The analysis will involve data cleaning and exploratory data analysis, specifically delving into NYSE data of select highly profitable companies. Python will be utilized as the primary programming language to achieve these research objectives.</p>

## **<u>Steps performend</u>**
1. Importing Necessary Libraries
2. Importing, Cleaning and Understanding Dataset
  * Importing Dataset (.csv file) to Dataframe
    * Merging all files to create a final data frame
    * Creating a pivot table for visualization
    * Creating a new column to understand Day-to-Day changes in stocks
  * Cleaning data frame
    * Replacing all NULL/NA values with 0 (as for stock analysis each and every data row of data is important)
    * Checking for abnormal data types in columns
3. Visualization
  * Visualizing stocks of different Industries using a Pair plot based on the Returns of each stock
  * Visualization of stocks using Line Graph based on Return of stocks
  * Visualizing distribution of stocks using Distribution plot based on Return from stocks
  * Visualizing correlation between stocks using Heatmap Subplots based on Return
  * Visualizing Trend Type of stocks using Candlestick
    * Uptrend
    * Downtrend
    * Sideways Trend
  * Visualizing data statistically based on the Returns of each stock
4. Profiling
  * Profile 1 -> Patrick
    * Creating a new dataframe and finding Correlation between stocks using Heatmap
    * Calculating cumulative return of the stocks selected for Patrick
    * Statistical understanding based on Cumulative Returns of each stock selected for Patrick
  * Profile 2 -> Peter
    * Creating a new dataframe and finding Correlation between stocks using Heatmap for Peter
    * Calculating cumulative return of the stocks selected for Peter
    * Statistical understanding based on Cumulative Returns of each stock selected for Peter
