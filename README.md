# Netflix-Styled Full Stack App

A full stack movie review application, deployed two ways to demonstrate the progression from manual deployment to modern DevOps practices.

## Documentation

- **[Manual Deployment](README-manual.md)** — Deployed manually on AWS EC2: self-hosted MongoDB, hand-built backend and frontend across three servers.
- **[Dockerized Deployment with CI/CD](README-docker.md)** — Containerized with Docker, automated builds via GitHub Actions, images stored in AWS ECR, database on MongoDB Atlas.
- **[Kubernetes Deployment (K3s)](README-kubernetes.md)** — Orchestrated on a single-node K3s cluster, pulling images from ECR with secrets-based configuration.
- **[Managed Kubernetes (AWS EKS)](README-eks.md)** — Deployed on Amazon EKS with eksctl, autoscaling worker nodes, and AWS LoadBalancer services.
## Tech Stack

React · Java Spring Boot · MongoDB Atlas · Docker · Kubernetes · K3s · AWS EKS · AWS EC2 · AWS ECR · GitHub Actions 

## Repositories

- Backend: https://github.com/oshiokefred-collab/netflix-styled-backend
- Frontend: https://github.com/oshiokefred-collab/netflix-styled-frontend