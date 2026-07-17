# 🚗 End-to-End MLOps Vehicle Insurance Pipeline

An industry-grade **MLOps project** that demonstrates the complete machine learning lifecycle — from data ingestion and model training to containerized deployment on **AWS EKS** with **CI/CD, DVC, MLflow, Prometheus, and Grafana** monitoring.

## ✨ Highlights

* 🔄 Automated ML pipeline using **DVC**
* 📊 Experiment tracking with **MLflow + DagsHub**
* 🐳 Containerized using **Docker**
* ☁️ Deployed on **AWS EKS (Kubernetes)**
* 🚀 CI/CD using **GitHub Actions**
* 📈 Monitoring with **Prometheus & Grafana**
* 🧪 Modular and production-ready codebase
* 📦 S3-backed artifact storage

---

## 🏗️ Architecture

```text
Data Source → DVC Pipeline → MLflow Tracking → Model Registry
        ↓
   Docker Image → Amazon ECR → Amazon EKS
        ↓
 Prometheus Monitoring → Grafana Dashboards
```

---

## 🛠️ Tech Stack

| Category            | Tools                   |
| ------------------- | ----------------------- |
| Language            | Python                  |
| ML                  | scikit-learn            |
| Experiment Tracking | MLflow, DagsHub         |
| Data Versioning     | DVC                     |
| Containerization    | Docker                  |
| Cloud               | AWS (S3, ECR, EKS, EC2) |
| CI/CD               | GitHub Actions          |
| Orchestration       | Kubernetes              |
| Monitoring          | Prometheus, Grafana     |

---

## 📂 Project Structure

```bash
├── src/
│   ├── data/
│   ├── feature_engineering/
│   ├── model/
│   ├── evaluation/
│   └── logger/
├── flask_app/
├── tests/
├── scripts/
├── dvc.yaml
├── params.yaml
├── requirements.txt
└── .github/workflows/ci.yaml
```

---

## ⚙️ Pipeline Stages

1. Data Ingestion
2. Data Preprocessing
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Model Registration
7. Docker Image Build
8. Push to Amazon ECR
9. Deploy to Amazon EKS
10. Monitor using Prometheus & Grafana

---

## 🚀 Local Setup

```bash
# Create environment
conda create -n atlas python=3.10
conda activate atlas

# Install dependencies
pip install -r requirements.txt

# Run DVC pipeline
dvc repro

# Start application
cd flask_app
python app.py
```

---

## 🐳 Docker

```bash
docker build -t vehicle-insurance-app:latest .
docker run -p 5000:5000 vehicle-insurance-app:latest
```

---

## ☁️ AWS Deployment

* Amazon S3 for artifact storage
* Amazon ECR for container registry
* Amazon EKS for Kubernetes deployment
* GitHub Actions for automated CI/CD

---

## 📈 Monitoring

### Prometheus

* Application metrics scraping
* Kubernetes service monitoring

### Grafana

* Real-time dashboards
* Infrastructure and application observability

---

## 📸 Dashboard Preview

*Add screenshots of Grafana dashboards, MLflow experiments, and EKS deployment here.*

---

## 🎯 Key Learnings

* Built a production-style MLOps workflow
* Implemented reproducible ML pipelines with DVC
* Tracked experiments using MLflow
* Automated deployment with GitHub Actions
* Deployed containers on Kubernetes (EKS)
* Set up end-to-end monitoring and observability

---

## 👨‍💻 Author

**Shubham Kumar**
B.Tech IT (2028) • KIET Ghaziabad

* LinkedIn: [www.linkedin.com/in/shubham-kumar-773a7b252](http://www.linkedin.com/in/shubham-kumar-773a7b252)
* GitHub: https://github.com/your-username

⭐ If you found this project useful, consider giving it a star!
