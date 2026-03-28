Classification with Logistic Regression
Project Overview

This project was completed as part of my internship at Codved (Level 2 - Task 2). The goal of this task is to build and evaluate classification models to predict a categorical outcome using machine learning techniques.

The primary focus is on Logistic Regression, with comparisons made against other models such as Decision Tree, Random Forest, and Support Vector Machine (SVM).

Objectives
Preprocess the dataset (handle categorical variables and apply feature scaling)
Train a Logistic Regression model
Evaluate model performance using:
Accuracy
Precision
Recall
ROC Curve
Compare performance with other classification models
Tools & Technologies
Python
pandas
scikit-learn
matplotlib
Dataset

The dataset used contains features for predicting a categorical outcome (e.g., flower species classification). It includes:

Multiple input features
A target variable representing class labels
Data Preprocessing

The following preprocessing steps were performed:

Encoding categorical variables
Feature scaling using standardization
Splitting data into training and testing sets

The following machine learning models were trained and evaluated:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier

Model Performance

All models achieved perfect performance on the dataset:

Model	Accuracy
Logistic Regression	1.0
Decision Tree	1.0
Random Forest	1.0
Evaluation Metrics:
Precision: 1.0
Recall: 1.0
ROC Curve: Perfect classification
Note on Results

Achieving 100% accuracy across all models may indicate:

A very simple or well-separated dataset
OR potential overfitting

Further validation (e.g., cross-validation) is recommended to ensure model generalization.

Visualization
ROC Curve plotted to evaluate classifier performance
Comparison charts for model accuracy
Key Takeaways
Logistic Regression performed equally well compared to more complex models
Ensemble methods like Random Forest did not provide additional improvement
Proper preprocessing significantly impacts model performance
Conclusion

This project demonstrates the effectiveness of classification algorithms in predicting categorical outcomes. Even simple models like Logistic Regression can perform exceptionally well when the dataset is well-structured.

👨‍💻 Author

Muhammed Abdullahi
Data Science Intern @ Codved

