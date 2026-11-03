*************************************************** DAY 1 ***************************************************

My Learning Plan : 

Month 1: Linux, Networking, & Cloud Foundations

Focus on understanding where applications live and how they communicate.
• Week 1: Linux & Command Line
	• Learn file systems, permissions (chmod, chown), and user management.
	• Master essential commands (ssh, grep, awk, find, curl).
	• Write basic Bash scripts to automate simple tasks (e.g., backing up a folder).
• Week 2: Networking & Security Basics
	• Understand OSI model layers, IP addressing, subnets, and DNS.
	• Learn how HTTP/HTTPS, SSH, and firewalls work.
	• Tools to practice: ping, traceroute, nslookup, netstat.
• Week 3 & 4: Cloud Computing (AWS, AWS, or GCP)
	• Pick one provider (AWS is highly recommended for beginners).
	• Learn core services: Compute (EC2), Networking (VPC), Storage (S3), and Identity Management (IAM).
	• Project 1: Host a static website on an S3 bucket and launch a secure EC2 instance running a basic web server.

Month 2: Containers, CI/CD, & Infrastructure as Code (IaC)

Focus on packaging applications and automating infrastructure.
• Week 5 & 6: Git & Containerisation (Docker)
	• Master Git workflows (branching, merging, pull requests).
	• Learn Docker fundamentals: Containers vs. VMs, writing Dockerfiles, and managing volumes/networks.
	• Explore multi-container setups using Docker Compose.
• Week 7: Continuous Integration/Continuous Deployment (CI/CD)
	• Learn the concept of the deployment pipeline.
	• Pick a tool like GitHub Actions or Jenkins.
	• Automate code linting, building a Docker image, and pushing it to a registry (Docker Hub).
• Week 8: Infrastructure as Code (Terraform)
	• Learn why manual cloud configuration is bad.
	• Master Terraform basics: Providers, Resources, Variables, and State.
	• Project 2: Write a Terraform script to spin up your Month 1 AWS infrastructure automatically, package your web app into a Docker image, and deploy it.

Month 3: Container Orchestration & Monitoring

Focus on scaling applications and keeping them healthy.
• Week 9 & 10: Kubernetes (K8s)
	• Understand why we need orchestration for multiple Docker containers.
	• Learn K8s architecture (Control Plane, Worker Nodes) and core objects (Pods, Deployments, Services, ConfigMaps).
	• Practice locally using Minikube or Kind.
• Week 11: Observability & Monitoring
	• Learn the importance of logs and metrics.
	• Set up Prometheus to gather system metrics and Grafana to build visual dashboards.
	• Understand basic log aggregation (like the ELK stack or Loki).
• Week 12: Capstone Project
	• Project 3: Build a complete GitOps pipeline. Push code to GitHub → GitHub Actions builds a Docker image → Terraform provisions a Kubernetes cluster → Your application automatically deploys to Kubernetes with active Prometheus monitoring.

