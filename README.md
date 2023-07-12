# Credit Card Fraud Detection
This project aims to develop a credit card fraud detection system using various modeling techniques. The following sections outline the steps involved in this project.

## Table of Contents

1. Introduction
2. Installation
3. Usage
4. Results
5. Contributing
6. License

## Introduction
Credit card fraud is a significant issue that affects individuals and businesses worldwide. This project addresses the problem by developing a fraud detection system using machine learning algorithms. The dataset used in this project contains credit card transactions labeled as fraudulent or non-fraudulent.

## Installation
To run this project locally, follow these steps:

1. Clone the repository.
2. Install the required libraries.

## Usage

1. Import Libraries: The necessary libraries are imported at the beginning of the code.

2. Load Data: The credit card fraud dataset is loaded into the program.

3. Exploratory Data Analysis (EDA):
a. Random Sample: Prints a random sample of 10 rows to verify data loading.
b. Data Overview: Displays an overview of the dataset.
c. Numerical Summary: Provides statistical summary for the 'Time' and 'Amount' columns.
d. Distribution Plots: Plots the distribution of the 'Time' and 'Amount' features.
e. Fraud vs Non-Fraud Transactions: Counts the number of fraud and non-fraud transactions and displays their ratio.
f. Count Plot: Creates a bar chart showing the count of fraud and non-fraud transactions.

4. Data Processing:
Correlation Heatmap: Plots a heatmap to identify any high correlations between variables.

5. Modelling:
a. Data Split: Splits the data into training, validation, and test sets while maintaining the class distribution.
b. StandardScaler: Initializes and fits the StandardScaler object to the training data.
c. Data Scaling: Scales the training, validation, and test sets using the fitted scaler.
d. Undersampling: Utilizes undersampling to address the issue of imbalanced classes.

6. Modeling Techniques:
a. Logistic Regression: Trains a logistic regression model on the resampled data.
b. Naive Bayes: Trains a Naive Bayes model on the resampled data.
c. Random Forest: Trains a random forest model on the resampled data.
d. Support Vector Machine (SVM): Trains an SVM model on the resampled data.

## Results
This project provides an understanding of the dataset through exploratory data analysis. The distribution plots reveal insights into the 'Time' and 'Amount' features. The count plot visually represents the number of fraud and non-fraud transactions. Additionally, a correlation heatmap is generated to identify any high correlations between variables.
The modeling techniques used in this project include logistic regression, Naive Bayes, random forest, and support vector machine (SVM). The performance of these models can be evaluated based on their accuracy, precision, recall, and F1-score.

## Contributing
Contributions to the Credit Card Detection project are welcome. If you would like to contribute, please follow the standard GitHub workflow:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request, explaining the purpose and changes of your contribution.

## Contact
For any questions, suggestions, or inquiries, please feel free to contact me at [rakshit.ayachit@gmail.com](mailto:rakshit.ayachit@gmail.com). We appreciate your feedback and contributions to improve the project.


