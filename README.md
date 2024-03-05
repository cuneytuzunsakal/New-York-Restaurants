The aim of this project is to develop a dashboard that empowers restaurant owners and chain management to strategically identify optimal locations for opening new branches. 
This dashboard will leverage a combination of data-driven criteria, 
including minimizing rent costs and crime rates, maximizing population density, optimizing competition levels, and aligning with target demographics. 
By providing precise location recommendations based on these factors, the project aims to enhance the decision-making process 
and increase the chances of success for new restaurant or cafe branches, ultimately contributing to the growth and profitability of the business. 

The dataset encompasses a comprehensive collection of information, primarily sourced from Zip-Code.com (https://www.zip-codes.com) website. This dataset features a diverse array of data, meticulously compiled through for use. It was diligently cleaned and made available for use on Zip-Code.com.

Formatted later on as a CSV file, the primary file in our dataset is named “dataset.csv”. This dataset is structured into 30 distinct columns, encompassing a variety of data types ranging from numerical values to textual information. Key columns include identifiers such as “'zip'”, “'population'”, “crime_rate”, “median_rent”, and several others. With a total of 101 rows, each row in the dataset represents an individual zip code location and its features. I got 22,146 different restaurants and grouped them to their zip codes as well as their attributes. So the main set is the summarization and analysis of 7 different data sets.

-- Data Cleaning

Data consistency problems were present in the demographic  dataset. Precision of crime rate information was reduced to 2 decimals to eliminate unnecessarily detailed information.
Numerical values were separated in thousands by commas, which could lead to inaccuracies in calculations in Power BI, so i removed the commas from those values.
From the clean dataset, a pivot table was created with cross-tabulation in order to enable data analysis. Restaurant counts were grouped by zip code with separate columns for each cuisine category. Total chain restaurant count was also added as a separate column to this data. Also i created a new column in the Power BI table to convert the boolean values in the "is_chain" column, where 1 is represented as "Yes" and 0 as "No."





