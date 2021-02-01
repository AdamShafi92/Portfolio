### Data Science Projects

### [Data Science Salary Predictor](https://github.com/AdamShafi92/ds-salary-predictor)
* Webapp here: https://data-salary-predictor.herokuapp.com/ created using Streamlit and SHAP.
* Scraped data from Indeed.co.uk for 7000+ data related jobs
* Scraped individual company information and full job descriptions. Cleaned using Pandas. Text data cleaned and vectorised
* EDA write ups: https://adam-shafi.medium.com/soft-skills-1999f0f85e70, https://adam-shafi.medium.com/tech-skills-2021-5805848851c6 
* Trained and optimised an XGBoost model to achieve £8.8k MAE.
* Used SHAP to create a highly interpetable framework for making predictions.
* Deployed in a Webapp, created a container version using Docker and Flask that could be deployed on AWS.


### [UFO Sightings Dashboard](https://public.tableau.com/profile/adam.shafi6605#!/vizhome/UFOSightingsDashboard_16041450574280/Dashboard1)
* Dashboard using .csv UFO dataset.
* Uses appropariate visualisations and a simple visual style.
* Makes use of Tableaus groups, parameters and filters.


### [Twitter Sentiment Analysis on Tweets Containing #stocks](https://github.com/AdamShafi92/Twitter-Sentiment-Analysis)
* Retrieved data using the Twitter API and labelled tweets 1000 manually.
* Extensive cleaning to remove emojis, retweets, extract stock tickers and ensure data was suitable for modelling.
* Performed lemmatisation to group together inflected words.
* Transformed the data into the correct format for NLTK (Natural Language Toolkit).
* Optimised mutliple skLearn models including Logistic Regression, Random Forest Classification to reach the best model.
* This could be used as one indicator in a larger dataset aimed at predicting stock prices, or looking at the influence of Twitter on stock prices.

![](./images/SPY_sentiment_2.PNG)

### [Image Classification of Herbs](https://github.com/AdamShafi92/Herb-Classification)
* The aim of this was to produce a quick image classification tool using the fastai toolkit.
* Downloaded 2000 images of herbs using the bing API.
* Used fastai to preprocess images .
* Trained a Resnet classifier and removed incorrectly labelled images.
* Deployed using Voila and Binder.
* https://bndr.it/rykge




