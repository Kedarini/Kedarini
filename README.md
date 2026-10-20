# Hi, I'm Radosław        
        
**Aspiring DevOps & Cloud Engineer**        
        
I build cost-aware, end-to-end DevOps pipelines from Bash scripts and containerized apps all the way to Terraform-provisioned AWS infrastructure, secure CI/CD, and monitoring. I focus on learning by doing with an emphasis on security, reproducibility and efficiency.        
        
---
        
**Scripting & Automation:** Python | Bash      
**Cloud & Infrastructure:** AWS (EC2, RDS, ECR, IAM, SSM, Secrets Manager) | Terraform | Packer      
**Containers & Orchestration:** Docker | Kubernetes      
**CI/CD & Observability:** GitHub Actions | Prometheus | Grafana      
**Tools & Concepts:** Linux | Git | Networking | FastAPI | PostgreSQL        
        
---

## Flagship Project

### [Self-Hosted CI/CD Platform](https://github.com/Kedarini/Self-hosted-CI-CD-platform)

A FastAPI + PostgreSQL URL shortener built as a vehicle for a complete, production-style DevOps pipeline designed, provisioned and deployed end-to-end on real AWS infrastructure.

- **Infrastructure as Code:** Fully defined in Terraform (VPC, EC2, RDS, ECR, IAM roles scoped to least privilege)
- **Secure CI/CD:** GitHub Actions builds and pushes to ECR, then deploys via AWS SSM (no open SSH port)
- **Secrets Management:** DB and Grafana credentials fetched at runtime from AWS Secrets Manager
- **Custom AMI:** Built with Packer, pre-installed with Docker and the SSM Agent for faster, consistent boots
- **Monitoring:** Prometheus + Grafana provisioned as code with a pre-configured dashboard
- **Kubernetes Ready:** Declarative manifests (Deployment, Service, ConfigMap/Secret, health probes) for local clusters (kind/minikube)
- **Cost-Aware:** Designed to run within AWS Free Tier by avoiding NAT Gateway, ALB and EKS

`Terraform` `AWS` `Docker` `Kubernetes` `GitHub Actions` `Packer` `Prometheus` `Grafana` `FastAPI` `PostgreSQL`

---

## Featured Projects

### CI/CD & Containers
- [Docker-GithubActions](https://github.com/Kedarini/Docker-GithubActions) - Frontend + FastAPI backend + PostgreSQL containerized with Nginx as a reverse proxy, validated by a GitHub Actions pipeline.

### Linux & Server Automation
- [Server Performance Stats](https://github.com/Kedarini/Server-Performance-Stats) - Monitor CPU, memory, disk usage and top resource-consuming processes via CLI.
- [Log Archive Tool](https://github.com/Kedarini/Log-Archive-Tool) - Bash script to archive `/var/log` into a timestamped `.tar.gz` file.
- [Nginx Log Analyser](https://github.com/Kedarini/Nginx-Log-Analyser) - Parse Nginx access logs with shell pipelines to find top IPs, paths and status codes.
- [SSH Remote Server Setup](https://github.com/Kedarini/SSH-Remote-Server-Setup) - Secure setup and connection to a remote AWS EC2 instance.
- [Static Site Server](https://github.com/Kedarini/Static-Site-Server) - Deploy and serve a static website with Nginx on AWS EC2.
- [GitHub Deployment Workflow](https://github.com/Kedarini/GitHub-Deployment-Workflow) - Automate deployment of a static site to GitHub Pages via GitHub Actions.

---

## Contact
- **Email:** [radekdamps@gmail.com](mailto:radekdamps@gmail.com)
- **LinkedIn:** [radoslawdamps](https://www.linkedin.com/in/radoslawdamps/)
