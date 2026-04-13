# 🚀 Wanderlust: End-to-End DevSecOps CI/CD Pipeline

<div align="center">
  <img src="https://github.com/krishnaacharyaa/wanderlust/assets/116620586/17ba9da6-225f-481d-87c0-5d5a010a9538" alt="Wanderlust Banner" width="100%">
</div>

---

## 📌 Project Overview

Wanderlust is a production-grade MERN stack travel application transformed into a robust **DevSecOps Case Study**.

This project implements a **Shift-Left Security model**, ensuring that every code change is:

* Audited
* Scanned for vulnerabilities
* Containerized before reaching production

---

## 🏗️ System Architecture & Workflow

## 🖼️ Image Add Karo

<!-- Add Architecture Diagram Here -->

---

## 🛡️ DevSecOps Pipeline Features

| Stage               | Tool                   | Purpose                                         |
| ------------------- | ---------------------- | ----------------------------------------------- |
| CI/CD Orchestration | Jenkins                | Automates build, test, and deployment lifecycle |
| SAST                | SonarQube              | Detects bugs, vulnerabilities, and code smells  |
| SCA                 | OWASP Dependency-Check | Scans third-party libraries for vulnerabilities |
| Container Security  | Trivy                  | Detects CVEs and misconfigurations in images    |
| Orchestration       | AWS EKS                | Manages scalable container deployments          |
| Observability       | Prometheus & Grafana   | Real-time monitoring and alerting               |

---

## 🚀 Deployment Workflow

### 1. Infrastructure (IaC)

```bash
cd terraform
terraform init
terraform apply -auto-approve
```

### 2. CI/CD Trigger

* Developer pushes code to GitHub
* Jenkins triggers pipeline via webhook

### 3. Security Gates

Pipeline executes:

* SAST (SonarQube)
* SCA (Dependency Check)
* Container Scan (Trivy)

⚠️ Pipeline fails automatically if **critical vulnerabilities** are found

### 4. Deployment

* Docker images pushed to **Amazon ECR**
* Application deployed to **AWS EKS using Helm**

---

## 🖼️ Image Add Karo

<!-- Add Jenkins Pipeline Screenshot Here -->

---

## 🖼️ Image Add Karo

<!-- Add SonarQube Report Screenshot Here -->

---

## 🛠️ Tech Stack

**Cloud:**
AWS (EC2, EKS, S3, IAM, VPC)

**DevOps:**
Docker, Jenkins, Terraform, Ansible, Git, GitHub

**Security:**
SonarQube, Trivy, OWASP Dependency-Check

**Monitoring:**
Prometheus, Grafana

**Application:**
Node.js, Express.js, React, MongoDB

---
