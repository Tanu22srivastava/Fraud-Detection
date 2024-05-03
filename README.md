# Credit Card Fraud Detection

## Project Overview
The "Credit Card Fraud Detection" project focuses on building a model to detect fraudulent transactions in credit card data. The dataset used in this project is available on Kaggle and contains transactions that occurred over two days, with 492 frauds out of 284,807 transactions, making the dataset highly unbalanced.

## Model Used
For this project, a logistic regression model was employed due to its simplicity and effectiveness in binary classification tasks. 

## Dataset Description
- **Features**: The dataset contains only numerical input variables resulting from a PCA transformation. Features V1 to V28 are the principal components obtained through PCA. Additionally, the dataset includes non-PCA transformed features such as Time (seconds elapsed between each transaction and the first transaction) and Amount (transaction amount).
- **Response Variable**: The response variable, Class, takes a value of 1 in case of fraud and 0 otherwise.

## Data Preprocessing
- **Data Balancing**: Due to the highly unbalanced nature of the dataset (with frauds accounting for only 0.172% of all transactions), the data was balanced before model training to avoid bias towards the majority class.
  
## Model Evaluation
The model's performance was evaluated using standard classification metrics such as accuracy, precision, recall, and F1-score. Additional techniques such as cross-validation were employed to ensure the model's robustness.

## Dataset Link
The dataset used in this project can be found on Kaggle at [link to dataset](https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input).

## Note
Please note that due to confidentiality issues, the original features and more background information about the data are not provided.

Feel free to reach out if you have any questions or need further information about this project.
