# 🚀 End-to-End MLOps for Sentiment Analysis | NLP | AWS | Docker | Kubernetes | CI/CD

A production-ready End-to-End MLOps project that automates the complete Machine Learning lifecycle for Sentiment Analysis using modern MLOps practices.

The project demonstrates how an NLP model can be developed, versioned, containerized, deployed on Kubernetes, monitored using Prometheus & Grafana, and automated with CI/CD pipelines.

---

## 📌 Project Overview

This project predicts the sentiment of a given text using an NLP pipeline and follows complete MLOps practices.

The objective was to build a scalable, reproducible and production-ready ML system instead of just training a model.

---

# 🏗 Architecture

```
User
   │
   ▼
Flask Web Application
   │
   ▼
Text Preprocessing
   │
   ▼
Vectorizer
   │
   ▼
MLflow Registered Model
   │
Prediction
   │
   ▼
Prometheus Metrics
   │
   ▼
Grafana Dashboard
```

---

# 🚀 Tech Stack

### Programming

- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy
- NLTK

### MLOps

- MLflow
- DVC
- DagsHub
- GitHub Actions
- Docker
- Kubernetes (EKS)

### Cloud

- AWS EC2
- AWS ECR
- AWS EKS
- AWS S3
- IAM

### Monitoring

- Prometheus
- Grafana

---

# ⚙ Features

✅ Automated NLP Pipeline

✅ Text Cleaning

✅ Stopword Removal

✅ Lemmatization

✅ Feature Engineering

✅ Model Training

✅ MLflow Experiment Tracking

✅ Model Registry

✅ DVC Pipeline

✅ Dockerized Deployment

✅ GitHub Actions CI/CD

✅ AWS ECR

✅ Kubernetes Deployment (Amazon EKS)

✅ Prometheus Monitoring

✅ Grafana Dashboard

---

# 📈 Monitoring

The application exposes custom Prometheus metrics.

- Total Requests
- Request Latency
- Prediction Count
- Endpoint Monitoring

Metrics Endpoint

```
/metrics
```

---

# ☁ AWS Services Used

- Amazon EC2
- Amazon ECR
- Amazon EKS
- Amazon S3
- IAM

---

# 🔄 CI/CD Pipeline

GitHub Push

↓

GitHub Actions

↓

Docker Build

↓

Push Image to Amazon ECR

↓

Deploy to Amazon EKS

↓

Application Live

↓

Prometheus Monitoring

↓

Grafana Dashboard

---

# 🧠 NLP Pipeline

Input Text

↓

Lowercase

↓

Remove Stopwords

↓

Remove Numbers

↓

Remove URLs

↓

Remove Punctuations

↓

Lemmatization

↓

Vectorization

↓

Prediction

---

# 📊 Model Management

- MLflow Experiment Tracking
- Model Registry
- Version Control
- Reproducible Pipeline

---

# 🐳 Docker

```
docker build -t sentiment-app .
docker run -p 5000:5000 sentiment-app
```

---

# ☸ Kubernetes

```
kubectl apply -f deployment.yaml
kubectl get pods
kubectl get svc
```


# 🎯 Learning Outcomes

✔ End-to-End MLOps

✔ CI/CD Automation

✔ AWS Deployment

✔ Model Versioning

✔ Monitoring

✔ Production Ready Deployment

✔ NLP Pipeline

✔ Kubernetes Deployment

---

# ⭐ Future Improvements

- FastAPI
- Auto Retraining
- Drift Detection
- Airflow Scheduling
- Terraform
- ArgoCD
- Helm Charts
