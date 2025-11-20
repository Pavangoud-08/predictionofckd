💡 Prediction of Chronic Kidney Disease Using Machine Learning

This project focuses on developing a Machine Learning-based Chronic Kidney Disease (CKD) prediction system capable of identifying early signs of CKD using clinical patient data. The system uses data preprocessing, feature engineering, and classification algorithms—primarily the Random Forest model—to classify whether a patient has CKD or not.

Early detection of CKD helps prevent severe kidney damage and improves patient outcomes. This project aims to support healthcare professionals through an automated, accurate, and efficient CKD prediction tool.

📌 Project Features
🔬 Machine Learning Techniques

Random Forest (Primary Model)

Support Vector Machine

Decision Trees

XGBoost

Hyperparameter tuning (Grid Search / Randomized Search)

🩺 Medical Features Used

19+ clinical parameters, including:

Serum Creatinine

Blood Urea

Haemoglobin

Blood Pressure

Blood Glucose Random

Sodium, Potassium

Specific Gravity

Albumin, Sugar

Diabetes Mellitus, Hypertension

Anemia, Appetite, Pedal Edema

🛠 Technologies Used
Programming & Frameworks

Python

Flask / Django

Jupyter Notebook / Google Colab

Libraries

Scikit-learn

Pandas, NumPy

Matplotlib, Seaborn

Database

MySQL / PostgreSQL / SQLite

📊 System Architecture

The workflow includes:

Data Collection

Data Preprocessing

Feature Selection

Model Training

Evaluation

Prediction

Deployment

🧪 Results

The CKD Prediction System was evaluated through multiple machine learning models, and the Random Forest Classifier produced the best results.

✅ Overall Model Performance

Accuracy: 93%

Precision: High

Recall: High

F1-Score: Balanced performance

ROC-AUC: Strong class separability

📈 Accuracy Graph

Shows the model’s accuracy during training and testing phases, confirming stable learning behavior without overfitting.

📉 ROC Curves

ROC curves were generated for both:

Random Forest

XGBoost

Both models achieved high AUC values, with Random Forest performing slightly better in distinguishing CKD vs Non-CKD classes.

🔍 Predicted Output Example

A sample prediction demonstrates the system correctly classifying a patient’s clinical parameters as “CKD Present” or “CKD Not Present.”

✔️ Key Observations

Serum Creatinine, Hemoglobin, and Blood Urea showed strong influence on model prediction.

Feature selection helped improve the accuracy and reduce noise.

The model handled missing values effectively after preprocessing.

Performance remained stable even when evaluated with cross-validation.

🔬 Conclusion from Results

The system proves to be:

Accurate (93%)

Reliable

Consistent

Clinically meaningful

These results confirm that the ML-based CKD prediction system can be used as an early diagnosis support tool in healthcare environments.

📂 Dataset Information

Records: 400

Features: 26 total, 19 used after preprocessing

Contains clinical and categorical medical parameters

Preprocessed using scaling, encoding, and missing value imputation

🖥️ System Modules

Preprocessing Module

Feature Engineering Module

Model Training Module

Prediction Module

Results & Reports Module

Deployment Module
