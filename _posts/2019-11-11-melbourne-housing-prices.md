---
layout: post
title:  "Melbourne Housing Prices"
date:   2019-11-11
excerpt: "Predicting property value in Melbourne, Australia"
project: true
tag:
- data science 
- projects
comments: false 
---

## Summary
This project aims to predict the value of property in Melbourne, Australia using spatial features and physical features.

Data for properties sold and physical features will be scraped from [Domain](https://www.domain.com.au/sold-listings/melbourne-vic-3000).

Data will be cleaned manually as well as generating new features.

Additional features may be generated from external data.

Various machine learning models will be evaluated to predict prices and the best performing model will be implemented.

Results and finding will be deployed as a web application.

### Update (Feb 2020)

Model research with feature engineering is nearing its end and deployment phase is beginning.

The LightGBM model was chosen for its low RMSE value and high variance score.

The current goals are:
- Development utility functions to clean and test data
- Development utility function to retrain the model and serialise the object
- Implement the model as a REST microservice and containerise it
