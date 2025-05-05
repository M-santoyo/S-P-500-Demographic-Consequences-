# We will be working with two datasets: 
# 1. spy.csv – This CSV file contains historical data for the S&P 500 (SPY), including the following details for each trading day:
        Open Date and Close Date

        Opening Price and Closing Price

        Highest Price and Lowest Price of the day

        Trading Volume (i.e., the number of shares traded that day)


# 2. webscrapinglink – This file contains a link to a web page from the U.S. Bureau of Labor Statistics, specifically displaying a Civilian Unemployment Rate graph.
        The website includes data on:

        Unemployment rates across various racial and ethnic groups

        Overall unemployment trends

        A historical perspective, covering approximately the last 30 years

        The primary focus was scraping the graph data from this site for further analysis.



# More information:

# Web Scraping (Selenium):
Website Access: Used Selenium WebDriver to open and navigate to the Bureau of Labor Statistics website.​

Table Extraction: Clicked "Show table" to reveal data and extracted unemployment rates for various demographics (Total, Men, Women, Teen, White, Black, Asian, Hispanic)

# Data Structuring

Data Storage: Extracted data stored in lists for each demographic group.​

Data Frame Creation: Combined lists into a pandas DataFrame with columns:​

		-Month-Year, Total Rate, Male Rate, Female Rate, Teen Rate, White Rate, Black Rate, Asian Rate, Hispanic Rate.

# Data Transformation
Date Conversion: Converted Month column to datetime format for time-based analysis.​

Numeric Conversion: Converted unemployment rate columns to numeric values using pd.to_numeric(), handling errors with coerce to convert invalid data to NaN.

# Data Inspection

S&P 500 Data Import: Loaded S&P 500 data (spy.csv) into a pandas DataFrame.​

Data Preview: Verified the first 10 rows of both data sets to ensure correct loading and format.