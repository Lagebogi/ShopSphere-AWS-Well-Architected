<img width="417" height="287" alt="image" src="https://github.com/user-attachments/assets/fa6789e2-7d24-4041-a537-02ca29bc2110" /># ShopSphere — Full AWS Well-Architected Project Evidence

A complete GitHub-ready evidence archive for the **ShopSphere production-oriented AWS architecture**.

This repository documents the implementation from the **VPC foundation through security, compute, load balancing, scaling, observability, WAF, CloudTrail, AWS Config, Amazon RDS, application validation, and Well-Architected evidence**.

## Architecture

```text
Users
  │
  ▼
Amazon CloudFront
  │
  ▼
Application Load Balancer
  │
  ├───────────────┐
  ▼               ▼
EC2 App-A       EC2 App-B
us-east-1a      us-east-1b
  │               │
  └───────┬───────┘
          ▼
     Amazon RDS MySQL
        Multi-AZ
      Private subnets
```

## Well-Architected alignment

| Pillar | Evidence in this project |
|---|---|
| Operational Excellence | SSM, CloudWatch, CloudTrail, AWS Config |
| Security | IAM, layered Security Groups, WAF, private subnets, CloudTrail, AWS Config |
| Reliability | Multi-AZ EC2/ASG, ALB, Multi-AZ RDS, health checks and recovery testing |
| Performance Efficiency | CloudFront, ALB, Auto Scaling, monitored CPU/host health |
| Cost Optimization | Right-sized resources, managed services, storage/capacity considerations |
| Sustainability | Right-sizing and preference for managed/serverless capabilities where appropriate |

## Evidence archive

The project evidence is documented in [docs/PROJECT_EVIDENCE.md](docs/PROJECT_EVIDENCE.md).

A detailed screenshot index is available in [docs/SCREENSHOT_INDEX.md](docs/SCREENSHOT_INDEX.md), providing organized navigation across the implementation evidence.

The repository contains around **175 unique project screenshots**. Exact duplicate screenshots and non-project preview artifacts were consolidated where applicable so the repository remains clean.

## Repository structure
```text
ShopSphere-AWS-Well-Architected/
├── README.md
├── .gitignore
├── docs/
│   ├── PROJECT_EVIDENCE.md
│   └── SCREENSHOT_INDEX.md
└── screenshots/
    ├── 01-Network-Foundation/
    ├── 02-Security-and-Identity/
    ├── 03-Compute-Load-Balancing-and-Scaling/
    ├── 04-Observability-and-Operations/
    ├── 05-Auditing-and-Governance/
    ├── 06-Database-RDS/
    ├── 07-Application-and-Architecture-Evidence/
    └── 08-Additional-Project-Evidence/
```

## Portfolio presentation

The evidence is grouped by architecture concern rather than by arbitrary screenshot filename. This makes the repository easier for a recruiter or interviewer to review while retaining the complete implementation trail.

## References & Acknowledgements

### Technical References

- AWS Documentation
- AWS Well-Architected Framework

### AI Assistance

- ChatGPT by OpenAI — Used for architectural guidance, troubleshooting,
  technical explanations, documentation, and project organization.

> **Note:** Screenshots are implementation evidence captured during the ShopSphere build. Resource identifiers, timestamps, and AWS-console details are retained where they are visible in the source screenshots.
