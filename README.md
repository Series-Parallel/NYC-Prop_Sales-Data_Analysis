# NYC-Prop_Sales-Data_Analysis
This is my first data analysis project. I did this project so that I can get better at machine learning proejcts. In this project I applied data gathering, data cleaning and data anaylsis. 
Doing this projetc helped me how to clean the data and perform data analyisis on it.

# Objectives of this Data Analysis.

1. Understand Sale Price Distribution:
   - Explore the distribution of property sale prices across NYC.
   - Identify outliers and unusual sale prices.
2. Analyze Borough-Level Trends:
   - Compare the average and median sale prices across boroughs (Manhattan, Bronx, Brooklyn, Queens, Staten Island).
   - Determine which borough has the highest and lowest transaction volume.
3. Examine Building Classes:
   - Identify the most common building types sold.
   - Analyze the relationship between building class and sale prices.
4. Study Seasonal Trends:
   - Examine how property sales vary by month or season.
   - Analyze if there are any significant yearly trends in sales.
5. Identify High-Value Areas:
   - Investigate blocks or lots with the highest total sales value.
   - Highlight neighborhoods or regions with frequent high-value transactions.


# Conclusion ( formed based on the objective's result and what is done in the analysis) :

1. Dataset Overview and Cleaning:
   + The initial dataset contained 84,548 entries across 22 columns. After cleaning, including handling missing values and removing extreme outliers, the dataset was reduced to 18,968 entries, ensuring high-quality data for analysis.
   + Non-numeric values in critical columns (SALE PRICE, GROSS SQUARE FEET, LAND SQUARE FEET) were converted, and rows with invalid or zero values were removed.

2. Sale Price Distribution:
   + The sale prices in NYC properties varied significantly, with a large number of properties sold at lower price ranges.
   + Outliers were prevalent, leading to additional filtering (e.g., removing sales under $100,000 or over $1 million), revealing a more interpretable price range for most properties.

3. Borough-Level Analysis:
   + Properties were segmented by borough, showing that Manhattan properties had significantly higher sale prices compared to other boroughs, reflecting its premium real estate market.
   + Bronx and Staten Island were the most affordable, with lower average sale prices and smaller property sizes.

4. Property Size Analysis:
   + Larger properties (measured in GROSS SQUARE FEET and LAND SQUARE FEET) correlated with higher sale prices, as expected.
   + After binning property sizes into "Low," "Medium," "High," and "Very High" categories, the analysis highlighted that larger properties were concentrated in suburban boroughs like Staten Island.

5. Seasonal Trends:
   + By analyzing the sales across months and years, the data suggested seasonality in the NYC real estate market, with certain months experiencing higher sales volumes.
  
6. Building Class Trends:
   + The most common property types belonged to residential units, with smaller, walk-up rental apartments dominating the dataset.
   + Commercial properties and mixed-use buildings showed significantly higher prices but fewer transactions overall.
