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
We use the Heart Failure Clinical Records Dataset available from the https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction. It contains 918 records with 11 features and 1 target.

1. Age: age of the patient [years]

2. Sex: sex of the patient [M: Male, F: Female]

3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]

4. RestingBP: resting blood pressure [mm Hg]

5. Cholesterol: serum cholesterol [mm/dl]

6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]

7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or 
definite left ventricular hypertrophy by Estes' criteria]

8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]

9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]

10. Oldpeak: oldpeak = ST [Numeric value measured in depression]

11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

12. HeartDisease: output class [1: heart disease, 0: Normal]
