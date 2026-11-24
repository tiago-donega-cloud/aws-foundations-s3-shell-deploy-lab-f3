<div align="center">

# ☁️ AWS S3 Static Hosting & Shell Script Deployment Lab

**Automated React Front-End Build & Amazon S3 Synchronization Pipeline on Linux**

[![AWS](https://img.shields.io/badge/AWS-Amazon%20S3%20%7C%20AWS%20CLI%20%7C%20ECS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)]()
[![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Shell%20Script-FCC624?style=for-the-badge&logo=linux&logoColor=black)]()
[![React](https://img.shields.io/badge/Frontend-React%20%7C%20Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black)]()
[![Docker](https://img.shields.io/badge/Containers-Docker%20%7C%20Amazon%20ECR-2496ED?style=for-the-badge&logo=docker&logoColor=white)]()
[![Git](https://img.shields.io/badge/Version%20Control-Git%20%26%20GitHub-F05032?style=for-the-badge&logo=git&logoColor=white)]()

</div>

---

## 🗺️ Architecture & Workflow Flowchart

![AWS S3 Shell Script Deployment Flowchart](images/00-architecture-flowchart.jpg)

Practical cloud deployment automation built on a Linux environment, decoupling front-end static asset delivery from back-end API compute services. Modular Shell Scripts (`deploy.sh`, `react.sh`, and `s3.sh`) orchestrate production React/Vite builds and synchronize static artifacts directly to an Amazon S3 bucket configured for Static Website Hosting[cite: 15, 16, 18].

---

## 🛠️ Technologies & Tools

* **Cloud Infrastructure:** Amazon S3 (Static Website Hosting, Object Synchronization), Amazon EC2 / ECS, AWS Systems Manager (SSM), Amazon ECR[cite: 15, 16, 18, 19]
* **Operating System & Automation:** Linux (Ubuntu), Bash / Shell Scripting (`deploy.sh`, `react.sh`, `s3.sh`), AWS CLI v2 (`aws s3 sync`)[cite: 15, 16]
* **Front-End Build Toolchain:** React, Vite, Node.js / npm[cite: 15, 16]
* **Version Control & IDE:** Git, GitHub, Visual Studio Code

---

## 🧪 Execution & Validation Evidence

| Automated Shell Script Build & S3 Sync | Amazon S3 Bucket Object Verification |
| :---: | :---: |
| ![Shell Script Build and Sync](images/01-shell-script-build-and-sync.jpeg) | ![S3 Bucket Uploaded Objects](images/02-s3-bucket-uploaded-objects.jpeg) |

| Production Static Website Endpoint (Amazon S3) |
| :---: |
| ![BIA Application Running on S3](images/03-bia-app-running-on-s3.jpeg) |

---

## 📄 Full Technical Documentation

* 📋 [Access Detailed Lab Report (PDF)](docs/04-s3-static-deploy-documentation.pdf)

---

## 👤 Author

**Tiago Donega** — Cloud & DevOps Engineering  
[![GitHub](https://img.shields.io/badge/GitHub-tiago--donega--cloud-181717?style=flat-square&logo=github)](https://github.com/tiago-donega-cloud)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tiagodonega--cloud--aws-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/tiagodonega-cloud-aws)