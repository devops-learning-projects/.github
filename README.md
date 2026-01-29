# 🛒 RoboShop – Cloud Native DevSecOps Project

## 📌 Overview
RoboShop is a microservices-based e-commerce application implemented using modern **DevSecOps practices** on AWS.  
This organization contains infrastructure, CI/CD, security, and application repositories for the RoboShop project.

---

## 🏗️ Architecture
- AWS VPC with public & private subnets
- Bastion host & NAT Gateway
- EKS cluster for container orchestration
- ALB / NLB for traffic management
- Route53 & ACM for DNS and TLS

---

## ⚙️ Infrastructure & Automation
- Terraform for Infrastructure as Code
- Ansible for configuration management
- Linux & Shell scripting for automation

---

## 🔁 CI/CD Pipeline
- GitHub Actions / Jenkins
- Self-hosted GitHub runners
- Docker image build & push
- Kubernetes deployment using Helm

---

## 🔐 Security
- HashiCorp Vault for secrets management
- IAM least privilege access
- Secure networking (private subnets)
- DevSecOps best practices (shift-left security)

---

## 📊 Observability
- Prometheus & Grafana (metrics)
- NewRelic
- ELK Stack (logs & monitoring)

