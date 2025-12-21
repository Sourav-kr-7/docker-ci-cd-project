# docker-ci-cd-project
End-to-end CI pipeline using GitHub Actions to build and validate a Dockerized Python application.

# 🚀 Docker CI/CD Project

![CI](https://github.com/Sourav-kr-7/docker-ci-cd-project/actions/workflows/docker-ci.yml/badge.svg)

A beginner-friendly yet production-style **DevOps project** that demonstrates how to build and validate a **Dockerized Python application** using **GitHub Actions CI pipeline**.

---

## 📌 Project Overview

This project showcases an **end-to-end Continuous Integration (CI) workflow** where a Python application is containerized using Docker and automatically built and executed whenever code is pushed to the `main` branch.

The goal of this project is to demonstrate **real-world DevOps fundamentals** such as containerization, CI automation, and pipeline debugging.

---

## 🛠️ Technologies Used

- 🐳 **Docker** – Containerization
- 🤖 **GitHub Actions** – CI automation
- 🐍 **Python** – Application logic
- 🧩 **YAML** – Workflow configuration
- 🌐 **Git & GitHub** – Version control

---

## ⚙️ How the CI Pipeline Works

1. Code is pushed to the `main` branch
2. GitHub Actions workflow is triggered automatically
3. Repository is checked out
4. Docker image is built
5. Docker container is executed
6. Application output is validated via logs

✔ Ensures consistent builds  
✔ Catches issues early  
✔ No manual intervention required  

---

## 📂 Project Structure

```text
docker-ci-cd-project/
│
├── app.py                         # Python application
├── Dockerfile                     # Docker build instructions
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
└── .github/
    └── workflows/
        └── docker-ci.yml          # GitHub Actions CI workflow


