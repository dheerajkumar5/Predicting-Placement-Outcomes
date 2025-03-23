# Predicting-Placement-Outcomes
Logistic Regression Model: Predicting Placement Outcomes

This repository contains a Logistic Regression model aimed at predicting student placement outcomes based on their CGPA and IQ scores. The project includes data exploration, model development, and performance evaluation, offering insights into the factors influencing placement decisions.

**Key Features**
Dataset Summary:

CGPA ranges from 3.3 to 8.5, with an average of 5.991.

IQ scores span from 37 to 233, with an average of 123.58.

Placement outcomes are binary, evenly distributed (0.5 mean).

**Data Insights:**

CGPA and Placement have a strong positive correlation, as highlighted in the correlation matrix (0.82).

The dataset exhibits varied characteristics, with skewness and kurtosis insights (if analyzed).

CGPA Distribution: Displays a visual representation (e.g., histogram) highlighting the spread of CGPA values.

Correlation Matrix: Demonstrates a strong correlation (0.82) between CGPA and Placement, providing key insights into their relationship.

**Model Performance:**

Applied Logistic Regression to classify placement outcomes.

Achieved an accuracy score of 85% on test data.

Model performance metrics:

Precision: 82% (class 0) and 89% (class 1).

Recall: 90% (class 0) and 80% (class 1).

F1-Score: 86% (class 0) and 84% (class 1).

**Logistic Regression model** provides:

High accuracy in classifying placement outcomes.

Balanced precision, recall, and F1-scores, making it a reliable model for binary classification tasks.

**Future Enhancements**

Explore advanced classification techniques, such as Decision Trees or Random Forests, for improved accuracy.

Investigate feature engineering to include additional variables influencing placement outcomes.

Implement cross-validation for robust model evaluation.
