# AV-Janatahack-Cross-Sell-Prediction
This competition was hosted from 11th September to 20th September 2020

## Problem Statement 
Your client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else.

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue. 

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

## Files provided  
train.csv, test.csv and sample_submission.csv

## Evaluation Metric

The evaluation metric for this hackathon is ROC_AUC Score.

## Public and Private Split
The public leaderboard is based on 40% of test data, while final rank would be decided on remaining 60% of test data (which is private leaderboard)

## Guidelines for Final Submission

Please ensure that your final submission includes the following:
1. Solution file containing the predicted response of the customer (Probability of response 1)
2. Code file for reproducing the submission, note that it is mandatory to submit your code for a valid final submission

## Final Results
ROC AUC Score (Private) - 0.8629324603 
ROC AUC Score (Public) - 0.8578634574

## Winning Results
ROC AUC Score (Private) - 0.8639416417
ROC AUC Score (Public) - 0.8594633845
 
