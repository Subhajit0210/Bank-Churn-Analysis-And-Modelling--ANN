# Bank-Churn-Analysis-And-Modelling--ANN

## Table of Contents
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Data Collection](#data-collection)
- [Data Preparation  or Data Preprocessing](#data-preparation-or-data-preprocessing)
- [Data Visualization](#data-visualization)
- [Model Architecture](#model-architecture)
- [Results and Insights](#results-and-insights)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview
Customer churn is a critical challenge in the banking sector. In this project, I developed an Artificial Neural Network (ANN) model to predict customer churn based on various demographic and account-related factors. The goal is to identify potential churners and take proactive measures to retain valuable customers.

## Dependencies
Make sure you have the following Python libraries installed before running the project:
- numpy - Data Manipulation
- pandas - Numerical Computations
- matplotlib - Data Visualization
- scikit-learn - Preprocessing, Model valuation
- keras - Building the ANN model

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

## Model Architecture
The **Artificial Neural Network (ANN)** used for classification consists of:

| **Layer**          | **Neurons** | **Activation Function** | **Initialization** |
|---------------|---------|---------------------|---------------|
| Input Layer   | 6       | ReLU                | He Uniform    |
| Hidden Layer 1| 6       | ReLU                | He Uniform    |
| Hidden Layer 2| 6       | ReLU                | He Uniform    |
| Output Layer  | 1       | Sigmoid             | -             |

### Hyperparameters:
- **Activation Function**: RELU (best one for hidden layers) & Sigmoid (for the output layer)
- **Optimizer**: Adamax or Adam (It is one the popular optimizer)
- **Loss Function**: Binary Cross-Entropy (It is mainly used when we have only 2 categories or for binary classification)
- Weight Initialization Technique: He_Uniform
- **Epochs**: 100
- **Batch Size**: 10
- **Validation Split**: 33%

### Description of it:
This ANN model is designed for Bank Churn Prediction. The model consists of an input layer, two hidden layers using ReLU activation, and an output layer with a Sigmoid activation function for binary classification. The **He Uniform** initializer is used for weight initialization in the hidden layers.

## How to Run

1. Install dependencies:
   ```bash
   pip install tensorflow numpy pandas matplotlib



## Usage
To run the project, follow these steps:
1. Clone the repository:
```bash
https://github.com/Subhajit0210/Bank-Churn-Analysis-And-Modelling--ANN.git
```
2. Run the Jupyter notebook:
```bash
jupyter notebook Bank_Churn_Analysis_&_Modelling_ANN.ipynb
```

## Contributing
Contributions are welcome! Please create a new branch for any changes and submit a pull request for review.
