FILES IN REPO / DESCRIPTION:

Amsterdam Airbnb Analysis.ipynb
/Python Jupyter notebook
listings.csv
/Airbnb listings data from Amsterdam

*********************
DESCRIPTION:
This README concerns the Python code and data found in the jovanglig/amsterdam_airbnb repo. 
This is an analysis of Airbnb data from Amsterdam which can be found on Inside Airbnb's website: http://insideairbnb.com/get-the-data.html.
The questions I want to answer using the data are as follows:

"How many hosts are running a business with multiple listings and where are they located in Amsterdam?"

"What are the top 10 Airbnb hosts based on the number of listings they have and how much do they constitute as a percent of the Amsterdam Airbnb market?

"Can I develop an accurate regression model that would predict the price of an Airbnb listing in Amsterdam using available attributes? Which attributes are good predictors for price?"

The first two questions are answered using Tableau. This code concerns itself with the data cleaning and the latter question, which is about devising a linear regression model to predict price. 
The code has the following general outline:

Loading of data
Statistics/Overview of data
Cleaning of data and prepping for modelling
Missing values imputation
Feature selection
Linear regression model configuration
Prediction
Performance measuring

*********************
MOTIVATION:
Being an Airbnb host myself who rents out several properties in Rotterdam, the second largest city in the Netherlands, I am fascinated by the amount of Airbnbs that have sprung up in Amsterdam and the urban parts of the country. Given the thighter regulations in Amsterdam concerning specifically home rental and gradually increasing tourist and rental income taxes, it is interesting to figure out which people are running multiple listings on Airbnb and as such have created a business out of it and where these listings are located on a map. This listing data, since it is real data, also lends itself well to devise a regression model which can accurately predict the price of stay, which I am very fascinated by.

I made a blogpost on the Medium platform about this analysis which you can find here:  https://medium.com/@jovangligorevi/finding-out-who-the-biggest-airbnb-home-owners-are-in-amsterdam-47bfdf8294f7

*********************
RESULTS:

The best model has an an achieved rsquared of 0.17. The model that applied a correlation threshold of 0.1 has an rqsuared of 0.17162653615978452. The k = 4 model achieved an rsquared of 0.09614673183724698 and the model with all features has an rsquared of -8.798159935611163e+23 on the test set.

*********************
LIBRARIES USED:
Pandas
Numpy
Scikit Learn (sklearn)
Seaborn
re
matplotlib

*********************
ACKNOWLEDGEMENTS
The code is part of an assignment for Udacity's Data Scientist Nanodegree, as such it is structured upon requirements given. 
This code uses data from Inside Airbnb's website: http://insideairbnb.com/get-the-data.html.
