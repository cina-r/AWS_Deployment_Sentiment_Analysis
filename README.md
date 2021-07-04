# AWS_Deployment_Sentiment_Analysis
This is the fifth and last project of the Udacity Deep Learning Nanodegree Program.  

## Setting up the virtual environment

1. >pip install virtualenv
2. python -m venv env
3. cd .\env\Scripts
4. activate
5. pip install -r requirements.txt
6. python -m ipykernel install --name=<choose-a-name-to-be-displayed-in-jupyter>

## Problem statement
We want to use Amazon SageMaker to deploy a sentiment analysis model and use it in a simple web page. The web page offers end users the possiblity to enter a movie review and then sends that review to our deployed model. The model will predict the review's sentiment in order to show it on the web page. 

## Solution
After some pre-processing, the training data from [IMDb](https://www.imdb.com/) is uploaded to Amazon's S3 together with the training script *train.py*. The trained model is then deployed and tested. The web app in this case is a simple static html file *index.html*. Exemplary results for a positive and a negative result, respecively, are shown in the following screenshots:
![Positive Review](/WebApp_Screenshot_1.png)
![Negative Review](/WebApp_Screenshot_2.png)
