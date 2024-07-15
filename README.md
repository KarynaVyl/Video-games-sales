# Video-games-sales
Here I'm showing the most popular games sold in Japan and the EU.

A video game company wants to increase profits. They sell games in Japan and Europe.

The analytical question we need to answer is: Which video games were the most popular in terms of sales in Japan and Europe?

Requirements: The game has at least 100 thousand sales. Platforms: PS4, PSP, Wii, XB.

Example : https://public.tableau.com/app/profile/karyna.vylupko/viz/Video-games-sales/Dashboard1 

More details on my DataLab: https://www.datacamp.com/datalab/w/78c570f4-0f1c-4711-9da1-58557941a7d8/edit 

The dataset was analyzed for potential problems:
Checked for missing values.
Analysis of unique values ​​for object columns.
The data types in each column are displayed.
Additionally, analysis of numerical columns to detect anomalies.
Check for duplicates.
Convert the Year column to integers if necessary.
Results are here : https://www.datacamp.com/datalab/w/ea8a2540-15ea-49d6-9282-514ce9473d69/edit#a89615e6-1f02-49ca-bed8-fcede7832b67 

Column 'Rank':

Issues: No missing values.
Resolution methods: No additional action is required.
Column 'Name':

Issues: No missing values.
Resolution methods: No additional action is required.
Column 'Platform':

Issues: No missing values.
Resolution methods: No additional action is required.
Column 'Year':

Problems: Missing values.
Solution methods:
Fill in the missing values ​​with the median or mean value.
Use forecasting techniques to fill in missing values.
Remove rows with missing values ​​if there are few of them.
Column 'Genre':

Issues: No missing values.
Resolution methods: No additional action is required.
Column 'Publisher':

Problems: Missing values.
Solution methods:
Fill in the missing values ​​with the modal value (the most common value).
Use forecasting techniques to fill in missing values.
Remove rows with missing values ​​if there are few of them.
Columns 'NA_Sales', 'EU_Sales', 'JP_Sales', 'Other_Sales', 'Global_Sales':

Problems: There are no missing values, but there may be anomalous values.
Solution methods:
Check for abnormal values ​​(such as very high or very low values) and take action to resolve them.
Use methods for tracking and handling anomalies, such as scatter plot or box plot methods.
