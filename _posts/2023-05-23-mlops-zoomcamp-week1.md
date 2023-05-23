---
layout: post
title: "Predicting NYC Taxi Ride Durations: Week 1 MLOps zoomcamp"
date: "2023-05-23 22:29"
category: 
author: Vladislav Skripniuk
tags:
  - mlopszoomcamp
summary: 
---

Introduction:
Welcome to my blog post, where I will take you through my experience completing a homework assignment for an ML Ops course. The objective of the assignment was to develop a machine learning model using Python, Jupyter, Pandas, and scikit-learn to predict the duration of NYC taxi rides. I will provide a brief overview of the steps involved in the process and share my insights along the way. If you're interested in exploring the source code of my solution, you can find it [here](https://github.com/VladSkripniuk/mlops-zoomcamp/).

In this assignment, I embarked on a data-driven journey to predict the duration of NYC taxi rides. It all started with collecting the NYC Yellow Taxi Trip Records dataset for January and February 2022, which served as the foundation for our analysis. Computing the trip durations allowed me to gain valuable insights into the variability of the dataset, measured by the standard deviation. Next, I focused on handling outliers, removing records where the duration fell outside the range of 1 to 60 minutes (inclusive), ensuring the quality and accuracy of our model.

Feature engineering played a crucial role in transforming categorical variables into a numerical format that the machine learning algorithm could understand. By applying one-hot encoding to the pickup and dropoff location IDs, I created binary features. This step enabled me to represent geographical information effectively. The resulting feature matrix had a specific dimensionality that shaped the input for our model.

Moving on to model training, I opted for a plain linear regression model with default parameters, leveraging scikit-learn's powerful tools. I used the feature matrix obtained from the previous step to train the model, and to evaluate its performance, I calculated the Root Mean Squared Error (RMSE) on the training data. This metric provided valuable insights into how well the model captured the variations in the dataset.

Finally, I applied the trained model to the validation dataset from February 2022. By computing the RMSE on this unseen data, I obtained an unbiased measure of the model's performance. This step allowed me to assess the generalization capability of the model and understand its potential for real-world scenarios.

Conclusion:
In this blog post, I shared my journey of completing an ML Ops homework assignment focused on predicting the duration of NYC taxi rides. Through data collection, computing trip durations, handling outliers, feature engineering, model training, and model validation, I delved into the world of ML Ops and leveraged Python, Jupyter, Pandas, and scikit-learn to accomplish the tasks at hand. If you're interested in exploring the source code of my solution, feel free to check it out [here](https://github.com/VladSkripniuk/mlops-zoomcamp/). This assignment not only provided me with practical experience but also deepened my understanding of ML Ops principles. I look forward to further exploring the exciting field of ML Ops in my journey ahead.