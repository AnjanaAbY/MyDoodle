**DRUG CLASSIFICATION MODEL**

This repository contains code for building and evaluating different classification models for drug classification based on historical data of patients and their responses to different medications.

**Overview:**

The code includes following key components:

**1. Data Loading and Exploration**:
      Loading the dataset('drug200.csv') and exploring it's basics statistics information.

**2. Data Preprocessing**:
      Null values in the dataset are identified, and the overall structure of the data is examined.
      Label encoding for categorical values(eg:Sex,BP,Cholesterol)

**3.Model Training and Evaluation**:
      Building and training models using Logistic Regression,Decision Tree,Random Forest,KNN,SVM and Naive Bayes classifiers.
      Evaluating the models using accuracy as a metric.

**4.Additional Metrics Calculation**:
      A function, calculate_additional_metrics, is defined to compute precision, recall, and F1-score for model evaluation.

**5.New Patient Prediction**:
      A new patient's data can be inputted into the training models for drug classification predictions. 

**File Structure:**

'drug200.csv' : Dataset file containing historical data of patients
