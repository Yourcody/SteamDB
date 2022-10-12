# Steam DB

## Group members

|Name | email | github_username|
--- | --- | ---|
|Qihang Dai| ahgdyycc@seas.upenn.edu |qihang-dai|
|JingXuan Bao| bjx@seas.upenn.edu | Jingxuan-Bao |
|Peihan Li| peihanli@seas.upenn.edu |Yourcody|
|JingRu Wang| | JrWang0930 |

## Application Description

We are going to build a Steam Store application, which is a video game digital distribution platform. The database will include the information of games, users, and developers. We will also provide some basic functions for users to search for games and developers, and if time permits, we will also implement some advanced functions such as recommendation system and game review system.

We plan to hold the databse on AWS RDS and running the web application on AWS EC2. The web application is planned to be built with Flask and React. The database will be built with MySQL. And we wish the application would support as many as functions like that in the Steam Store.

## Dataset Description

The dataset we are going to use is from [Kaggle](https://www.kaggle.com/nikdavis/steam-store-games). It contains 27075 games and 18 features. The features include game name, developer, publisher, release date, price, tags, and so on. The dataset is updated on 2019-06-12 and it is a clean dataset, which saves us a lot of time on data cleaning (doesn't mean we don't need to do more EDA). The overall dataset is 252.04MB. Its a big enough dataset for us to build a database and a web application. For exapmle, We would use steam.csv as our main dataset, which has 27075 rows and 18 columns. We would also use steam_description_data.csv as our secondary dataset, which has 27075 rows and 2 columns. We would use the game name as the primary key to join the two datasets. The overall order of the dataset shall meet the requiredment of meaningful optimization cause the datasets has 6 csv files in total that we may optionally use.

## Five Sudo SQL Query (aggregate, subquery, join, nested aggregation, nested subquery, etc.)



