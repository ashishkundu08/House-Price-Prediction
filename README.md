🏠 House Price Prediction

This project applies machine learning techniques to predict house prices based on various property features such as area, quality, location, and garage type.
It demonstrates how different regression models perform, explores the impact of regularization, and visualizes feature importance using real housing data.

🎯 Objective

The goal of this project is to build predictive models that can accurately estimate house prices based on various features. The focus areas include:

Understanding how regression techniques work

Applying Ridge and Lasso regularization

Comparing models using evaluation metrics

Interpreting coefficients and feature importance

🧠 Models Used

Linear Regression → Baseline model without regularization

Ridge Regression → L2 regularization to handle multicollinearity

Lasso Regression → L1 regularization for feature selection

Decision Tree Regressor → Non-linear model for hierarchical data splits

📊 Evaluation Metrics

R² Score – Model accuracy

RMSE – Root Mean Squared Error

🧰 Tools & Libraries

Python

NumPy, Pandas

Scikit-learn

Jupyter Notebook

🗂️ Dataset

Dataset: Ames Housing Dataset (from Kaggle
)

Features: 80+ numerical and categorical features

Target: SalePrice (House Price)

⚙️ Key Steps

Data Cleaning & Preprocessing

Removed columns with excessive missing values

Imputed missing data

Encoded categorical variables (One-Hot Encoding)

Applied feature scaling where needed

Model Training & Evaluation

Split dataset using train_test_split

Trained four regression models

Compared R² and RMSE values

Coefficient & Feature Analysis

Visualized top features for Linear, Ridge, and Lasso

Noted how Lasso zeroes out less important features

Feature Importance (Decision Tree)

Extracted top 10 important features

Visualized using feature importance plots

📈 Results
Model	R² Score
Linear Regression	0.9092
Ridge Regression	0.8823
Lasso Regression	0.9092
Decision Tree	0.8079

Lasso performed similarly to Linear Regression, while Ridge slightly underperformed.
Decision Tree showed overfitting on deeper depths.

💡 Learnings

Understanding regression models and their differences

Interpreting and visualizing model coefficients

Recognizing overfitting in Decision Trees

Importance of regularization for generalization

👨‍💻 Author

Ashish Kundu
2nd Year B.Tech in Chemical Engineering
Indian Institute of Technology, Hyderabad
