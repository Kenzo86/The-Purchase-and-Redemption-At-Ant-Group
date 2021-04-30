# The Purchase and Redemption At Ant Group
#### Introduction
Ant Group is an affiliate company of Chinese Alibaba Group. The group serves millions of users, with a large amount of capital inflows and outflows are involved in business scenarios every day. Faced with such a huge membership base, the pressure on capital management will be increased  continuously. Therefore, it is important to predict the inflow and outflow of funds while ensuring the minimum liquidity risk of funds and meeting daily business operations.
###### Definition before Starting the Project
1. Purchases refers to funds inflow
2. Redemptions refers to funds outflow.

#####  Research Direction
Analyzing the purchases and redemptions data from the Ant Group, and predicting the future captial flows based on historical data. 

##### Data
A data set file that consists of 4 parts:
1. User Profile Table: user_profile_table.csv
2. User Balance Table(The Purchases and Redemptions Table): user_balance_table.csv, it contains over 2.8 million rows of user balances.
3. Yields Rate Table: mfd_day_share_interest.csv
4. Bank Offered Rate Table: mdf_bank_shilbor.csv

Time Period: 2013.07.01 - 2014.08.31
Since the data size is huge, so I compressed the folder, if you want to use the dataset for testing, please uncompress the folder.
##### Exploratory Data Analysis
###### Part 1: User Purchases and Redemptions
1. The Daily Total Amount of Purchases and Redemptions
2. The Total Amount of Purchases and Redemptions from 2014-04 to 2014-09
3. The Total Amount of Purchases and Redemptions in Each Month from 2013-07 to 2014-09
4. The Weekly Total Amount of Purchases and Redemptions from 2014-04 to 2014-09
5. The Impact of Date on Total Purchases and Total Redemption
6. The Purchases and Redemptions during Holiday Periods.

###### Part 2: Bank Interest Rate and Share Interest Rate
1. Bank Interest Rate from 2013-07 to 2014-09 Compare with Total Purchases and Redemptions
2. Share Interest Rate from 2013-07 to 2014-09 Compare with Total Purchases and Redemptions

###### Part 3: Users' Profiles
1. Total Purchases and Redemptions by Gender
2. Total Purchases and Redemptions by Cities
3. Total Purchases and Redemptions by Constellations

##### Prediction
In this project, I want to find out: the daily total purchases and redemption on 2014-09.

1. Date Range: 2014.04 - 2014.08
Since the data from 2014-04 to 2014-09 is more stable, and shows more regular changes (Observed and written in EDA).

2. Method: Weighted Moving Average (https://www.real-statistics.com/time-series-analysis/basic-time-series-forecasting/weighted-moving-average/)



