🚀 3-Tier Banking App Deployment on AWS EKS using DevSecOps
A production-grade simulation of a secure, scalable, and automated CI/CD pipeline deploying a Java-based 3-tier banking application to AWS EKS using GitOps and monitoring tools.

🛠️ Tech Stack
Source Control: GitHub

CI/CD Pipeline: Jenkins, ArgoCD (GitOps)

Security: SonarQube, Trivy, OWASP Dependency-Check

Infrastructure: AWS EKS, Terraform, Docker, Helm

Monitoring: Prometheus & Grafana

✅ Key Features
Automated CI/CD pipeline with version-controlled deployments using GitOps

Static Code & Image Scanning integrated into Jenkins pipeline

Zero Downtime Deployments on Kubernetes (EKS)

Live Monitoring & Alerting using Grafana dashboards

Email Notifications on build and deployment status

📷 Preview

End-to-End Pipeline: Build → Scan → Push → Deploy → Monitor

⚙️ Project Highlights
Configured Jenkins master/agent architecture on EC2

Deployed ArgoCD for GitOps-style delivery to EKS

Integrated SonarQube & Trivy in CI pipeline for quality and security

Set up Prometheus & Grafana for cluster and app observability

Provisioned infrastructure using Terraform for repeatability

📌 About This Project
This project replicates enterprise DevSecOps workflows. It’s designed as a hands-on implementation to mirror production environments, built independently using real AWS infrastructure for deep learning and demonstration.

🧹 Clean-Up
eksctl delete cluster --name=bankapp --region=us-west-1
