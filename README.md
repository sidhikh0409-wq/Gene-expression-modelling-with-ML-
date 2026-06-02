# Gene-expression-modelling-with-ML-
**Objective**
<br>
The objective of this project is to develop and compare multiple machine learning regression models for predicting continuous gene expression outcomes, including log Fold Change (logFC) and B-statistic (log-odds of differential expression). Rather than classifying genes as significant or non-significant, this approach treats differential expression analysis as a regression problem, enabling quantitative prediction of expression changes and gene significance scores.
<br>

**Dataset**

<br>

**The dataset contains differential gene expression statistics generated from transcriptomic analysis.**

<br>

**Columns:**
logFC – Log Fold Change in gene expression
<br>

logFC – Log Fold Change in gene expression
<br>
AveExpr – Average expression level
<br>
t – Moderated t-statistic
<br>
P.Value – Raw p-value
<br>.
Removed non-numeric identifier column (name)
<br>
Selected a continuous target variable
<br>
logFC (gene expression change) remaining statistical features were used as predictors checked for missing values and outliers standardized features where required
<br>

**Train-Test Split**
<br>
**80% Training Set**
<br>
Model training
<br>
Hyperparameter tuning
<br>
Cross-validation
<br>
**20% Testing Set**
<br>
Independent performance evaluation
<br>
Assessment of model generalization
<br>
Regression Models Evaluated
<br>

**The following machine learning algorithms were implemented and compared:**
<br>
Linear Regression
<br>
Random Forest Regressor
<br>
Decision Tree Regressor
<br>
Gradient Boosting Regressor
<br>
Support Vector Regressor (SVR)
<br>
K-Nearest Neighbors (KNN) Regressor
<br>
Model Evaluation Metrics
<br>

**Model performance was assessed using:**
<br>
R² Score (Coefficient of Determination)
<br>
Mean Squared Error (MSE)
<br>
Root Mean Squared Error (RMSE)
<br>

These metrics were used to compare predictive accuracy and model robustness.
<br>

**Workflow**
<br>
  Import and preprocess differential expression dataset
<br>
  Select target variable (logFC )
<br>
  Split data into training and testing sets
<br>
  Train multiple regression models
<br>
  Evaluate model performance using regression metrics
<br>
  Compare model predictions
<br>
  Identify the best-performing regression algorithm
<br>
  Interpret feature contributions to gene expression outcomes
