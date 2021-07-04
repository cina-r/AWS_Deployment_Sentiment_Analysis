# AWS_Deployment_Sentiment_Analysis
This is the fifth and last project of the Udacity Deep Learning Nanodegree Program.  

## Problem statement
We want to use Amazon SageMaker to deploy a sentiment analysis model and use it in a simple web page. The web page offers end users the possiblity to enter a movie review and then sends that review to our deployed model. The model will predict the review's sentiment in order to show it on the web page. 

## Solution
After some pre-processing, the training data is uploaded to Amazon's S3 together with the training script *train.py*. The trained model is then deployed and tested. The web app in this case is a simple static html file *index.html*. Exemplary results for a positive and a negative result, respecively, are shown in the following screenshots:
![Positive Review](/WebApp_Screenshot_1.png)
![Negative Review](/WebApp_Screenshot_1.png)
