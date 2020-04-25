# Predicting Churn for Sparkify

## Introduction
    Sparkify is a popular digital music service similar to Spotify of Pandora.Menus of users stream their favorite songs to this service every day either using the free-tier that place advertisements between the songs or using the premium subscription model, where they stream music as free but pay a monthly flat rate.Users can upgrade,downgrade,or cancel their service at any time.So, it's crucial to make sure users love the service.
    Every time a user interacts with the service while they're playing songs, logging out,like in a song with a thumbs up,hearing an ad, or downgrading their service, it generates data,All this data contains the key insights for keeping users happy and help business thrive.
    It's the job for data team to predict which users are at risk to churn either downgrading from premium to free-tier or cancelling their service altogether.If can accurately identify these users before they leave, business can offer them discounts and incentives,potentially saving business millions in revenue.

## Metrics
  There are two metrics areaUnderROC and areaUnderPR for pyspark BinaryClassificationEvaluator. Churn customer is minority. areaUnderROC is not good choice for imbalanced classification.So, we choose areaUnderPR to measure performance of the models.  

## What will It including?
   Showing how to manipulate large and realistic datasets with Spark to engineer relevant features for predicting churn and  how to use Spark MLlib to build machine learning models with large datasets, far beyond what could be done with non-distributed technologies like scikit-learn.

## Career Relevance

   - Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. 
   - Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data.

## Essential Skills

   - Load large datasets into Spark and manipulate them using Spark SQL and Spark Dataframes.
   - Use the machine learning APIs within Spark ML to build and tune models.
   - Integrate the skills Spark and the Data Scientist. 
   
## Conclusion
    Feature Engineering is most time killing and most creative part.Exploratory a useful feature is difficult.
    
## Improvement
    Exploratorying more Features, the implementation mybe being improved.
    
## Blog Link
https://medium.com/@yycncom/predicting-churn-for-sparkify-6c795e65ce78

## Installation

Python3+,numpy,sklearn,pandas.Anaconda is proposed.There is no other installation requirment.
