# Machine Learning Midterm Project (Loan Approval Prediction)

## Project Overview

This project is a supervised machine learning classification task that predicts whether a loan application will be approved or not based on applicant information. A realistic synthetic dataset of 150 samples is generated using Python.


## Objective

* Build a custom dataset using Python
* Perform Exploratory Data Analysis (EDA)
* Visualize data patterns
* Apply supervised learning models
* Compare model performance
* Evaluate accuracy and analyze results


## Dataset Description

The dataset contains 150 records with the following features:

* Gender
* Married
* Education
* ApplicantIncome
* LoanAmount
* Credit_History
* Loan_Status (Target Variable: 0 = Not Approved, 1 = Approved)

Note: Dataset is synthetically generated using NumPy for realistic behavior.


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn



## Exploratory Data Analysis (EDA)

The following steps were performed:

* Data inspection using `.info()` and `.describe()`
* Checking missing values
* Visualizing class distribution
* Income vs Loan Status analysis
* Correlation heatmap



## Machine Learning Models Used

### 1. Logistic Regression

* Simple linear classification model
* Works well for baseline prediction

### 2. Decision Tree Classifier

* Handles non-linear relationships
* Captures complex decision rules



## Evaluation Metrics

* Accuracy Score
* Train vs Test Accuracy Comparison
* Confusion Matrix



## Results Summary

* Decision Tree achieved higher training accuracy but showed slight overfitting
* Logistic Regression gave more stable and generalizable results


## Conclusion

This project demonstrates how different machine learning models behave on the same dataset. It highlights the trade-off between model simplicity (Logistic Regression) and complexity (Decision Tree).



## How to Run the Project

1. Open Jupyter Notebook or Google Colab
2. Run all cells step-by-step
3. Observe EDA, training, and results
4. Compare model performance



## Project Structure


ML-Loan-Project/
│── notebook.ipynb
│── README.md

## Author

AYMEN  ZEHRA
ML Midterm Project Submission
