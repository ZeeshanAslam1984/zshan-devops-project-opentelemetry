# zshan-devops-project-opentelemetry

A comprehensive DevOps project demonstrating end-to-end observability using **OpenTelemetry**, deployed on **AWS** with **Kubernetes (EKS)**, **Terraform**, and **CI/CD pipelines**.

Built and maintained by **Zeeshan Aslam** as part of hands-on learning and real-world DevOps implementation.

## Overview

This project showcases:
- Distributed tracing with **OpenTelemetry Collector**
- Metrics and logs collection from microservices
- Infrastructure provisioning via **Terraform (AWS)**
- Deployment on **Amazon EKS**
- CI/CD automation using **GitHub Actions** (or Jenkins/GitLab CI — customize as needed)
- Cost-optimized, secure, and scalable cloud architecture

Ideal for DevOps engineers exploring observability, cloud automation, and modern application monitoring.

## Tech Stack

- **Observability**: OpenTelemetry, Prometheus, Jaeger (or Tempo), Grafana
- **Cloud**: AWS (EKS, EC2, ECR, IAM, VPC)
- **IaC**: Terraform
- **Containerization**: Docker
- **Orchestration**: Kubernetes (EKS)
- **CI/CD**: GitHub Actions / Jenkins / GitLab CI (configurable)

## Project Structure

├── infrastructure/ # Terraform modules for AWS provisioning
├── k8s/ # Kubernetes manifests (EKS deployments)
├── otel-config/ # OpenTelemetry Collector configurations
├── apps/ # Sample instrumented microservices (if included)
├── test/ # Tracetesting and validation scripts
├── .github/workflows/ # CI/CD pipelines (optional)
└── README.md
