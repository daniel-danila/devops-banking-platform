# devops-banking-platform
Enterprise DevOps platform — Kubernetes, Oracle DB, CI/CD, Terraform, Monitoring
# DevOps Banking Platform 

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

> Enterprise-grade DevOps platform built on Oracle Linux, Kubernetes and Oracle DB.

CI/CD Pipeline
Jenkins | GitHub Actions | GitLab CI
|
Kubernetes Cluster
Spring Boot API | Tomcat | JBoss
|
Oracle DB 26ai
|
Infrastructure as Code
Terraform (OCI | AWS | Azure) | Ansible
|
Observability
Dynatrace | Prometheus | Grafana

## Tech Stack

| Category | Technologies |
|---|---|
| Container Orchestration | Kubernetes, Podman, Docker |
| CI/CD | Jenkins, GitHub Actions, GitLab CI/CD |
| Infrastructure as Code | Terraform (OCI, AWS, Azure), Ansible |
| App Servers | Oracle WebLogic, Tomcat, JBoss/WildFly |
| Database | Oracle DB 23ai |
| Monitoring | Dynatrace, Prometheus, Grafana, Zabbix |
| Scripting | Bash, Python, PowerShell |
| Cloud | Oracle OCI, AWS, Azure |

## Project Structure
devops-banking-platform/
├── app/                    # Spring Boot REST API
├── docker/                 # Dockerfile
├── k8s/                    # Kubernetes manifests
├── jenkins/                # Jenkinsfile
├── terraform/              # IaC - OCI, AWS, Azure
├── ansible/                # Configuration playbooks
├── scripts/                # Bash + Python automation
├── monitoring/             # Prometheus + Grafana
└── docs/                   # Architecture diagrams

## Roadmap

- [x] Repository structure
- [ ] Spring Boot REST API + Oracle DB 23ai
- [ ] Kubernetes manifests + deploy
- [ ] Dockerfile + container build
- [ ] Jenkins CI/CD pipeline
- [ ] GitHub Actions workflow
- [ ] Terraform OCI infrastructure
- [ ] Ansible playbooks
- [ ] Prometheus + Grafana monitoring
- [ ] Dynatrace APM integration
- [ ] Multi-cloud Terraform (AWS + Azure)

## Author

Daniel Danila
GitHub: https://github.com/daniel-danila
