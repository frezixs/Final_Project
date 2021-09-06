# Final_Project

## Team 
Chunhe Zhang 
Xinghui Li 
Shulin Gu (Tony)
Rong Yong (Sarah)

## Presentation
### Selected topic 
Analyze Housing price of Beijing and Shanghai 

### Reason why they selected their topic
All of our team members are Chinese and about 25 years old, so we all facing the challenge to buy house. 
So we are curious about housing price in China's most developed cities Beijing and Shanghai. 

### Description of their source of data 
These Housing price of Beijing from 2011 to 2017.
It includes URL, ID, Lng, Lat, CommunityID, TradeTime, DOM(days on market), Followers, Total price, Price, Square, Living Room, number of Drawing room, Kitchen and Bathroom, Building Type, Construction time. renovation condition, building structure, Ladder ratio( which is the proportion between number of residents on the same floor and number of elevator of ladder. It describes how many ladders a resident have on average), elevator, Property rights for five years（It's related to China restricted purchase of houses policy), Subway, District, Community average price.
Most data is traded in 2011-2017, some of them is traded in Jan,2018, and some is even earlier(2010,2009)
All the data was fetching from https://bj.lianjia.com/chengjiao.
We also fetch some data of shanghai housing price from http://sh.lianjia.com/chengjiao.

### Questions they hope to answer with the data
1. Analyze what factor will influence the housing price most significantly. 
2. Predict housing price for next year. 

## Github 
All the requirement is satisfied for the first segment. 
- ✓ Includes a README.md
- ✓ Description of the communication protocols
- ✓ At least one branch for each team member 
- ✓ Each team member has at least four commits from the duration of the first segment 

## Model 
- Linear Regression model is chosen to predict the housing price. It is recommanded to use linear regression to perform the prediction when the predicted output is continuous
- Using the Provisional Machine Learning Model, we reach an accuracy of 0.5786. This can be improved by adding more features of housing information.

## Database 
- Since our Beijing dataset was preprocessed by the author and the dataset we scraped from the website was independent of the Beijing dataset, we do not need to integrate datasets together. 
- The datasets have been imported into the PostgresSQL database for future use.
































