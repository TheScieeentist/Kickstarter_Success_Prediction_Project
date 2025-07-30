# Kickstarter Projects – Machine Learning Project

This 4 days project was was in colaboration with Naomi Pletner & Dr. Susan Gritzka during the Data Science Bootcamp at **neue fische** and is intended **solely for educational and portfolio purposes**. It demonstrates the end-to-end process of working with a real-world dataset, from data exploration to model evaluation. 

The aim of this project was to archieve a ML-model predicting the success likelyhood of Kickstarter campaigns.
We focused on creating a model, that was independent of Pledge and Backers but trained to identify the success rate by the Category, Subcategory, their Goal and the Country from where the campaign started. 
Using feature engineereing, we involved the launch month, the launch day (in the week), Project Duration, (Campaign-)Name length and performed a sentiment analysis of the (Campaign-)Name.

Data-source: https://www.kaggle.com/datasets/ulrikthygepedersen/kickstarter-projects/data.  

## Project Overview

- **Dataset**: [Kickstarter Projects – Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/kickstarter-projects/data)
- **Goal**: Predict whether a Kickstarter campaign will succeed or fail based on campaign features.
- **Key steps**:
  * Exploratory Data Analysis (EDA)
  * Data cleaning and feature engineering
  * Binary classification model training and evaluation

## Machine Learning Models Used

Several models were applied and compared to find the best-performing approach:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* XGBoost (best performace)
* Voting Classifier (Ensemble)
* Stacking Classifier

## Insights

* Campaign duration and launch category were among the most relevant predictors.
* XGBoost showed strong performance in terms of accuracy and robustness across validation folds.
* Various ensemble techniques were explored to improve predictive performance.

## Disclaimer

This project is **not intended for commercial or production use**.  
All results are exploratory and for demonstration purposes only.

This project and repo was created for and during the Data Science Bootcamp at [neue fische](https://www.neuefische.de/bootcamp/data-science-und-ai).
