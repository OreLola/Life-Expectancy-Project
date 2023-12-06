# Decades Unveiled: Exploring Trends in Fertility and Life Expectancy in Ecuador

The objective of this project is to examine the patterns of fertility and life expectancy rates in Ecuador from 1960 to 2013. The analysis will entail utilizing Python to dissect the dataset and leveraging Power BI to visualize our discoveries. The identified trends offer valuable insights into various aspects, including population dynamics, potential economic and health impacts, explanations for the aging population, high immigration rates, and other noteworthy observations. The visualizations serve as a quick and informative way to observe changes over the specified years.

# Data
There is a folder containing the our data sources. It includes three excel sheets: Country_Metadata, Fertility_Rate and LifeExpectancy_At_Birth.

# Tools
The project used python on visual studio code, Microsoft Excel, Power Query and Power BI.

# Steps followed
## Data Extraction and Transformation (the codes can be found in the code folder)
To process the raw data, the following steps were undertaken within Visual Studio Code:

- I uploaded the data to GitHub using the "update file" feature.
- I linked Visual Studio Code by creating a branch under the code menu.
- I utilized Pandas, NumPy, and openpyxl to import the data into Excel workbooks.
- I set the maximum column and devised a function for each Excel sheet to create dataframes.
- I employed islice from itertools to perform various transformations on the dataframes.
- I executed tasks such as creating headers, resetting indexes, altering column names, melting columns, changing data types from text to integers, merging, creating new columns, calculating averages, and ultimately saving the transformed dataframes in Excel format for download into the local drive.
The resultant data frames are named df_region, df_country.

# Loading Data into PowerBI

- In imported the previously created dataframes into PowerBI.
-I utilized Power Query for basic edits, including decimal reduction and removal of the index column.
In PowerBI:
- I applied a line graph to illustrate the trend of fertility and life expectancy over the years.
- I employed a scorecard to display the average values of life expectancy and fertility throughout the specified period.
- I generated visuals comparing the average fertility rate and life expectancy in Ecuador to those in Latin America.

# Outcome
When comparing Ecuador to the Latin America & Caribbeans, Ecuador has a high fertility rate of about 4.4% compared to Latin America’s about 3.7%. Over the decade, Ecuador’s life expectancy has steadily risen from about 55 years of age to about 75years. The relationship between fertility and expectation shows that there is no linear relationship between both. 
