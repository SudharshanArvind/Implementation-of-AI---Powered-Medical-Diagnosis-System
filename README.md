# Implementation-of-AI---Powered-Medical-Diagnosis-System
This project is a Disease Prediction System that uses Machine Learning models to predict the likelihood of a person having a disease based on user-inputted medical details. The diseases covered in this project include:  

  - Diabetes
  - Heart Disease  
  - Lung Cancer  
  - Parkinson's Disease  
  - Thyroid Disease

The application is built using Streamlit for the web interface, and the trained models are stored as .sav files for predictions.


# 🚀 Features

- User-friendly Web Interface using Streamlit
- Multiple Disease Predictions
- Pre-trained Machine Learning Models for accurate predictions
- Simple Input Forms for entering medical details
- Instant Predictions with results displayed on-screen
- Secure & Fast Processing

# 🛠 Installation & Setup

## Prerequisites

Ensure you have Python 3.x installed along with the required dependencies.

## Clone the Repository

    git clone https://github.com/yourusername/disease-prediction.git
    cd disease-prediction

## Install Dependencies

    pip install -r requirements.txt

## Run the Streamlit App

    streamlit run app.py

This will start a local server, and you can access the app in your browser.

# 📁 Project Structure

disease-prediction/

│── 📂 app/                   # Streamlit Web App

│   ├── app.py                # Main Streamlit App

│── 📂 models/                 # Trained ML Models

│   ├── diabetes_model.sav

│   ├── heart_model.sav

│   ├── lung_model.sav

│   ├── parkinsons_model.sav

│   ├── thyroid_model.sav

│── 📂 data/                   # Datasets

│   ├── diabetes.csv

│   ├── heart_disease.csv

│   ├── lung_cancer.csv

│   ├── parkinsons.csv

│   ├── thyroid.csv

│── 📂 notebooks/              # Jupyter Notebooks (Training & Testing)

│   ├── diabetes_disease.ipynb

│   ├── heart_disease.ipynb

│   ├── lung_cancer.ipynb

│   ├── parkinsons_disease.ipynb

│   ├── thyroid_disease.ipynb

│── README.md                  # Project Documentation

│── requirements.txt            # Python Dependencies

# 📊 Model & Dataset Details

Each disease prediction model was trained on relevant medical datasets:
- Diabetes: diabetes.csv
- Heart Disease: heart disease.csv
- Lung Cancer: lung cancer.csv
- Parkinson's Disease: parkinsons.csv
- Thyroid Disease: thyroid.csv

The trained models are stored as:
- diabetes model.sav
- heart model.sav
- lung model.sav
- parkinsons model.sav
- thyroid model.sav

# 🖥 Usage Guide

1. Run the Streamlit app.

2. Select a disease from the dropdown menu.

3. Enter the required medical details.

4. Click on the Test Result button.

5. The app will display whether the person has the disease or not.


# 📷 Screenshots
![2](https://github.com/user-attachments/assets/1896fbdf-7cb1-4ca0-8116-6eb03ea9fd4a)
![1](https://github.com/user-attachments/assets/42683451-45c5-4fe2-b8a1-3c7f50baed8e)


# 📜 License

This project is licensed under the MIT License.
