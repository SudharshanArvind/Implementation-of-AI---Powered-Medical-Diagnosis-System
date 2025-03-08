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

│   ├── README.md              # Dataset & Model Details

│── 📂 assets/                 # Screenshots & UI Previews

│   ├── screenshot1.png        # Sample output screenshot

│   ├── screenshot2.png        # Additional UI previews

│── README.md                  # Project Documentation

│── requirements.txt            # Python Dependencies

# 📊 Model & Dataset Details

Each disease prediction model was trained on relevant medical datasets:
- Diabetes: data/diabetes.csv
- Heart Disease: data/heart disease.csv
- Lung Cancer: data/lung cancer.csv
- Parkinson's Disease: data/parkinsons.csv
- Thyroid Disease: data/thyroid.csv

The trained models are stored as:
- models/diabetes model.sav
- models/heart model.sav
- models/lung model.sav
- models/parkinsons model.sav
- models/thyroid model.sav


# 📷 Output Screenshots

The assets/ folder contains sample output screenshots showing how the app works.

Example output:


The image demonstrates how the user inputs medical parameters and receives an instant prediction. More screenshots can be added to showcase different disease predictions and app functionality.


# 🚀 Deployment Instructions

For details on deploying this project, refer to **[DEPLOYMENT.md](DEPLOYMENT.md)**


# 📜 License

This project is licensed under the MIT License.
