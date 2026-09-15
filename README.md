# ShopSphere — Full AWS Well-Architected Project Evidence

A complete GitHub-ready evidence archive for the **ShopSphere production-oriented AWS architecture**.

This repository documents the implementation from the VPC foundation through security, compute, load balancing, scaling, observability, governance, database infrastructure, application validation, and AWS Well-Architected evidence.

> **Note:** This project is designed as a portfolio and learning implementation demonstrating production-oriented AWS architecture and Well-Architected principles. It should not be interpreted as a live production system.

---

## Architecture

The ShopSphere architecture is designed around a secure, highly available, scalable, and observable AWS environment.

```text
                         Users
                           |
                           v
                    Amazon CloudFront
                           |
                           v
                 Application Load Balancer
                           |
                  +--------+--------+
                  |                 |
                  v                 v
             EC2 App-A         EC2 App-B
             us-east-1a        us-east-1b
                  |                 |
                  +--------+--------+
                           |
                           v
                    Amazon RDS MySQL
                       Multi-AZ
                    Private Subnets
```

### Core Architecture Components

- Amazon VPC
- Public, application, and database subnets
- Internet Gateway
- NAT Gateway
- Public and application route tables
- Security Groups
- IAM and AWS Systems Manager access
- Amazon EC2
- EC2 Launch Template
- Auto Scaling Group
- Application Load Balancer
- Target Group
- Amazon CloudFront
- AWS WAF
- Amazon CloudWatch
- Amazon CloudTrail
- AWS Config
- Amazon RDS for MySQL
- Amazon SQS

---

## Well-Architected Alignment

The implementation is organized around the six pillars of the **AWS Well-Architected Framework**.

| Pillar | Evidence in this project |
|---|---|
| **Operational Excellence** | AWS Systems Manager, CloudWatch, CloudTrail, AWS Config, monitoring, alarms, and operational validation |
| **Security** | IAM, layered Security Groups, AWS WAF, private subnets, CloudTrail, and AWS Config |
| **Reliability** | Multi-AZ EC2/Auto Scaling, ALB, Multi-AZ RDS, health checks, and recovery validation |
| **Performance Efficiency** | CloudFront, ALB, Auto Scaling, and CloudWatch performance monitoring |
| **Cost Optimization** | Right-sized resources, managed services, Auto Scaling, and resource utilization monitoring |
| **Sustainability** | Elastic scaling, managed services, and monitoring of resource utilization |

---

## Key AWS Services Demonstrated

### Networking

- Amazon VPC
- Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Elastic IP
- VPC resource mapping
- Network segmentation

### Security and Identity

- AWS IAM
- AWS Systems Manager
- Security Groups
- AWS WAF
- Web ACL
- Managed WAF protections
- Private database networking

### Compute and Scaling

- Amazon EC2
- EC2 Launch Templates
- Auto Scaling Groups
- Multi-AZ application instances
- Application health validation

### Load Balancing and Delivery

- Application Load Balancer
- Target Groups
- Health checks
- Amazon CloudFront

### Observability and Operations

- Amazon CloudWatch
- CloudWatch dashboards
- Metrics
- CPU monitoring
- Application health monitoring
- ALB HealthyHostCount monitoring
- CloudWatch alarms

### Auditing and Governance

- AWS CloudTrail
- AWS Config
- Configuration recording
- Managed compliance rules
- Compliance monitoring
- Resource inventory

### Database

- Amazon RDS for MySQL
- Multi-AZ configuration
- DB subnet groups
- Private database subnets
- Database connectivity
- Monitoring
- Backup configuration

### Messaging

- Amazon SQS

---

## Evidence Archive

The repository contains **around 175 unique project screenshots**, organized into dedicated architectural and operational sections.

The screenshots provide visual evidence of:

- Infrastructure deployment
- VPC and networking configuration
- Security controls
- IAM configuration
- AWS WAF protection
- EC2 deployment
- Auto Scaling
- Load balancing
- Multi-AZ architecture
- Application health
- CloudWatch monitoring
- CloudWatch alarms
- CloudTrail auditing
- AWS Config governance
- RDS configuration
- Database networking
- SQS configuration
- Application validation

A detailed project explanation is available in:

**[`docs/PROJECT_EVIDENCE.md`](docs/PROJECT_EVIDENCE.md)**

A detailed screenshot navigation index is available in:

**[`docs/SCREENSHOT_INDEX.md`](docs/SCREENSHOT_INDEX.md)**

Exact duplicate screenshots and non-project preview artifacts were consolidated where applicable.

---

## Repository Structure

```text
ShopSphere-AWS-Well-Architected/
│
├── README.md
├── .gitignore
│
├── docs/
│   ├── PROJECT_EVIDENCE.md
│   └── SCREENSHOT_INDEX.md
│
└── screenshots/
    │
    ├── 01-Network-Foundation/
    │
    ├── 02-Security-and-Identity/
    │
    ├── 03-Compute-Load-Balancing-and-Scaling/
    │
    ├── 04-Observability-and-Operations/
    │
    ├── 05-Auditing-and-Governance/
    │
    ├── 06-Database-RDS/
    │
    ├── 07-Application-and-Architecture-Evidence/
    │
    └── 08-Additional-Project-Evidence/
```

