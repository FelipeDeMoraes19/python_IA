# Python AI Project: Artificial Intelligence and Predictions

## Code Overview

The provided Python code performs the following steps:

1. **Data Loading and Visualization**: Customer data is loaded from the "clientes.csv" file using the pandas library. Information about the table, such as the first few rows and data types, is displayed.

2. **Data Preprocessing**: The LabelEncoder class from the sklearn library is used to encode categorical variables such as "profissao", "mix_credito", and "comportamento_pagamento". The variables are then split between dependent (y) and independent (x) variables.

3. **Data Splitting**: The data is split into training and testing sets using the train_test_split function from the sklearn library.

4. **Model Building**: Two classification algorithms, RandomForestClassifier and KNeighborsClassifier, are used to build credit score prediction models.

5. **Model Evaluation**: The performance of the models is evaluated using the accuracy metric.

6. **Credit Score Prediction for New Customers**: The models are used to predict the credit score of new customers, whose data is loaded from the "novos_clientes.csv" file.

7. **Variable Importance Analysis**: An analysis is performed to identify the importance of variables in predicting the credit score.

## Project Files

- `clientes.csv`: File containing data of bank customers.
- `novos_clientes.csv`: File containing data of new customers for whom the credit score will be predicted.
- `inicial.ipynb`: JupyterNotebook source code containing the main script of the project.

## Installation Requirements

To run the code in this project, you need to have Python installed on your system. Additionally, the following Python libraries are used and must be installed:

- pandas
- scikit-learn

The libraries can be installed using pip:

```bash
pip install pandas scikit-learn
```
