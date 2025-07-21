# Heart-Disease-Prediction
Data Science Project
This project focuses on predicting the presence of heart disease using a dataset containing various health parameters. The goal is to build a classification model that can accurately predict whether a patient has heart disease based on their medical information.

Dataset
The dataset used in this project is the Heart Disease Dataset, which includes the following features:

age: Age of the patient
sex: Sex of the patient (1 = male, 0 = female)
cp: Chest pain type (0-3)
trestbps: Resting blood pressure (mm Hg)
chol: Serum cholesterol (mg/dl)
fbs: Fasting blood sugar (> 120 mg/dl)
restecg: Resting electrocardiographic results (0-2)
thalach: Maximum heart rate achieved
exang: Exercise-induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: The slope of the peak exercise ST segment (0-2)
ca: Number of major vessels (0-3) colored by flourosopy
thal: Thallium stress test result (1 = normal, 2 = fixed defect, 3 = reversable defect)
target: Diagnosis of heart disease (1 = present, 0 = absent)
Project Steps
Data Loading and Understanding: Load the dataset and perform initial exploration to understand its structure and features.
Exploratory Data Analysis (EDA): Analyze the relationships between features and the target variable using visualizations and statistical methods.
Data Preprocessing: Prepare the data for model training, which may include handling missing values, scaling, and encoding categorical features.
Model Fitting: Train different classification models to predict heart disease. In this project, we specifically used:
Logistic Regression
Random Forest
Model Evaluation: Evaluate the performance of the trained models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
Gradio Interface: Build a user-friendly interface using Gradio to allow interactive predictions based on user input.
How to Run
Clone the repository.
Install the required libraries: pip install numpy pandas matplotlib seaborn scikit-learn gradio
Run the Jupyter notebook.
The Gradio interface will launch, allowing you to input patient data and get a heart disease prediction.
Results
The project includes the evaluation results for the trained models, demonstrating their accuracy and other performance metrics.

Future Work
Explore other classification algorithms.
Perform hyperparameter tuning to improve model performance.
Investigate feature engineering techniques.
Deploy the model as a web application for wider access.
