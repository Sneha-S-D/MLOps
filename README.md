
# Kidney-Disease-Classification-MLflow-DVC

## Tech Stack & Tools

* **Python** (Deep Learning, Data Preprocessing)
* **TensorFlow / Keras** – Model building
* **MLflow** – Experiment tracking, model logging, production-grade tracking
* **DVC (Data Version Control)** – Lightweight pipeline orchestration & experiment tracking
* **Docker** – Containerization for deployment
* **GitHub Actions** – CI/CD automation
* **AWS (EC2, ECR)** – Cloud deployment infrastructure

---

## Project Workflow

1. **Configuration Management** – `config.yaml`, `params.yaml`
2. **Entity & Component Updates** – Define data entities and ML components
3. **Pipeline Orchestration** – Update pipelines in `main.py` and `dvc.yaml`
4. **Experiment Tracking** – MLflow logging with local/DagsHub tracking URI
5. **Version Control** – DVC for dataset, pipeline, and reproducibility
6. **Deployment**

   * Dockerize the application
   * Push image to AWS ECR
   * Deploy on AWS EC2 via GitHub Actions

---

## Features

* End-to-end **Kidney Disease Classification** pipeline
* **Experiment tracking** (MLflow + DagsHub)
* **Pipeline reproducibility** (DVC)
* **Cloud-native deployment** using AWS, Docker, GitHub Actions

---

