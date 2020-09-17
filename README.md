## FILES IN REPO / DESCRIPTION

- Amsterdam Airbnb Analysis.ipynb (Python Jupyter notebook)
- listings.csv (Airbnb listings data from Amsterdam)

*********************
## DESCRIPTION
This README concerns the Python code and data found in the jovanglig/amsterdam_airbnb repo. 
This is an analysis of Airbnb data from Amsterdam which can be found on Inside Airbnb's website: http://insideairbnb.com/get-the-data.html.


*********************
## MOTIVATION
Being an Airbnb host myself who rents out several properties in Rotterdam, the second largest city in the Netherlands, I am fascinated by the amount of Airbnbs that have sprung up in Amsterdam and the urban parts of the country. Given the thighter regulations in Amsterdam concerning specifically home rental and gradually increasing tourist and rental income taxes, it is interesting to figure out which people are running multiple listings on Airbnb and as such have created a business out of it and where these listings are located on a map. This listing data, since it is real data, also lends itself well to devise a regression model which can accurately predict the price of stay, which I am very fascinated by.

The questions I want to answer using the data are as follows:

***"How many hosts are running a business with multiple listings and where are they located in Amsterdam?"***

***"What are the top 10 Airbnb hosts based on the number of listings they have and how much do they constitute as a percent of the Amsterdam Airbnb market?***

***"Can I develop an accurate regression model that would predict the price of an Airbnb listing in Amsterdam using available attributes? Which attributes are good predictors for price?"***

*********************
## RESULTS

***"How many hosts are running a business with multiple listings and where are they located in Amsterdam?"***

There are **2161 hosts** who rent out multiple listings on Airbnb in Amsterdam. They make up around **13.17 %** of the market, which means that actually slightly more than **one in ten Airbnb hosts** in Amsterdam have multiple listings and are probably running a home rental business.

***"What are the top 10 Airbnb hosts based on the number of listings they have and how much do they constitute as a percent of the Amsterdam Airbnb market?***

The top 10 of hosts by listings own **351 homes** together and make up around **1.85%** of the Airbnb homes in Amsterdam.

***"Can I develop an accurate regression model that would predict the price of an Airbnb listing in Amsterdam using available attributes? Which attributes are good predictors for price?"***

Overall, my price prediction models proved not that successful in predicting the price of a stay in Amsterdam. My best model is **model 1** which uses a correlation threshold. This model has an r-square of **0.17**. 

The features that are of the biggest importance to the price of a stay in Amsterdam are:
- Room in an aparthotel
- Hotel room
- located in the neighbourhood of ‘Centrum-West’
- The number of guests
- Private room in an appartment


I made a blogpost on the Medium platform about this analysis which you can find here:  https://medium.com/@jovangligorevi/finding-out-who-the-biggest-airbnb-home-owners-are-in-amsterdam-47bfdf8294f7

*********************
## LIBRARIES USED
- Pandas
- Numpy
- Scikit Learn (sklearn)
- Seaborn
- re
- matplotlib

*********************
## ACKNOWLEDGEMENTS
The code is part of an assignment for Udacity's Data Scientist Nanodegree, as such it is structured upon requirements given. 
This code uses data from Inside Airbnb's website: http://insideairbnb.com/get-the-data.html.
