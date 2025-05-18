3-Tier Banking Application Deployment on AWS EKS Using DevSecOps
This project simulates a production-grade deployment of a secure, scalable, and automated CI/CD pipeline for a Java-based 3-tier banking application. It uses DevSecOps practices to deploy to AWS EKS with GitOps-based delivery and integrated monitoring.

Tech Stack
Source Control: GitHub

CI/CD Pipeline: Jenkins, ArgoCD (GitOps)

Security Tools: SonarQube, Trivy, OWASP Dependency-Check

Infrastructure & Orchestration: AWS EKS, Terraform, Docker, Helm

Monitoring & Observability: Prometheus, Grafana

Key Features
Automated CI/CD pipeline with GitOps-driven deployment using ArgoCD

Static code analysis and container image scanning integrated into Jenkins

Zero-downtime deployments on Kubernetes (EKS)

Real-time monitoring and alerting with Grafana dashboards

Email notifications for build and deployment status

Pipeline Workflow
End-to-end flow: Build → Scan → Push → Deploy → Monitor

Project Highlights
Set up Jenkins in a master-agent architecture on EC2

Deployed ArgoCD for GitOps-style delivery to EKS

Integrated SonarQube and Trivy into the CI pipeline for code quality and security

Configured Prometheus and Grafana for cluster and application observability

Used Terraform to provision infrastructure, ensuring repeatability and scalability

About the Project
This project replicates enterprise-level DevSecOps workflows and is designed to mirror real-world production environments. It was independently built using actual AWS infrastructure to support hands-on learning and demonstration of modern CI/CD practices.
