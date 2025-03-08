# 🚀 Deployment Instructions

This guide provides steps to deploy the Disease Prediction System on Streamlit Cloud, Docker, or a Virtual Private Server (VPS).

## 📌 1. Deploying on Streamlit Cloud (Recommended)

Streamlit Cloud is the easiest way to deploy a Streamlit app.

### Steps to Deploy:

1. Push your project to GitHub.

2. Go to Streamlit Cloud.

3. Click Deploy an app and connect your GitHub repository.

4. Select app/app.py as the entry point.

5. Click Deploy – your app will be live!

### Updating the App:

- Any changes you push🚀 Deployment Instructions

This guide provides steps to deploy the Disease Prediction System on __Streamlit Cloud, Docker, or a Virtual Private Server (VPS).__

## 📌 1. Deploying on Streamlit Cloud (Recommended)

Streamlit Cloud is the easiest way to deploy a Streamlit app.

### Steps to Deploy:

1. Push your project to GitHub.

2. Go to Streamlit Cloud.

3. Click Deploy an app and connect your GitHub repository.

4. Select app/app.py as the entry point.

5. Click Deploy – your a to GitHub will automatically reflect in the deployed app.

## 📌 2. Deploying with Docker

You can containerize your app using Docker.

### Steps to Deploy with Docker:

1. Install Docker on your system.

2. Create a Dockerfile in the project root with the following content:

        FROM python:3.9
        WORKDIR /app
        COPY . /app
        RUN pip install -r requirements.txt
        CMD ["streamlit", "run", "app/app.py", "--server.port=8501", "--server.enableCORS=false"]

3. Build and run the container:

        er build -t disease-prediction .
        docker run -p 8501:8501 disease-prediction

4. Open [http://localhost:8501](http://localhost:8501) in your browser to access the app.

## 📌 3. Deploying on a Virtual Private Server (VPS)

You can deploy this project on AWS, Google Cloud, Azure, or DigitalOcean.

### Steps to Deploy on VPS:

1. Set up a Virtual Machine (VM) running Ubuntu.

2. Install Python and Streamlit:

        sudo apt update && sudo apt upgrade -y
        sudo apt install python3 python3-pip -y
        pip install streamlit

3. Clone the repository:

        git clone https://github.com/yourusername/disease-prediction.git
        cd disease-prediction
        pip install -r requirements.txt

4. Run the Streamlit app:

        streamlit run app/app.py --server.port=8501 --server.enableCORS=false

5. Access the app by opening [http://your-server-ip:8501](http://your-server-ip:8501) in your browser.


## 📌 4. Running the App Locally

If you don't want to deploy online, you can run the app locally:

    streamlit run app/app.py

This will start a local server, and you can access the app in your browser.


## 🎯 Conclusion

- For quick deployment → Use Streamlit Cloud.
- For containerized deployment → Use Docker.
- For full control → Use a VPS (AWS, GCP, Azure, DigitalOcean).

Let me know if you need further assistance! 🚀
