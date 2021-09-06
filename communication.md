## Dataset
The dataset we used for our project is the housing price of Beijing from 2011 to 2017 [Kaggle: Housing Price in Beijing](https://www.kaggle.com/ruiqurm/lianjia).
Most data is traded in 2011-2017, some of them is traded in Jan,2018, and some is even earlier(2010,2009)

Within this dataset are a number of columns that capture house information in Beijing, such as the following:
- URL & ID: Identification columns
- Longitude & Latitude: Coordinates
- Cid: Community id
- TradeTime: The time of transaction
- DOM: Active days on market
- Followers: The number of people follow the transaction
- Total price: The total price
- Price: The average price by square
- Square: The area of the house
- Living Room, Drawing room, Kitchen, Bathroom: Number of rooms that houses contain
- Building Type: Including tower(1), bungalow(2), combination of plate and tower(3), plate(4)
- Construction time: The time of construction
- Renovation condition: Including other(1), rough(2), simplicity(3), hardcover(4)
- Building structure: Including unknow(1), mixed(2), brick and wood(3), brick and concrete(4),steel(5) and steel-concrete composite (6)
- Ladder ratio: The proportion between number of residents on the same floor and number of elevator of ladder. It describes how many ladders a resident have on average.
- Elevator: Have(1) or not have(0) elevator
- FiveYearsProperty: If the owner have the property for less than 5 years (related to China restricted purchase of houses policy).
- Subway: Have(1) or not have(0) subway nearby
- CommunityAverage: Community average price

Our team is also scraping the housing price of Shanghai from [Shanghai Lianjia](https://sh.lianjia.com/chengjiao/). The Shanghai dataset contains the same information as the Beijing dataset and is used to compare housing prices between Beijing and Shanghai and predict the future pricing trends for the two cities.

Since our Beijing dataset was preprocessed by the author and the dataset we scraped from the website was independent of the Beijing dataset, we do not need to integrate datasets together. The datasets have been imported into the PostgresSQL database for future use.