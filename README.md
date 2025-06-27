Project Title
Microsoft: Classifying Cybersecurity Incidents with Machine Learning**

Skills Gained
- Data Preprocessing & Feature Engineering  
- Classification Techniques  
- Model Evaluation (Macro-F1 Score, Precision, Recall)   
- Model Optimization & Benchmarking  
- Cybersecurity Incident Analysis  

Domain
Cybersecurity | Machine Learning | Threat Intelligence


Problem Statement

As a Data Scientist at Microsoft, you are tasked with enhancing SOC (Security Operations Center) efficiency by developing a machine learning model to classify cybersecurity incidents using the GUIDE dataset. The objective is to build a robust classification model that predicts whether an incident is a True Positive (TP), Benign Positive (BP), or False Positive (FP)—supporting incident triage automation and threat prioritization.


 Approach & Methodology

 1.  Data Exploration
- Understand structure, types, and distribution from `train.csv`
- Conduct Exploratory Data Analysis (EDA) to uncover patterns and check for imbalances

 2.  Data Preprocessing
- Handle missing values (impute or drop)
- Encode categorical features using label or one-hot encoding
- Normalize numeric features where needed
- Feature Engineering 

 3. Model Development
- Models used:
  - Logistic Regression
  - Random Forest

 4. Model Evaluation
- Metrics: **Macro-F1 Score**, **Precision**, **Recall**
- Evaluate across TP, BP, and FP labels


 5. Final Testing
- Evaluate on `test.csv` and compare with baseline models
- Report macro-F1, precision, and recall




