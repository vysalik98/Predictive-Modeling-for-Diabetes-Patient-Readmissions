## Predictive-Modeling-for-Diabetes-Patient-Readmissions

### Project Overview   
This project focuses on predicting hospital readmissions within a 30-day period for diabetic patients. Using a dataset with 101,766 records and 50 attributes, we performed data preprocessing, exploratory data analysis (EDA), and implemented machine learning algorithms to build predictive models.

### Data Description
The dataset contains 101,766 records and 50 attributes, including:

Numeric attributes: 12
Categorical attributes: 30
Text attributes: 4
Boolean attributes: 3

#### Key attributes include:   

encounter_id: Unique identifier for each encounter
patient_nbr: Unique identifier for each patient
age
race
admission_type_id
time_in_hospital
num_lab_procedures
num_procedures
num_medications
number_outpatient
number_emergency
number_inpatient
diag_1, diag_2, diag_3: Diagnoses
diabetesMed: Indicates if diabetes medication was prescribed
readmitted: Target variable (readmission within 30 days)

#### Setup and Installation
Clone the repository:

#### Data Preprocessing

1. Handling Missing Values:
2. Data Cleaning:
3. Feature Engineering:


#### Exploratory Data Analysis

1. Histograms for key numerical variables.
2. Bar charts for categorical variables.
3. Scatter plots to examine relationships between continuous variables.
4. Correlation heatmap to identify strong positive/negative correlations.

#### Model Implementation

Implemented and compared two machine learning models:

1. Logistic Regression
2. Random Forest

Preprocessing steps before modeling:

Data splitting: 80% training, 20% testing.
One-hot encoding for categorical variables.
Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
AUC-ROC score

#### Results
The Random Forest model achieved the highest performance with an accuracy score of 65%. Key factors influencing readmission included the number of diagnoses, hospital stays, lab procedures, and medications.

#### Conclusion
This project demonstrated the potential of machine learning to predict hospital readmissions for diabetic patients. The insights gained can help healthcare providers identify high-risk patients and implement targeted interventions to reduce readmission rates.
