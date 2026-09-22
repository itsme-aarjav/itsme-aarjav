# Hi, I'm Aarjav Jain

### DevOps and Cloud Engineering

B.Tech CSE (AI and ML) graduate focused on building practical skills in DevOps and Cloud Engineering.

I enjoy working with cloud infrastructure, Linux, containers, CI/CD pipelines, Kubernetes, and deployment workflows. Most of my learning comes from building projects, breaking things, troubleshooting them, and getting them running again.

## Technical Skills

* **AWS:** EC2, VPC, IAM, S3, RDS, DynamoDB, Lambda, CloudFormation, CloudWatch, CloudFront, Route 53, EBS, KMS, Auto Scaling, Load Balancer
* **CI/CD:** Jenkins, Declarative Pipeline, Jenkinsfile, GitHub Webhooks, Pipeline as Code, Jenkins Agents, Credentials, Parameters
* **Containers:** Docker, Docker Compose, Dockerfile, Docker Hub, Multi Stage Builds, Container Health Checks
* **Code Quality and Security:** SonarQube, SonarQube Scanner, Quality Gates, Trivy, Container Vulnerability Scanning
* **Kubernetes:** Kubernetes, Minikube, kubectl, Helm, Deployments, ReplicaSets, StatefulSets, Services, ClusterIP, Ingress, ConfigMaps, Secrets, HPA, PVC, Metrics Server, Probes, Rollouts
* **Linux and Networking:** Linux, Ubuntu, Bash, Nginx, TCP/IP, DNS, CIDR, Subnets, Routing, Reverse Proxy
* **Tools:** Git, GitHub, Jira, Python

## Featured Projects

### Full Stack ChatApp | End to End DevOps and Kubernetes

This is my latest and most complete DevOps project. I took a full stack real time chat application and worked on the containerization, CI/CD pipeline, security checks, Kubernetes deployment, scaling, storage, and recovery side of the project.

**Application technologies**

* React
* Vite
* Node.js
* Express.js
* Socket.IO
* MongoDB

**DevOps and infrastructure technologies**

* Git and GitHub
* Jenkins
* SonarQube
* Trivy
* Docker
* Docker Hub
* Kubernetes
* Minikube
* kubectl
* Helm
* Nginx
* AWS EC2

**What I implemented**

* GitHub Webhook triggers the Jenkins pipeline automatically
* Jenkins runs frontend linting and SonarQube analysis
* Docker images are built for the frontend and backend using multi stage Dockerfiles
* Trivy scans the images for HIGH and CRITICAL vulnerabilities before they are pushed
* Versioned images are pushed to Docker Hub
* Helm is used to deploy the application to Kubernetes
* Frontend and backend run as Kubernetes Deployments
* MongoDB runs as a StatefulSet with persistent storage using PVC
* Nginx Ingress and host Nginx handle application traffic and API or Socket.IO routing
* Readiness and liveness probes are used for health checks
* CPU requests and limits are configured for workloads
* HPA and Metrics Server are used for autoscaling
* Kubernetes Secrets and Jenkins credentials are used to keep sensitive values out of Git
* Helm release history and rollback were tested using a failed deployment scenario
* Deployment health is checked using kubectl rollout status and cluster resource checks

[View Repository](https://github.com/itsme-aarjav/full-stack_chatApp)

### POKÉVAULT LEGENDS | AWS 3 Tier Cloud Deployment

A hands on AWS cloud infrastructure project where I worked on deploying and testing a 3 tier application setup.

**Technologies used**

* AWS EC2
* VPC
* Public and Private Subnets
* Route Tables
* Internet Gateway
* NAT Gateway
* Security Groups
* Application Load Balancer
* Target Groups
* Health Checks
* Ubuntu Linux
* Git and GitHub

[View Repository](https://github.com/itsme-aarjav/pokevault-legends)

### DevOps Project Dashboard | Docker Containerization

A practical Docker project created to understand container based application deployment and day to day container management.

**Technologies used**

* Docker
* Dockerfile
* Docker Hub
* Environment Variables
* Port Mapping
* Container Logs
* Container Lifecycle Management
* Health Checks
* Linux and curl

[View Repository](https://github.com/itsme-aarjav/java)

## My DevOps Workflow

```text
GitHub
   ↓
Jenkins
   ↓
Lint and SonarQube
   ↓
Docker Build
   ↓
Trivy Scan
   ↓
Docker Hub
   ↓
Helm
   ↓
Kubernetes
   ↓
Verification, Scaling, Persistence and Rollback
```

## Connect

* [LinkedIn](https://www.linkedin.com/in/aarjav-jain-60b2762a5/)
* [GitHub](https://github.com/itsme-aarjav)
