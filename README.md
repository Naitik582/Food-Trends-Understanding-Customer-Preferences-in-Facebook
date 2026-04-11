# Food-Trends-Understanding-Customer-Preferences-in-Facebook
I worked in a team limit of seven members with a Team Leader who contributes and Gives Direction, Each member have different tasks,

like Collecting Data from Facebook Page Restaurant customer comments to identify there feedback improve in that, like Taste, Package Quality, Price etc..,



We collect 1 Data- Unstructured Data - (Facebook) In this we identify large dataset nearly 1 lakh, comments, likes, shares, customer name, product name (Social). 

We collect 2 Data- Structured Data - In this we have Customer Details and Product details and their feedback in Rating Format (Survey).



Before Importing these dataset I used Python Libraries to identify sentiment scores and labels through (Vader) in Unstructured Data  and finally created Unique Customer Id and Unique Product Id in Unstructured Data.



Then we complete our modules:-

1. Introduction

2. Sentiment Analysis

3. Product Insights

4. Customer Segmentation

5. Strategy & Innovation Dashboard

6. Conclusion



After Import Datasets in Power Bi I do Transform Data to remove duplicates, errors, null values, replace values, and add some custom, conditional columns for our dashboards.



Then From Structured Data I Add Customer Table, Product Table & Date Table,

Then From Unstructured Data I Add Feedback Table,

Then From Both Data I add Source Table.



After doing all process in Power Query Close & Apply.

Then Going in Model View for Relationships to Connect Our Datasets, the main crucial part of our project,



Unstructured Data & Structured Data = Fact Table

Feedback Table, Customer Table, Product Table, Date Table & Source Table = Dimensions Table



In Model View I used One to many*, 

Customer Table, Product Table, Date Table to FEEDBACK TABLE.

Rule Simple we can not connect to Fact Table Directly.



All Things Finish Going To DAX & ADD Column:-

I used AVERAGE, SUM, TOTAL, SWITCH, MAXIMUM, MINIMUM, DIVIDE, VAR, COUNTROWS, TOP N, FILTER, ROUND.



Then Completing Our Dashboards for See Customer Trends for which Product Items with Brand with customer city & state and Rating if Low we can Improve it.



I used Premium Charts Like Word Cloud, Box & Whisker, Rader Chart, Advanced Line Chart & Bubble/Scatter Chart for Our Dashboards.
