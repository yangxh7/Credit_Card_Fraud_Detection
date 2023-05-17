# Credit Card Fraud Detection

This machine learning project is designed to identify fraudulent credit card transactions. The creditcard.csv dataset contains data on credit card transactions made over a period of 2 days in September 2013 by European cardholders. The dataset contains a total of 31 variables, including time, amount, and 28 anonymous variables (V1-V28) which have been derived using a PCA transformation. The target variable is Class, which takes on the value 1 in cases where the transaction was fraudulent and 0 otherwise. 

The dataset is highly unbalanced, with only 0.17% of transactions being classified as fraudulent. The purpose of this dataset is to build predictive models to identify fraudulent credit card transactions based on the given features.

## Table of Contents

- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Background

Credit card fraud continues to be a major problem for both merchants and customers, with significant financial impact on everyone involved. Machine learning techniques has proven effective in detecting fraudulent transactions, and this project aims to identify fraudulent behavior using predictive models.

This project focuses on a dataset that contains various features of credit card transactions, including time, amount, and several anonymous variables derived using Principal Component Analysis (PCA) transformation. I will use a Random Forest classifier in this project to identify fraudulent transactions accurately, even with a highly unbalanced dataset.

## Installation

This project requires the following libraries:

- numpy
- pandas
- sklearn
- matplotlib
- seaborn

To install these libraries, execute the following command:

```
pip install numpy pandas sklearn matplotlib seaborn
```

## Usage

To use this project, follow these steps:

1. Clone this repository to your local environment.
2. Download the dataset from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud, and save the csv file into the repository.
3. Install the required libraries using the command mentioned in the installation section.
4. Run the `credit_card_fraud_detection.ipynb` script to preprocess the data, train the Random Forest classifier model, and evaluate its performance by calculating accuracy and AUC score.

## Evaluation

The evaluation for this project is based on accuracy and Area Under the Curve (AUC) of the Precision-Recall curve. The model achieved an accuracy score of 0.9996 on the testing set, indicating that it performed exceptionally well in predicting the target variable. The precision-recall curve AUC score of 0.863 also shows that the Random Forest classifier model is effective in detecting credit card fraud.

## Conclusion

This project demonstrates the potential of using machine learning to detect credit card fraud. The Random Forest classifier model achieved outstanding accuracy and AUC score when tested on the preprocessed credit card fraud dataset, even with a highly unbalanced dataset. However, this model can further be enhanced with additional data to ensure its effectiveness in identifying fraudulent transactions in real-world applications.

## Contributing

Contributions are always welcome. If you have any suggestions, please feel free to create a pull request.
