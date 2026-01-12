# Rockshaver API Docker Tests

![CI](https://github.com/007will/Rockshaver-API-Docker-Tests/actions/workflows/ci.yml/badge.svg)

API test suite designed to run inside Docker containers for isolated integration and contract testing. Contains scripts to start dependent services, run contract/contract-tests, and produce machine-readable artifacts for CI.

Quickstart
- Start containers: `docker-compose up --build -d`
- Run tests: `npm ci && npm run test:ci`

What to review
- Docker-based test harness, contract/contract-tests, CI integration.

Author: José Willams — https://github.com/007will
# 🧪 Rockshaver API – Dockerized Automated Tests

![API Testing](https://img.shields.io/badge/API-Testing-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED)
![QA](https://img.shields.io/badge/Quality-Assurance-green)
![CI Ready](https://img.shields.io/badge/CI%2FCD-Ready-brightgreen)

## 📌 Overview

This repository contains a **Dockerized API Test Automation project**, designed to demonstrate **QA Engineering best practices**, environment isolation, and readiness for **CI/CD pipelines**.

The main goal is to showcase:

- Automated API testing in an isolated environment  
- Docker usage for consistent execution  
- Professional QA project structure  
- Easy local and CI execution  

---

## 🧱 Project Architecture

- Automated API tests
- Fully containerized execution
- Clean and maintainable structure
- CI/CD ready (GitHub Actions, Azure DevOps, GitLab CI)

---

## 📁 Repository Structure

```bash
Rockshaver-API-Docker-Tests/
├── tests/                 # Automated API test cases
├── docker/
│   └── Dockerfile         # Test container definition
├── reports/               # Test execution reports and evidence
├── .env.example           # Environment variables example
├── docker-compose.yml     # Container orchestration
├── package.json           # Dependencies and scripts (if applicable)
└── README.md              # Project documentation

🚀 Requirements

To run this project, you only need:

Docker

Docker Compose

👉 No local installation of Node, Java, or test frameworks is required.

⚙️ Setup

Clone the repository:

git clone https://github.com/007will/Rockshaver-API-Docker-Tests.git
cd Rockshaver-API-Docker-Tests


(Optional) Configure environment variables:

cp .env.example .env

▶️ Running the Tests
Run everything using Docker Compose
docker-compose up --build


This command will:

Build the test image

Start the container

Execute the API test suite automatically

Generate logs and reports

🧪 Test Coverage

HTTP status code validation

Response body validation

Positive and negative scenarios

API contract validation

Realistic API test scenarios

📊 Reports and Evidence

After execution:

Execution logs are available in the terminal

Test evidence can be stored in the reports/ folder

Ready for integration with Allure, HTML Reports, or similar tools

🔄 CI/CD Integration

This project is structured for seamless integration with:

GitHub Actions

Azure DevOps Pipelines

GitLab CI

A pipeline only needs to execute:

docker-compose up --build

🎯 Portfolio Value

This repository demonstrates:

QA Engineer mindset

API test automation skills

Docker as a technical differentiator

Clean documentation and maintainable structure

👤 Author

José Willams
Quality Assurance • Test Automation • API Testing • DevOps

🔗 GitHub: https://github.com/007will

🔗 LinkedIn: https://linkedin.com/in/007will

⭐ Project created with a strong focus on quality, automation, and professional best practices.


---

## 3️⃣ Como usar esse projeto para valorizar sua homepage

Na **sua página principal do GitHub**, recomendo:

### 🔥 Destaque explícito
```md
## 🚀 Featured Projects

🔹 **Rockshaver API – Dockerized Tests**  
Automated API testing project using Docker, focused on QA Engineering and CI/CD readiness.  
👉 https://github.com/007will/Rockshaver-API-Docker-Tests
