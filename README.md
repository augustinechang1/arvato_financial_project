# Arvato Customer Segmentation & Prediction

Python Version 3.7.4

Package used - sklearn, time, numpy, pandas, matplotlib, tqdm

## Domain
Arvato, a services company is looking to help its client, a mail company to better understand its customer segments and identify the most probable customers.
Company’s marketing goal is to target audience that are most likely to respond to a mail and convert to a customer

## Problem
Targeting consumers has mainly been driven by business experience and intuition, making it hard to predict or track the success of campaigns. With data, we can make more accurate predictions that lead to a greater outcome (i.e., increase in profitability)
Following problems exists within the dataset, which requires additional wrangling:
- Inconsistency in type and format
- Unknown values marked as 0’s and -1’s, need to be converted to nan
- Sparse dataset- need to drop columns and rows that have majority of nan’s and replace the rest with a value
- Encode categorical variables
- Too many features- feature selection

## Data
All dataset has been provided under agreement to terms and conditions
Customer demographic information
Population demographic information
Information describing the demographic metadata and range of values
Training and testing data, including labels for whether a customer converted or not given in training data

## Benchmark Model
Logistic Regression, most foundational and easy to interpret. Logistic regression uses a sigmoid function, which maps the probability between 0 and 1. In this project, I used the logistic regression to predict whether he/she will convert to a customer (1) or not (0) given the customer's demographics.

## Evaluation Metrics
AUC score

## Project Design
By applying data and data-driven techniques to uncover various insights of customer behavior, we can:
Segment customers based on their attributes
Predict probability of customer making a purchase given mail ad
Test model on unseen data points (other customers)

*Further details and annotations can be found within the jupyter notebook
