<div align="center">

# Hi, I'm Marwan Hassan Abdo 👋

### Multi-Cloud Engineer Trainee @ GBG | DevOps & Cloud Engineering

Cairo, Egypt · [LinkedIn](https://www.linkedin.com/in/marwannhassan) · [Email](mailto:marwanhassanabdo22@gmail.com)

</div>

---

## About Me

I'm a Computer Science graduate focused on **Cloud Engineering, Multi-Cloud Infrastructure, and DevOps**. I build practical cloud environments and automation workflows with an emphasis on security, networking, scalability, reliability, and repeatable deployments.

I'm currently a **Multi-Cloud Engineer Trainee at GBG**, working with practical market scenarios across **AWS and Microsoft Azure**. Alongside this role, I have completed and worked through a broad set of AWS training assignments and hands-on labs covering identity and access management, compute, networking, storage, migration, backup, disaster recovery, and application delivery.

- ☁️ AWS cloud architecture, infrastructure, security, and operations.
- 🌐 Multi-cloud learning across AWS and Microsoft Azure.
- 🔐 IAM, network security, secure connectivity, and traffic inspection.
- ⚙️ Linux, Docker, Kubernetes, Jenkins, Terraform, and Ansible.
- 📍 Cairo, Egypt.

## Current Role

**Multi-Cloud Engineer Trainee — GBG**  
*October 2026 – Present*

Working on practical market scenarios that simulate production environments across AWS and Azure.

Selected scenarios from this GBG training experience:

1. **Secure & Scalable AWS Environments** — Enforcing MFA, implementing tag-based access control, and enabling secure EC2-to-S3 access through IAM roles instead of hardcoded credentials.
2. **Application Deployment with Elastic Beanstalk** — Deploying a Flask web application while exploring managed infrastructure, load balancing, and Auto Scaling.
3. **Secure EC2 Management with Systems Manager** — Using Session Manager and Run Command to manage instances and configure Apache without opening SSH port 22.
4. **Automated Hosting with AWS Amplify** — Connecting a GitHub repository to Amplify for automated deployments triggered by repository changes.

These four scenarios describe the work highlighted in my GBG announcement. They are **not** the complete list of my AWS projects and labs.

## AWS Hands-on Projects & Labs

In addition to the four GBG scenarios above, I have worked on **15+ AWS hands-on scenarios and architecture tasks** through my cloud training and practical lab work. The areas below are grouped by project so the scope of the work is clear.

### 1. Identity, Access Management & Secure Application Infrastructure

- **IAM MFA Enforcement** — Creating IAM controls that require MFA and restrict access until MFA is configured.
- **Tag-Based Access Control** — Applying permission boundaries through resource tags and conditions, including environment-based access such as `Env=Dev`.
- **Secure EC2-to-S3 Access** — Using an EC2 instance profile and IAM role to access S3 with least privilege, without storing long-term AWS access keys on the instance.
- **Secure & Scalable Web Application** — Building an EC2-based web application environment with an Application Load Balancer, target groups, health checks, launch templates, and an Auto Scaling Group across multiple Availability Zones.

### 2. AWS Storage, Backup & Recovery

- **Amazon EFS Regional File System** — Creating an encrypted Regional EFS file system, configuring mount targets across Availability Zones, and securing NFS access with security groups.
- **Amazon S3 File Gateway** — Configuring an AWS Storage Gateway file share backed by S3 and accessing the file share from an EC2 Linux instance.
- **AWS Backup** — Creating a backup vault and backup plan for EC2, EBS, EFS, and S3, then testing recovery by restoring resources separately.

### 3. AWS Networking & Secure Connectivity

- **AWS Client VPN** — Configuring a Client VPN endpoint, certificate-based authentication, client CIDR, subnet association, authorization rules, split tunneling, and connection logging.
- **Hub-and-Spoke Architecture with Centralized AWS Network Firewall** — Designing a hub-and-spoke environment with Transit Gateway, VPC attachments, firewall subnets, route tables, and centralized traffic inspection. This project remains under validation: I do not consider it complete until every required ingress, egress, and inter-VPC route is verified to traverse the Network Firewall.

### 4. Database Migration & Data Transfer

- **Cross-Region MySQL Migration with AWS DMS** — Migrating a MySQL database between EC2 environments in different AWS Regions, configuring binary logging for Change Data Capture (CDC), setting up DMS endpoints and replication, validating data, and planning cutover.
- **AWS DataSync: EFS to S3 Across Regions** — Building the source environment on AWS in a separate Region (including EC2 and EFS), then transferring files to an S3 destination using DataSync locations and tasks.

### 5. Linux Disaster Recovery

- **Linux Disaster Recovery with Nginx** — Designing a Linux-only DR environment with Nginx, using AWS-hosted primary and recovery environments in separate Regions, and planning Route 53 failover/failback for application continuity. The design also considers the application backend and private connectivity requirements.

### 6. Additional AWS Application & Operations Labs

- **AWS Elastic Beanstalk** — Deploying a Flask application in a managed web environment and exploring load balancing and scaling.
- **AWS Systems Manager** — Managing Linux EC2 instances with Session Manager and Run Command without relying on SSH access.
- **AWS Amplify** — Connecting a GitHub repository to a static website deployment and validating automatic redeployment after source changes.

> **Project documentation note:** This section summarizes the AWS tasks and labs I have worked on; it does not imply that every item already has a separate public repository. I am preparing dedicated repositories with architecture diagrams, implementation steps, security notes, validation evidence, and cleanup instructions. Any architecture still being tested is identified as in progress rather than marked complete.

## DevOps & Application Projects

- **[DEPI DevOps Project](https://github.com/Marwan226/DEPI-Project)** — E-commerce application project with DevOps work covering Docker, Kubernetes, Ansible, Terraform, Jenkins CI/CD, and Prometheus/Grafana planning and implementation artifacts.
- **[Java CI/CD with Jenkins, Docker & Kubernetes](https://github.com/Marwan226/simple-java-app-dolfined)** — Maven-based Java application with Docker image building, Jenkins pipeline stages, Docker Hub publishing, and Kubernetes deployment manifests for Amazon EKS.
- **[SpareCar Application](https://github.com/Marwan226/Spare-car)** — Full-stack spare-parts e-commerce application with a React/TypeScript frontend and Node.js/Express backend using MongoDB/Mongoose. The repository also contains infrastructure work folders for Ansible, Kubernetes, and Terraform.

## Automation Project

- **[UiPath RPA Travel Automation](https://github.com/Marwan226/uipath_rpa)** — Travel invoice processing automation using Dispatcher and Performer workflows, REFramework, UiPath Queues, and validation rules.

## Technical Skills

| Category | Technologies & Skills |
|---|---|
| Cloud Platforms | Amazon Web Services (AWS), Microsoft Azure |
| AWS Services | EC2, S3, IAM, VPC, EBS, EFS, ALB, Auto Scaling, Elastic Beanstalk, Systems Manager, Amplify, AWS Backup, Client VPN, DMS, DataSync, Transit Gateway, Network Firewall, Route 53 |
| DevOps & CI/CD | Docker, Kubernetes, Jenkins, CI/CD Pipelines |
| Infrastructure as Code | Terraform, Ansible |
| Operating Systems | Linux, Red Hat Enterprise Linux 10, Bash, LVM |
| Monitoring | Prometheus, Grafana, Alertmanager |
| Networking & Security | TCP/IP, Routing, VPC Networking, Security Groups, Juniper, FortiGate, IAM, Firewall Technologies |
| Automation | UiPath, REFramework, Queues |
| Version Control | Git, GitHub |

## Certifications

- **AWS Certified Solutions Architect – Associate (SAA-C03)**
- **AWS Certified Cloud Practitioner**
- AWS Academy Cloud Architecting
- AWS Academy Cloud Foundations
- Red Hat System Administration I (RH124) — Red Hat Academy
- Red Hat System Administration II (RH134) — Red Hat Academy

## Training & Professional Development

- **Multi-Cloud Engineer Trainee — GBG** | October 2026 – Present
- **Cloud Training — National Telecommunications Institute (NTI)** | January 2026 – April 2026  
  120 training hours, 25+ AWS Academy modules, and 20+ hands-on labs.
- **Linux Administration Training — National Telecommunications Institute (NTI)** | June 2026 – August 2026  
  Red Hat System Administration I and II based on RHEL 10.
- **DevOps Training — Digital Egypt Pioneers Initiative (DEPI)** | June 2025 – December 2025

## Previous Experience

- **RPA Automation Intern — BARQ Systems** | July 2026 – September 2026  
  Developed UiPath workflows for travel invoice processing using Dispatcher/Performer patterns, REFramework, queues, and validation rules.
- **Network Security Intern — BARQ Systems** | May 2026 – June 2026  
  Gained practical exposure to Juniper devices, FortiGate firewalls, networking fundamentals, and enterprise network security.

## Current Focus

- Advanced AWS networking and centralized traffic inspection.
- Multi-cloud architecture across AWS and Azure.
- Infrastructure as Code and configuration automation.
- Kubernetes, containerized workloads, and CI/CD.
- Cloud security, monitoring, migration, and disaster recovery.

---

<div align="center">

**Build. Automate. Secure. Learn continuously.**

</div>
