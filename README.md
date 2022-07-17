<b>Sparkify Capstone Project:</b> Udacity Data Science Nanodegree Capstone Project

<b>Installation:</b> The modules used in the analysis are the following:
<br>• pyspark
<br>• numpy
<br>• pandas
<br>• matplotlib

<b>Project Motivation:</b> The aim of the analysis is to be able to understand and predict the behavior of a user when he/she decides to cancel his/her subscription. In order to gain insights form the data, exploratory data analysis, data processing and machine learning techniques will be implemented.

<b>Project Overview:</b> This project is the analysis of user logs for a music streaming service called “Sparkify”. The Sparkify music service company wants to identify the users that might churn in future. Once the reasons for attritions are better understood, our goal is to build a model and predict the users that will churn so that additional attention/perks can be given to these users and try to retain them on the platform.

<b>Problem Statement:</b> We have logs of all user actions performed in “Sparkify” application; our intent is to understand from this dataset which user behaviors can help us predict whether users will “churn”.

<b>Files Description:</b> The files leveraged/created as part of the project are the following:
<br>• mini_sparkify_event_data.json: The dataset used for the analysis.
<br>• Sparkify.ipynb: The jupyter notebook contains all the analysis.

<b>Licensing:</b> The dataset used for this analysis belongs to Udacity.

<b>Dataset Description:</b> The dataset used for analyzing the web log data from the music app Sparkify. This dataset contains 286500 user logs with 18 columns where user information (name, surname, gender, location), usage of the web (pages visited, songs played, artist details, number of session etc.) and user subscription plan (free or paid) have been collected.

<b>Data Exploration and Data Preprocessing:</b> We have 18 features in this data set such as Artist, FirstName, Gender, Page, Song, SessionId etc. In music application data set, some userIds are null, we remove these records.

<b>Data Visualization:</b> We are checking the count of churned and active users at gender level and we observed that churn rate in male is higher compared to female. We have also found out that most of the users are accessing pages like NextSong, Home, Thumbs Up, Add to Playlist etc.

<b>Feature Engineering:</b> We have shortlisted key features such as Gender, Level etc. Also, we have created additional features at user level which include "Songs Listened", "Total Sessions", "Average Session Time" etc.

<b>Modeling Results:</b> We ran multiple models and selected f1-score as an evaluation metric because this is a class imbalance problem and high accuracy can be achieved by simply predicting the dominated class all the time. Below we have captured f1 score for each model:
<br>Logistic regression (f1 score 0.81)
<br>Decision Tree Classifier (f1 score 0.84)
<br>Random Forest (f1 score 0.83)
we decided to move forward with Decision Tree Classifier model because it is performing slightly better than rest of the models in terms of f1 score.

<b>Conclusion:</b> This exercise will help us identify the users that might churn in near future and we can control the attrition rate by providing competitive benefits and perks to these users or by improving customer service, support etc.

<b>Further Improvements:</b> I believe that creating more advanced features from the dataset would help in improving these predictions. For example, we can create features not only at user level, but weekly or monthly level as well.

