# FLIGHT DELAY PREDICTION USING SUPERVISED MACHINE MEARNING

![Untitled-design](https://github.com/dapzwalt/FLIGHT-DELAY-PREDICTION-USING-SUPERVISED-MACHINE-LEARNING/assets/125368548/44bb392a-a013-4921-aecf-b0914da3d6ee)


## Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Model](#machine-learning-model)
- [Evaluation Metrics](#evaluation-metrics)
- [Model Optimization](#model-optimization)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)

## Project Overview
The project encompasses the analysis of historical flight data, weather conditions, and other relevant factors to build a robust prediction model. The system will offer real-time predictions, empowering airlines and passengers to make
informed decisions and take proactive measures to mitigate the impact of potential delays.

## Project Objective
The aim of this project is to Build advanced machine learning models that analyze historical flight data and relevant factors (e.g., weather conditions, air traffic) to predict flight delays with a high level of accuracy and to
assist airlines in optimizing their operations by providing early insights into potential delays. This includes optimizing crew schedules, resource allocation, and maintenance planning to minimize disruptions.

## Data Sources
The dataset used in this project was provided by the company. The dataset contains a collection of features extracted from the company database which includes features as 
gender, arrival delay, departure delay, flight per airline, online service, schedule departure, air_time and other relevant information

## Exploratory Data Analysis
I performed data wrangling, conducted univariate and bivariate analysis, showing correlations between variables and drawing out inferences. checked for missing values and duplicates in my dataset. Most importantly, feature engineering was performed to extract relevant information from my raw data

## Data Preprocessing
I performed exploratory data analysis, encoding of categorical variables, normalization of my data which entails scaling the features before feeding the data into the machine learning model.

## Machine Learning Model
The flight delay prediction model is built using a supervised machine learning approach. Training and testing of my data was done by splitting my data to the ratio 70:30 respectively. Several classification algorithms were employed which includes:

- **Logistic Regression**
- **Naive Bayes**

## Evaluation Metrics
The following evaluaton metrics were used to assess the performance of the individual machine learning algorithms, which are: 

- **Recall:** A high recall meant it was good at identifying instances of delay while minimizing false negatives.
- **F1score:** This is the harmonic mean of precision and recall, thus providing a balanced metric for model evaluation
- **Accuracy:** Accuracy shows how good the model performed but is not a final resort to determining or choosing the best model
  
## Model Optimization
After extensive experimentation and hyperparameter tuning, the model with the highest score in terms of its classification report was chosen based on its performance and generalized capabilities.

## Key insights
- The purpose of this project is to predict predict flight delay with a high level of accuracy by analysing historical flight data and other factors
- After subjecting the models to evaluation metrics like the accuracy, recall, precision and f1score, the best performing model was chosen which is the Naive Bayes because we had lesser error with this model 

## Conclusion
Considering the business objective, an ideal model should prioritize predicting low false negatives and high true positives. This is crucial as a high number of false negatives will hinder airport operational efficiencies.

Despite the Naïve Bayes model having a higher count of false positive predictions compared to logistic regression, the associated cost in this context is deemed lower than the potential cost of handling false negatives by the airport authorities. Consequently, the Naive Bayes model is selected as the optimal choice.

