# Kaggle Competition - Predicting Airbnb User Bookings

This repository contains code developed for [Airbnb's Kaggle
competition][competition]. It is written in **Python 3** using **Jupyter Notebooks**.

[competition]: https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings

## Description

New users on Airbnb can book a place to stay in 34,000+ cities across 190+
countries. By accurately predicting where a new user will book their first
travel experience, Airbnb can share more personalized content with their
community, decrease the average time to first booking, and better forecast
demand.

In this competition, the goal is to predict in which country a new user
will make his or her first booking. There are **12** possible outcomes of the
destination country and the datasets consist of a list of users with their
demographics, web session records, and some summary statistics.

## Data

All of the datasets for the competition can be downloaded at the [competition][competition] website.

You will need to download the files `train_users_2.csv`, `test_users.csv` and `sessions.csv`
and unzip them into the 'data' folder.

**Note**: Please rename `train_users_2.csv` to `train_users.csv`



## Requirements

To replicate the findings and execute the code in this repository you will need
the following Python packages:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Jupyter](http://jupyter.org/)
- [SciKit-Learn](http://scikit-learn.org/stable/)
- [Matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Imbalanced Learn](http://contrib.scikit-learn.org/imbalanced-learn/stable/api.html)


## Resources

- [LightGBM Documentation](https://lightgbm.readthedocs.io) - A library designed
and optimized for boosted (tree) algorithms.
- [XGBoost Documentation](https://xgboost.readthedocs.org) - Another library designed
and optimized for boosted (tree) algorithms.


Enclosed in this repository are also the following portions of the capstone project for Udacity's Machine Learning NanoDegree:
1. Capstone Report PDF
2. Data Exploration Jupyter Notebook
3. Data Preprocessing, Training, Cross Validation, and Testing Jupyter Notebook
