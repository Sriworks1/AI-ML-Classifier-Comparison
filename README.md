# Comparing Classifiers - Practical Application #3

## Overview

Our goal of this assignment is to compare the performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines) using a [banking dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) that is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

## Business Context

This banking dataset helps banking institution to predict the success of their marketing campaign. If the propensity to subscribe the bank product(in this case, a term deposit) is high, tele marketer could prioritize such contact  and thus be productive and yield better results. This would save a lot of time in productivity for tele marketers and improved customer loyality. 

# Data Understanding

| Column      | Feature Type | Description
| ----------- | ----------- | -----------
| age      | Numerical       | Age
| job   |  Categorical | Type of Job ("admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services")  