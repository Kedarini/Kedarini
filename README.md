# Hi there, I'm Radosław!    
**Aspiring DevOps & Cloud Engineer**    
    
I build full, working pipelines to learn tools properly, not just in theory from a Bash script to a    
Terraform-managed AWS stack with CI/CD, secrets management, and Kubernetes as an alternative deployment    
target. I bridge the gap between code and infrastructure to build scalable, automated systems.    

---
    
**Languages:** Python | Bash    
**Second Languages:** C# | JavaScript & TypeScript    
**Cloud & Infra:** AWS (EC2, RDS, ECR, IAM, Secrets Manager, SSM) | Terraform (IaC) | Docker | Kubernetes | Packer    
**CI/CD & Monitoring:** GitHub Actions | Prometheus | Grafana    
**Tools:** Git, Linux (Arch Linux/CLI), Networking concepts, FastAPI, PostgreSQL    
    
---
    
## Flagship Project    
    
### [Self-Hosted CI/CD Platform](https://github.com/Kedarini/Self-hosted-CI-CD-platform)    
A FastAPI + PostgreSQL URL shortener built as a vehicle for a complete, production-style DevOps pipeline    
designed, deployed, and debugged end to end on real AWS infrastructure.    
    
- Infrastructure fully defined in **Terraform**: VPC, EC2, RDS, ECR, IAM roles scoped to least privilege    
- **CI/CD** in GitHub Actions lint, test, build/push to ECR, deploy via **AWS SSM** (no open SSH port)    
- Secrets (DB, Grafana) fetched at **runtime from AWS Secrets Manager** never written to disk or Git    
- Custom **Packer**-built AMI with Docker and the SSM Agent preinstalled for faster, consistent boots    
- **Prometheus + Grafana** monitoring, with the datasource and dashboard provisioned as code    
- **Kubernetes** manifests (Deployment, Service, ConfigMap/Secret, health probes) as an alternative
  deployment target on a local cluster    
    
`Terraform` `AWS` `Docker` `Kubernetes` `GitHub Actions` `Packer` `Prometheus/Grafana` `FastAPI` `PostgreSQL`    
    
---    

## Featured Projects    
    
### Full-Stack & CI/CD    
- [Docker-GithubActions](https://github.com/Kedarini/Docker-GithubActions) - Frontend + FastAPI backend +
  PostgreSQL, each containerized as a separate service behind Nginx, with a GitHub Actions pipeline
  validating the build on every change.    
    
### Automation & Scripting    
- [Bash Organizer](https://github.com/Kedarini/Bash-Organizer) - Automating file organization and workspace cleanup using Bash.    
- [Bash Backup](https://github.com/Kedarini/Bash-Backup) - Automating creation of backup of current working directory.    
- [Bash System Monitor](https://github.com/Kedarini/Bash-System-Monitor) - Script checking system usage status.    
- [Temp Cleanup](https://github.com/Kedarini/TempCleanup) - Python-based automation tool for system maintenance.    
- [Job Scraper](https://github.com/Kedarini/PythonJobScraper) - Automated web scraper for data collection and analysis.    
    
### DevOps Roadmap Projects    
- [Server Performance Stats](https://github.com/Kedarini/Server-Performance-Stats) - Monitor CPU, memory, and disk usage, alongside the top resource-consuming processes.    
- [Log Archive Tool](https://github.com/Kedarini/Log-Archive-Tool) - A Bash script to archive `/var/log` into a timestamped `.tar.gz` file in a specified directory.    
- [Nginx Log Analyser](https://github.com/Kedarini/Nginx-Log-Analyser) - Bash script using pipelines to parse Nginx logs for top IPs, paths, and status codes.    
- [GitHub Deployment Workflow](https://github.com/Kedarini/Gh-Deployment-Workflow) - Continuously deploy index.html to GitHub Pages.    
- [SSH Remote Server Setup](https://github.com/Kedarini/SSH-Remote-Server-Setup) - Connect to AWS server.    
- [Static Site Server](https://github.com/Kedarini/Static-Site-Server) - Setup Nginx server on AWS.    
    
### Software Development    
- [Currency Exchange](https://github.com/Kedarini/ExchangeCurrency) & [Password Generator](https://github.com/Kedarini/PasswordGenerator) — Practical applications demonstrating clean code principles in Python.    
    
---    
    
## Let's Connect    
- **Email:** radekdamps@gmail.com    
- **LinkedIn:** [radoslawdamps](https://www.linkedin.com/in/radoslawdamps/)    
    
