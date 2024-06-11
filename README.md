# **ICU Requirement Prediction for COVID-19 Patients in Brazil**
This is the web deployment of the ICU requirement prediction model for COVID-19 patients in Brazil. You can access the web application here: ICU Requirement Prediction

**About**
The dataset used in this project is publicly available on the Kaggle website. It consists of data related to COVID-19 patients in Brazil, with the goal of predicting whether a patient will require admission to the Intensive Care Unit (ICU). The dataset includes various attributes related to patient demographics, medical history, and current health status.


**Dataset**
The dataset comprises records of COVID-19 patients and includes the following attributes:

**Demographic:**
Sex: Male or Female (Nominal)
Age: Age of the patient (Continuous)

**Medical History:**
Pre-existing Conditions:
Diabetes: Whether the patient has diabetes (Nominal)
Hypertension: Whether the patient has hypertension (Nominal)
Cardiovascular Disease: Whether the patient has any cardiovascular disease (Nominal)
Respiratory Disease: Whether the patient has any respiratory disease (Nominal)
Cancer: Whether the patient has cancer (Nominal)
Obesity: Whether the patient is obese (Nominal)
Current Health Status:
Symptoms and Vital Signs:
Fever: Whether the patient has a fever (Nominal)
Cough: Whether the patient has a cough (Nominal)
Shortness of Breath: Whether the patient experiences shortness of breath (Nominal)
Oxygen Saturation: Oxygen saturation level (Continuous)
Heart Rate: Heart rate (Continuous - Considered continuous due to a large number of possible values)
Blood Pressure:
Systolic BP: Systolic blood pressure (Continuous)
Diastolic BP: Diastolic blood pressure (Continuous)
Predict Variable (Desired Target):
ICU Admission: Whether the patient requires ICU admission (Binary: "1" means "Yes", "0" means "No")

**Methodology**
Data Preprocessing:
Handling missing values
Encoding categorical variables
Normalizing continuous variables

**Model Building:**
Various machine learning algorithms were evaluated, including Logistic Regression, Decision Tree, and Random Forest classifiers.
Hyperparameter tuning was performed to optimize model performance.
Evaluation Metrics:
Accuracy
Precision
Recall
F1 Score
ROC-AUC
Deployment:

The dataset used in this project can be found on Kaggle: Brazil COVID-19 Dataset
