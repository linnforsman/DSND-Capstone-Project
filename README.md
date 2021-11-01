# Sparkify
Capstone project, using Spark for Big Data. Predicting Customer Churn using PySpark

## Project Motivation
Customer churn is an important business problem, because it is a major source of revenue for many business models. Being able to predict customer churn is a critical step in the business process to prioritize retention program on customers who are likely to churn. 
In this project, we use Spark to predict customer churn using user activity dataset and build a machine learning model to identity users who are most likely to churn.

## Installation
- The code was developed using Anaconda distribution of Python, version 3. Libraries used include `PySpark`, `Pandas`, `Seaborn`, and `Matplotlib`.

## File Descriptions
- `Sparkify.ipynb`: exploratory data analysis, data preprocessing, and pilot development of machine learning model on local machine using data subset from [Udacity]().
- `mini_sparkify_event_data.json`: subset of user activity data.

## Results
The results are communicated and presented in this [blog post](https://linnforsman.medium.com/predicting-music-streaming-service-churn-with-pyspark-78825dfa491c).

Note that the scores are reasonable, but not perfect. The model is not perfect, but it is able to identify users who are most likely to churn. One limitation is that I was not able to run the model for the entire dataset due to my AWS tier.

## Licensing, Authors Acknowledgements
Thanks to [Udacity](https://www.udacity.com/) for providing the course material and giving a challenging project.