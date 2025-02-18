# Bank-Churn-Analysis-And-Modelling--ANN

## Table of Contents
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Data Collection](#data-collection)
- [Data Preparation  or Data Preprocessing](#data-preparation-or-data-preprocessing)
- [Data Visualization](#data-visualization)
- [Clustering Techniques](#clustering-techniques)
- [Results and Insights](#results-and-insights)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview
Customer churn is a critical challenge in the banking sector. In this project, I developed an Artificial Neural Network (ANN) model to predict customer churn based on various demographic and account-related factors. The goal is to identify potential churners and take proactive measures to retain valuable customers.

## Dependencies
The project requires the following Python libraries:
- numpy
- pandas
- matplotlib
- scikit-learn
- keras

## Data Collection
The dataset used in this project is the 'Mall_Customers.csv' file, which contains information about customers such as:
- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited

## Data Preparation or Data Preprocessing
The data preparation steps included:
- Loading the data into a Pandas DataFrame.
- Performing exploratory data analysis (EDA) to understand the data distribution.
- Checking for and handling any missing values.
- Dropped unnecessary columns (RowNumber, CustomerId, Surname).
- Creating dummy variables (Gender, Geography).
- Concatenation of dummy variables (Gender, Geography).
- Dropping of unnecessary columns (Gender, Geography).

## Data Visualization
- Visualizing the training progress of the Artificial Neural Network (ANN).
- Visualize the loss of the Artificial Neural Network (ANN) during training.

