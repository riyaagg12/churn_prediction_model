# Churn Prediction Model

This project predicts customer churn based on various attributes like credit score, geography, age, and account activity. Using machine learning techniques, this model identifies customers who are likely to leave a service or product.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn is a critical business metric, especially in subscription-based services. This project uses machine learning to help businesses predict churn and implement retention strategies proactively.

The project leverages Python and libraries such as:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset

The dataset (`Churn_Modelling.csv`) contains the following features:

- **RowNumber**: Serial number of the entry
- **CustomerId**: Unique customer identifier
- **Surname**: Customer's last name
- **CreditScore**: Credit score of the customer
- **Geography**: Country of the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been a client
- **Balance**: Customer's bank balance
- **NumOfProducts**: Number of bank products held by the customer
- **HasCrCard**: Indicates if the customer has a credit card
- **IsActiveMember**: Indicates if the customer is an active member
- **EstimatedSalary**: Estimated salary of the customer
- **Exited**: Target variable indicating whether the customer churned

## Installation

1. Open the project in Google Colab:

   - Upload the notebook file (`churn_prediction_model.ipynb`) and the dataset (`Churn_Modelling.csv`) to your Google Drive.
   - Open the notebook in Google Colab by right-clicking and selecting "Open with > Google Colaboratory."

2. Ensure that the required libraries are installed in the Colab environment. Use the following command in a code cell to install missing dependencies:

   ```python
   !pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage

1. Upload the dataset to your Colab session or mount your Google Drive.

2. Load the dataset into the notebook using Pandas:

   ```python
   import pandas as pd
   df = pd.read_csv('/content/drive/MyDrive/Churn_Modelling.csv')
   ```

3. Run all cells in the notebook to:
   - Preprocess the data
   - Train the machine learning model
   - Evaluate the model's performance

4. Modify input values in the notebook to test predictions for specific customers.

## Results

The model achieved the following metrics:

- **Accuracy**: XX% (Replace with actual accuracy)
- **Precision**: XX% (Replace with actual precision)
- **Recall**: XX% (Replace with actual recall)
- **F1 Score**: XX% (Replace with actual F1 Score)

Visualizations include:

- Feature importance
- Correlation heatmaps
- Model evaluation metrics

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Commit your changes.
4. Submit a pull request.
