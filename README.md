# Heart-Failure-Prediction

### Heart Failure Prediction
This project aims to predict the risk of heart failure using machine learning algorithms and neural networks based on clinical data. It serves as a practical implementation of data preprocessing, model training, evaluation, and visualization using Python, scikit-learn and tensorflow.

### Overview
This repository demonstrates how machine learning can be used to predict heart failure events. We use a labeled dataset containing various clinical features to train and evaluate classification models. The project includes:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Model training (e.g., Logistic Regression, Random Forest, etc.)

Evaluation metrics (accuracy, precision, recall, F1-score, ROC AUC)

Visualizations (confusion matrix, ROC curve).

### Dataset
We use the Heart Failure Clinical Records Dataset available from the UCI Machine Learning Repository](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction. It contains 918 records with 11 features and 1 target.

Age: age of the patient [years]

Sex: sex of the patient [M: Male, F: Female]

ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]

RestingBP: resting blood pressure [mm Hg]

Cholesterol: serum cholesterol [mm/dl]

FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]

RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or 
definite left ventricular hypertrophy by Estes' criteria]

MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]

ExerciseAngina: exercise-induced angina [Y: Yes, N: No]

Oldpeak: oldpeak = ST [Numeric value measured in depression]

ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

HeartDisease: output class [1: heart disease, 0: Normal]
