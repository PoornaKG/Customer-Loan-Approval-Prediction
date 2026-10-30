Customer Loan Approval Prediction Using Machine Learning

1. Project Overview

This project focuses on developing a Machine Learning classification model to predict whether a customer's loan application will be approved or rejected based on financial and personal attributes.

The project uses Logistic Regression, a supervised machine learning algorithm, to learn patterns from historical loan application data and classify new applications into two categories: Approved (1) or Not Approved (0).

The primary objective is to understand and implement the complete Machine Learning workflow, including data exploration, preprocessing, model training, prediction, and performance evaluation.

2. Dataset Information

The dataset contains 1,000 customer records and 6 columns, representing customer details and loan approval status.

| Feature | Description |
|---|---|
| Age | Customer's age |
| Income | Customer's income |
| Loan_Amount | Requested loan amount |
| Credit_Score | Customer's credit score |
| Employment_Type | Employment category |
| Loan_Approved | Target variable |

Target Variable:
- `1` – Loan Approved
- `0` – Loan Not Approved

3. Data Preprocessing

The following preprocessing techniques were implemented:

- Data Exploration: Examined dataset dimensions, columns, and missing values using Pandas.
- Missing Value Handling: Replaced missing Income values with the mean and missing Employment_Type values with the mode.
- Categorical Encoding: Applied Label Encoding to convert employment categories into numerical values.
- Feature and Target Separation: Separated input features (X) and target variable (y).

4. Machine Learning Algorithm

Logistic Regression

Logistic Regression was implemented as the classification algorithm to predict loan approval outcomes.

The model was trained using the preprocessed customer data to identify patterns associated with loan approval.

5. Train-Test Split

The dataset was divided into training and testing subsets using an 80:20 ratio.

- Training data: 80% (800 records)
- Testing data: 20% (200 records)

The `train_test_split()` function from Scikit-learn was used with `random_state=42` to ensure reproducibility.

6. Model Evaluation

The trained model generated predictions on the unseen test dataset.

The following evaluation techniques were used:

- Accuracy: Measures the overall proportion of correct predictions.
- Precision: Measures how many predicted approvals or rejections were correct.
- Recall: Measures how many actual approvals or rejections were correctly identified.
- F1-Score: Represents the balance between precision and recall.
- Confusion Matrix: Visualizes correct and incorrect classification results.

7. Model Performance

The Logistic Regression model achieved an accuracy of 79% on the test dataset.

| Evaluation Metric | Not Approved (0) | Approved (1) |
|---|---:|---:|
| Precision | 0.83 | 0.70 |
| Recall | 0.87 | 0.62 |
| F1-Score | 0.85 | 0.66 |

Overall Accuracy: 79%

8. Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

9. Key Learning Outcomes

Through this project, I gained practical experience in:

- Understanding supervised machine learning.
- Exploring and cleaning structured datasets.
- Handling missing values and categorical variables.
- Implementing Logistic Regression for classification.
- Splitting datasets into training and testing sets.
- Evaluating model performance using classification metrics.
- Visualizing model predictions using a confusion matrix.

10. Conclusion

This project provided hands-on experience in building and evaluating a supervised Machine Learning classification model. It strengthened my understanding of data preprocessing, Logistic Regression, model prediction, and performance evaluation.

This is a learning project developed to build a strong foundation in Machine Learning and practical data science workflows.
