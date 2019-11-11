# Sparkify Churn Reduction project

## Installation
This project was built in Python 3.6. A number of additional libraries were also used - these libraries and their version numbers are listed below. 

- numpy: 1.16.2
- pandas: 0.24.2
- matplotlib: 3.0.3
- seaborn: 0.9.0
- pyspark: 2.4.4


## Project overview and motivation

This project covers an exploration of data on churn, and the construction of a predictive model to better anticipate churn ahead of time. 

The project draws on a fictional but representative dataset from 'Sparkify', a streaming service comparable to companies such as Spotify or Pandora. The data comprises user logs that provide insight on how users, including data on whether they have churned or not and data on a wide variety of on-ste activities. 


## Results

We found we're able to reach an F1-Score of c.76% using our tuned random forest model. We achieved this with a random forest model, tuned to select preferable hyperparameters. Among our individual features, songs played and thumbs down proved the strongest predidctors of churn. 


## File descriptions
- \
	- README.md
	- mini_sparkify_event_data.json [0]
	- Sparkify - Churn Reduction.ipynb
	- Sparkify - Churn Reduction.html

[0] Not included on Github repository as file size is too large.
