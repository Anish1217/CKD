**Chronic Kidney Disease (CKD) Prediction**
Chronic Kidney Disease (CKD) is a critical health problem that can be effectively treated if detected in its early stages. This project leverages machine learning to predict CKD using attributes derived from various medical tests. The goal is to build and evaluate machine learning models that can provide accurate predictions and support early diagnosis.

Overview
This project investigates the attributes of medical test results to identify patterns that indicate chronic kidney disease. By analyzing these attributes, machine learning models are trained to classify whether a person is at risk for CKD.

**Dataset**
The dataset used contains 19 features related to medical tests, including blood pressure, glucose levels, and other biomarkers. These features were analyzed and preprocessed to ensure the best possible prediction results.

**Steps to Complete the Project**
Download the Dataset
Obtain a CKD-related dataset from reliable sources (e.g., Kaggle or UCI Machine Learning Repository).

Data Preprocessing
Clean the data by:

Handling missing values
Normalizing numerical features
Encoding categorical variables.
Exploratory Data Analysis (EDA)
Conduct a thorough analysis of the dataset to uncover trends and insights.

Model Training
Train the models (RF, SVM, and DT) on the preprocessed data.

**Performance Evaluation**
Evaluate the models using the following metrics:

Accuracy
F1 Score
Precision
Recall
Model Deployment
Save the best-performing model and integrate it into a Flask-based web application.

**Technologies Used**
Programming Language: Python
Libraries:
NumPy
Pandas
Scikit-learn
Matplotlib / Seaborn
Deployment:
Flask for building the web application.
