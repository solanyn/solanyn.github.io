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

Status: Completed  

GitHub: https://github.com/solanyn/property-prediction

This project aims to predict the value of property in Melbourne, Australia using spatial features and physical features and trained using a cleaned dataset. Data for properties to predict on was obtained using the Domain API. Data will be cleaned manually as well as generating new features from auxiliary data sets. Various machine learning models will be evaluated to predict prices and the best performing model will be implemented. Results and finding will be deployed as a web application hosted on AWS.

### Update (Feb 2020)

Model research with feature engineering is nearing its end and deployment phase is beginning. The LightGBM model was chosen for its low RMSE value and highest R-squared score.

The current goals are:
- Development utility functions to clean and test data
- Development utility function to retrain the model and serialise the object
- Implement the model as a REST microservice and containerise it

Future goals are:
- Create a web application around the trained model and display the predictions

### Update (Jul 2020)

The project is completed as a full-stack web application hosted on AWS using Docker and AWS EC2 as a REST API to serve model predictions. Properties are retrieved from the Domain API to display on a map and a static JavaScript web page was used to display the properties on a map. A more detailed writeup and source code can be found on the GitHub link at the top of the page.
