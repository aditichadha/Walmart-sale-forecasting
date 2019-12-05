# Walmart-sale-forecasting

The objective is predicting store sales using historical markdown data.
One challenge of modelling retail data is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line.


We were provided with historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and you are tasked with predicting the department-wide sales for each store.
In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modelling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.

For convenience, the four holidays fall within the following weeks in the dataset (not all holidays are in the data):
-Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
-Labor Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
-Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
-Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13