---

## Project Evidence by Section

### 01 — Network Foundation

Documents the underlying AWS networking architecture, including:

- VPC creation
- Subnet configuration
- Internet Gateway
- Public route table
- NAT Gateway
- Application route table
- VPC resource map
- Elastic IP
- RDS connectivity
- Database subnet group configuration

### 02 — Security and Identity

Documents the security controls implemented around the application and database tiers, including:

- Application Load Balancer Security Group
- Application Security Group
- Database Security Group
- IAM role configuration
- AWS Systems Manager access
- AWS WAF Web ACL
- WAF managed protections
- ALB protection

### 03 — Compute, Load Balancing, and Scaling

Documents the compute and high-availability layer, including:

- EC2 application instances
- Launch Template
- Launch Template advanced configuration
- Auto Scaling Group
- Desired capacity
- Multi-AZ instances
- Target Group
- Application Load Balancer
- Health checks
- Application availability validation

### 04 — Observability and Operations

Documents monitoring and operational visibility, including:

- CloudWatch dashboards
- EC2 CPU metrics
- Application health metrics
- CPU alarms
- ALB HealthyHostCount alarms
- Alarm configuration
- Health recovery validation

### 05 — Auditing and Governance

Documents AWS governance and audit capabilities, including:

- CloudTrail
- AWS Config
- Configuration recording
- Managed Config rules
- Compliance status
- Resource inventory
- Governance validation

### 06 — Database and RDS

Documents the ShopSphere database layer, including:

- Amazon RDS MySQL
- Multi-AZ configuration
- DB subnet group
- Private database networking
- RDS connectivity
- Monitoring
- Backup configuration
- Database security

### 07 — Application and Architecture Evidence

Documents application-level validation and end-to-end architecture evidence, including:

- Application availability
- Multi-AZ application health
- Load-balanced application access
- Architecture validation
- End-to-end implementation evidence

### 08 — Additional Project Evidence

Contains additional supporting screenshots captured during implementation, troubleshooting, validation, and project development.

---

## Portfolio Presentation

This repository is structured to make the project easy to review from an engineering, cloud architecture, and interview perspective.

A reviewer can:

1. Start with the architecture overview.
2. Review the Well-Architected alignment.
3. Explore the AWS services used.
4. Review the project evidence documentation.
5. Navigate directly to individual screenshot categories.
6. Inspect the implementation evidence for networking, security, compute, monitoring, governance, and database architecture.

---

## Key Design Principles Demonstrated

The ShopSphere architecture demonstrates several practical cloud engineering principles:

- **High availability** through Multi-AZ deployment
- **Horizontal scalability** through Auto Scaling
- **Load distribution** through an Application Load Balancer
- **Network isolation** through subnet segmentation
- **Controlled access** through IAM and Security Groups
- **Application protection** through AWS WAF
- **Operational visibility** through CloudWatch
- **Auditing** through CloudTrail
- **Governance** through AWS Config
- **Database resilience** through RDS Multi-AZ
- **Content delivery** through CloudFront
- **Decoupled messaging capability** through Amazon SQS

---

## Learning and Engineering Outcomes

This project provided hands-on experience with:

- AWS networking architecture
- Multi-AZ design
- EC2 and Auto Scaling
- Application Load Balancing
- AWS security controls
- IAM
- AWS WAF
- CloudWatch monitoring and alarms
- CloudTrail auditing
- AWS Config governance
- Amazon RDS
- Application validation
- AWS Well-Architected Framework principles

The project also demonstrates the ability to connect individual AWS services into a cohesive cloud architecture rather than treating each service as an isolated component.

---

## References & Acknowledgements

### Technical References

- AWS Documentation
- AWS Well-Architected Framework

### AI Assistance

- **ChatGPT by OpenAI** — Used for architectural guidance, troubleshooting, technical explanations, documentation, project organization, and evidence curation.

All AWS architecture decisions and implementations represented in this repository were reviewed and validated as part of the project development process.

---

## Project Status

**Status:** Completed portfolio evidence archive

**Architecture focus:** Production-oriented AWS / Well-Architected design

**Primary region used:** `us-east-1`

**Availability design:** Multi-AZ

**Database:** Amazon RDS for MySQL

**Monitoring:** Amazon CloudWatch

**Security:** IAM, Security Groups, AWS WAF, CloudTrail, AWS Config

---

## Final Note

ShopSphere is intended to demonstrate practical understanding of AWS architecture, infrastructure implementation, security, reliability, scalability, observability, governance, and the AWS Well-Architected Framework.

The repository is organized as an evidence-driven portfolio project so that the architecture and implementation can be reviewed systematically.
