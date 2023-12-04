**INSURANCE CHARGES PREDICTION**

This repository contains code for predicting insurance charges based on various features such as age, sex, smoker status, and others. The code uses different regression models and evaluates their performance.

**Steps:**

**1.Data Loading and Exploration:**

      The dataset is loaded from the provided CSV file('insurance.csv'), and basic descriptive statistics are displayed.
      Null values in the dataset are checked.

**2.Data Visualization:**

      Scatter plots and bar graphs are created to visualize the relationships between features (e.g., Age, Sex, Smoker) and insurance charges.
      Correlation plots are used to understand the relationships between numerical features.

**3.Data Preprocessing:**

      The 'region' column, deemed unnecessary, is dropped from the dataset.
      Label encoding is applied to 'sex' and 'smoker' columns.

**4.Model Training and Evaluation:**

      Linear Regression, Support Vector Regression (SVR), Decision Tree Regressor, and Random Forest Regressor models are trained.
      Mean Squared Error, Root Mean Squared Error, and R-squared Score are calculated to evaluate model performance.

**5.Model Comparison:**

      Linear Regression, SVR, Decision Tree, and Random Forest models are compared based on their performance metrics.
      The models aim to predict insurance charges given the input features.

**Files:**

insurance.csv: Dataset containing information about individuals and their insurance charges.
