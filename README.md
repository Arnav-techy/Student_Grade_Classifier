# Student_Grade_Classifier
ML Classification for Student Performance

## 📌 Project Overview

This project is part of a Machine Learning Competition focused on educational data analysis. The objective is to build a classification model that predicts students' final grades based on demographic, academic, and behavioral attributes.

## 🎯 Objectives
Perform comprehensive data cleaning and preprocessing.

Conduct exploratory data analysis (EDA) and outlier detection.

Encode categorical variables and apply feature scaling.

Perform correlation analysis to identify significant features.

Train and evaluate multiple classification models.

Perform hyperparameter tuning on the best-performing model.

Generate predictions on the test dataset and submit results.

## 📁 Files Provided
train.csv: Dataset with features and target column (final_grade).

test.csv: Dataset without the target column (for predictions).

sample_submission.csv: Example of the submission format.

## 📊 Evaluation Metric
Accuracy is used to evaluate model performance.

Higher accuracy indicates better predictive performance.

## 🚀 Deliverables
Predictions (.csv): Submitted via both the Kaggle Competition Webpage and Google Form.

Notebook (.ipynb): Clean, well-documented code including all required steps.



## 📤 Submission Format
The final submission CSV must have the following structure:

id |	final_grade

1	 |    a

2	 |    a

3	 |    a

…	 |    …
## ⚙️ Implementation Steps

1. Data Cleaning and Preprocessing
   
    Handle missing values.

    Remove duplicates.

    Correct inconsistent data entries.

2. Data Visualization and Outlier Analysis
   
    Visualize feature distributions.

    Identify and treat outliers using appropriate methods (IQR, Z-score, etc.).

3. Encoding Categorical Variables
   
    Apply Label Encoding or One-Hot Encoding as needed.

5. Feature Scaling
   
    Use StandardScaler or MinMaxScaler to normalize numerical features.

6. Correlation Analysis
   
    Compute correlation matrix.

    Identify and retain significant features.

6. Model Training
   
    Train multiple classifiers (e.g., Logistic Regression, Random Forest, XGBoost, etc.).

    Evaluate using cross-validation.

7. Hyperparameter Tuning

    Use GridSearchCV or RandomizedSearchCV to optimize the best model.

8. Generate Predictions

    Predict on test.csv.

    Save results in the required CSV format.

## 📈 Evaluation Components
Component	Weight
Data Cleaning and Preprocessing	High
Data Visualization and Outlier Analysis	High
Model Training and Hyperparameter Tuning	High
Competition Submission	High
Note: All deliverables including Google Form submission are mandatory for complete evaluation.

## 📅 Competition Timeline
Start: Dec 19, 2025

Close: Dec 19, 2025

## 🛠️ Requirements
Python 3.7+

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, etc.

## 📝 Usage
Clone the repository.

Install required libraries:



pip install -r requirements.txt

Run the Jupyter notebook (EduGrade_Predictor.ipynb).

Generate predictions and submit via Kaggle and Google Form.

## 🤝 Contributors
Department of Computer Science and Engineering (AI & AIML)

## 📄 License
This project is for educational and competition purposes.

Good luck with your machine learning journey! 🏆



