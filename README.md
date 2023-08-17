# Predicting Water Temperature with Linear Regression - CalCOFI Dataset

This Jupyter Notebook presents an endeavor of predicting ocean water temperature using linear regression techniques. The analysis is conducted on the CalCOFI dataset, which provides a substantial amount of diverse and high-quality oceonographic data.

## Table of Contents

[[TOC]]

## Introduction
## Dataset
## Notebook Contents

## Introduction

This notebook focuses on predicting ocean water temperature using linear regression techniques. The goal is to explore the relationships between water temperature and other relevant features, such as depth, salinity, oxygen concentration, and spatiotemporal factors. The analysis includes Exploratory Data Analysis (EDA), feature engineering, feature selection, and the evaluation of three different linear regression models.

## Dataset

The dataset used for this analysis is the CalCOFI dataset, which contains observations of more than 70 various oceanographic variables, including water temperature. The data is gathered from the year 1949 and up to now at 75 or 113 hydrographic stations (depending on the season of expedition) and includes samples from different depth levels. Standard expeditions sample the water from down to 500 meters deep, while deep casts may go down to 5000 meters deep.

The dataset can be found on the official site of the programme: [CalCOFI Website](https://calcofi.org/data/oceanographic-data/bottle-database/)

## Notebook Contents

This notebook is organized into the following sections:

- Data Exploration: In this section, we will take a closer look at the dataset, examine its structure, and gain insights into the variables.
- Data Cleaning: Here, we will clean the data by addressing missing values, and any other data quality issues.
- Data Splitting: We will split the dataset into training and testing sets to prepare for model building and evaluation.
- Feature Extraction: This section involves extracting relevant features from the dataset that will be used in our modeling process.
- Data Visualization: We will use visualizations to further explore the relationships between variables and gain a deeper understanding of the data.
- Outliers Detection: Detecting and handling outliers is crucial for building a robust predictive model. We will identify and address outliers in this section.
- Feature Selection: We will select a set of features using a mutual information score.
- Feature Preprocessing and Feature Engineering: Here, we will preprocess the features, perform transformations, and engineer new features to enhance our model's performance.
- Choosing a Model: In this section, we will select the appropriate regression model for predicting water temperature based on the features we have prepared.
- Fitting and Evaluating the Model: We will train our chosen model on the training data, evaluate its performance using appropriate metrics, and refine it.
- Conclusion: Finally, we will summarize our findings, discuss the results of our modeling efforts, and suggest potential areas for future work.

For detailed information and code implementation, please refer to the notebook file.
