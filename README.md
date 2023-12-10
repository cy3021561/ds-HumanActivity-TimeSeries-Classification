# Time Series Classification Project

## Overview

This project is focused on the classification of human activities using time series data obtained from a Wireless Sensor Network. It involves feature creation/extraction from time series and implementing classification models.

## Dataset: AReM

- **Source**: The dataset can be downloaded from the [UCI Machine Learning Repository - Activity Recognition system based on Multisensor data fusion (AReM)](https://archive.ics.uci.edu/ml/datasets/Activity+Recognition+system+based+on+Multisensor+data+fusion+%28AReM%29).
- **Content**: The dataset contains 7 folders representing seven types of activities. Each folder has multiple files, each file representing an instance of a human activity.
- **Features**: Each file contains 6 time series (`avg rss12`, `var rss12`, `avg rss13`, `var rss13`, `vg rss23`, and `ar rss23`), with each time series comprising 480 consecutive values.
- **Instances**: There are 88 instances in the dataset.

## Project Tasks

### Part 1: Feature Creation/Extraction

- Extract and create relevant features from the time series data for classification purposes.

### Part 2: Binary and Multiclass Classification

- **(a) Binary Classification Using Logistic Regression**: Implement logistic regression for binary classification of activities.
- **(b) Binary Classification Using L1-penalized logistic regression**: Explore the use of L1 regularization in logistic regression for binary classification.
- **(c) Multi-class Classification (The Realistic Case)**: Implement and evaluate a multi-class classification model for the realistic scenario of multiple activities.

## Objective

The goal of this project is to accurately classify human activities based on sensor-generated time series data, exploring various feature extraction techniques and classification models.

## Importance

Understanding human activities through sensor data has significant applications in areas such as healthcare monitoring, sports analytics, and human-computer interaction.
