# 📑 Notebooks: Dataset & Model Details

## 📊 Dataset Information

Each dataset used in this project contains medical parameters to predict different diseases. Below is an overview of the datasets:

- Diabetes Dataset (data/diabetes.csv)

  - Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree, Age

  - Target: 1 (Diabetic) or 0 (Not Diabetic)

- Heart Disease Dataset (data/heart_disease.csv)

  - Features: Age, Sex, Chest Pain Type, Blood Pressure, Cholesterol, Blood Sugar, ECG Results, Heart Rate, Angina, etc.

  - Target: 1 (Heart Disease) or 0 (No Heart Disease)

- Lung Cancer Dataset (data/lung_cancer.csv)

  - Features: Gender, Age, Smoking, Yellow Fingers, Anxiety, Fatigue, Coughing, Chest Pain, etc.

  - Target: 1 (Has Cancer) or 0 (No Cancer)

- Parkinson's Disease Dataset (data/parkinsons.csv)

  - Features: Various voice-based metrics such as MDVP (Fo, Fhi, Flo), Jitter, Shimmer, HNR, NHR, D2, PPE

  - Target: 1 (Parkinson’s) or 0 (No Parkinson’s)

- Thyroid Disease Dataset (data/thyroid.csv)

  - Features: Age, Sex, TSH Level, T3 Level, TT4 Level, On Thyroxine

  - Target: 1 (Has Thyroid Disease) or 0 (No Thyroid Disease)


## 🧠 Model Training & Performance

Each model was trained using different Machine Learning algorithms, including:

- Diabetes: Logistic Regression / Decision Tree / Random Forest

- Heart Disease: Logistic Regression / SVM / Random Forest

- Lung Cancer: Random Forest / Decision Tree

- Parkinson’s Disease: Support Vector Machine (SVM)

- Thyroid Disease: Naïve Bayes / Decision Tree

Performance Metrics Used:

- Accuracy

- Precision & Recall

- F1 Score

- Confusion Matrix

All training and testing were performed in Jupyter Notebooks, which are available in the notebooks/ folder.

## 📂 Folder Structure

notebooks/

│── diabetes_disease.ipynb               # Training & Testing for Diabetes Prediction

│── heart_disease.ipynb                  # Training & Testing for Heart Disease Prediction

│── lung_cancer.ipynb                    # Training & Testing for Lung Cancer Prediction

│── parkinsons_disease.ipynb             # Training & Testing for Parkinson’s Prediction

│── thyroid_disease.ipynb                # Training & Testing for Thyroid Prediction

│── README.md                            # Dataset & Model Details


## 🔍 How to Use the Notebooks

1. Open the desired .ipynb file in Jupyter Notebook.

2. Run each cell to preprocess the data, train models, and evaluate performance.

3. Modify hyperparameters or try different ML algorithms to improve accuracy.
