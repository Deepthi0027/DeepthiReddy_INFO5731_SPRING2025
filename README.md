# GCP App Engine Deployment

This is a simple Flask-based web application that can be deployed on **Google Cloud App Engine**.

## 🚀 Deployment Steps

### 1️⃣ Install GCP SDK & Authenticate
```sh
gcloud auth login
gcloud config set project [YOUR_PROJECT_ID]
```

### 2️⃣ Enable App Engine
```sh
gcloud app create --region=us-central
```

### 3️⃣ Deploy the Application
```sh
gcloud app deploy
```

### 4️⃣ Open the Application
```sh
gcloud app browse
```

## 🛠 Project Structure
```
/gcp_app_engine_project
│── app.yaml
│── main.py
│── requirements.txt
│── templates/
│   ├── index.html
│── README.md
```

### Enjoy your deployed app! 🎉
