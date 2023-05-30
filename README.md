# Walmart_Sales_Prediction
Walmart Sales Prediction using Data Analytics and Machine learning

Walmart is a renowned retail corporation that operates a chain of hypermarkets. Here, Walmart has provided a data combining of 45 stores including store information and monthly sales. The data is provided on weekly basis. Walmart tries to find the impact of holidays on the sales of store. For which it has included four holidays weeks into the dataset which are Christmas, Thanksgiving, Super bowl, Labor day. Here we are owing to Analyze the dataset given. before doing that , let me point out the objective of this analysis. Our Main Objective is to predict sales of store in a week.
## Why this problem needs To be Solved?
Holidays can create a huge impact on sales. So, if there is a good prediction on Sales then Walmart can calculate how much product to order during Holiday time. It will help in predicting which products needs to be purchased during the holiday time. As customers planning to buy something expects the products to be available immediately. And through prediction they can figure out which product will require at what time . Thus soar the trust of Customer on Walmart. This problem can also solve the issue of Marketing Campaigns. As Forecasting is often used to adjust ads and marketing campaigns and can influence the number of sales. Walmart runs several markdown events throughout the year. And these markdown event precede to the prominent holidays. So to solve the issue Walmart can organize such events more efficiently.
## Dataset Information. 
### Stores.csv:
It has three columns.
Store: stores numbered from 1 to 45 Size : stores size has provided
type : store type has been provided ,there are 3 types — A,B and C .
### Train.csv
It has five columns. Store: the store number 
Dept: the department number Date : the week
Weekly_Sales: sales for the given department in the given store IsHoliday: whether the week is a special holiday week
### Test.csv: 
It is same as train.csv except it does not have ‘IsHoliday’ Column.
### Features.csv
It has eleven columns. Store: the store number Date: the week
Temperature: average temperature in the region. Fuel_Price: cost of fuel in the region
MarkDown1–5: anonymized data related to promotional markdowns that Walmart is running. Markdown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA. Selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.
CPI — the consumer price index Unemployment : the unemployment rate.
IsHoliday: whether the week is a special holiday week


