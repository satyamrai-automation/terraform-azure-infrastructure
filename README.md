<div align="center">

# ⚡ Terraform Azure Infrastructure

### *Infrastructure as Code • Microsoft Azure • Enterprise DevOps*

A curated collection of Terraform configurations for building modern Microsoft Azure infrastructure following Infrastructure as Code (IaC), cloud architecture, and DevOps engineering best practices.

[![Terraform](https://img.shields.io/badge/Terraform-v1.x-623CE4?style=flat-square&logo=terraform)]()
[![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?style=flat-square&logo=microsoftazure)]()
[![GitHub](https://img.shields.io/badge/Open%20Source-GitHub-181717?style=flat-square&logo=github)]()
[![License](https://img.shields.io/badge/License-MIT-success?style=flat-square)]()

---

*"Automate infrastructure. Document everything. Build once. Reuse everywhere."*

</div>

---

# Overview

This repository serves as a personal Infrastructure Engineering Lab focused on Microsoft Azure and Terraform.

Instead of isolated examples, every directory represents a practical infrastructure component that contributes toward building a production-inspired Azure platform.

The primary objective is to learn cloud infrastructure through hands-on implementation while following engineering standards commonly used in enterprise environments.

---

# Repository Goals

- Build Azure infrastructure using Terraform
- Learn Infrastructure as Code (IaC)
- Practice reusable Terraform modules
- Improve Azure architecture knowledge
- Follow Git & GitHub workflow
- Apply infrastructure security best practices
- Maintain production-style documentation
- Continuously improve cloud engineering skills

---

# Learning Journey

| Phase | Focus | Status |
|:------:|---------------------------|:------:|
| Phase 01 | Infrastructure Foundation | ✅ Completed |
| Phase 02 | Storage Services | 🚧 In Progress |
| Phase 03 | Networking | 🚧 In Progress |
| Phase 04 | Compute | ⏳ Planned |
| Phase 05 | Security | ⏳ Planned |
| Phase 06 | Identity | ⏳ Planned |
| Phase 07 | Monitoring | ⏳ Planned |
| Phase 08 | Containers & AKS | ⏳ Planned |
| Phase 09 | Automation | ⏳ Planned |
| Phase 10 | Azure Landing Zone | 🎯 Final Goal |

---

# Repository Structure

```text
terraform-azure-infrastructure/

├── 01-resource-group/
├── 02-storage-account/
├── 03-virtual-network/
├── 04-subnet/
├── 05-network-security-group/
├── 06-public-ip/
├── 07-network-interface/
├── 08-linux-virtual-machine/
├── 09-bastion/
├── 10-load-balancer/
├── 11-application-gateway/
├── 12-key-vault/
├── 13-managed-identity/
├── 14-monitoring/
├── 15-aks/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# Engineering Principles

- Infrastructure as Code
- Modular Design
- Reusable Components
- Automation First
- Security by Default
- Documentation Driven
- Version Controlled Infrastructure
- Continuous Learning

---

# Technology Stack

| Domain | Technologies |
|---------|--------------|
| Cloud | Microsoft Azure |
| IaC | Terraform |
| Version Control | Git & GitHub |
| CLI | Azure CLI |
| Scripting | PowerShell · Bash |
| IDE | Visual Studio Code |

---

# Development Workflow

```text
Plan
   │
   ▼
Design
   │
   ▼
Terraform Development
   │
   ▼
terraform fmt
   │
   ▼
terraform validate
   │
   ▼
terraform plan
   │
   ▼
Local Testing
   │
   ▼
Feature Branch
   │
   ▼
Commit
   │
   ▼
Push
   │
   ▼
Pull Request
   │
   ▼
Review
   │
   ▼
Merge
```

---

# Project Roadmap

### Foundation

- [x] Azure Resource Group

### Storage

- [ ] Storage Account
- [ ] Blob Storage

### Networking

- [ ] Virtual Network
- [ ] Subnet
- [ ] Network Security Group
- [ ] Public IP
- [ ] Network Interface

### Compute

- [ ] Linux Virtual Machine
- [ ] Availability Set
- [ ] VM Scale Set

### Networking Services

- [ ] Azure Bastion
- [ ] Load Balancer
- [ ] Application Gateway

### Identity & Security

- [ ] Managed Identity
- [ ] Key Vault
- [ ] Azure Firewall
- [ ] Private Endpoint

### Observability

- [ ] Azure Monitor
- [ ] Log Analytics

### Containers

- [ ] Azure Container Registry
- [ ] Azure Kubernetes Service

### Enterprise

- [ ] Azure Landing Zone

---

# Quality Standards

Each module is expected to follow these quality checks.

- ✅ terraform fmt
- ✅ terraform validate
- ✅ terraform plan
- ⏳ TFLint
- ⏳ tfsec
- ⏳ Checkov
- ⏳ Gitleaks
- ⏳ Trivy
- ⏳ Infracost

---

# Future Vision

The long-term objective is to evolve this repository into a production-inspired Azure Infrastructure collection featuring:

- Enterprise Terraform Modules
- Azure Landing Zone
- Hub & Spoke Architecture
- Multi-Environment Deployments
- Remote State Management
- GitHub Actions CI/CD
- Infrastructure Security
- Policy as Code
- Monitoring & Observability
- Cost Optimization

---

# Contributing

Suggestions, improvements, and discussions are always welcome.

If you have ideas to improve the repository, feel free to open an Issue or submit a Pull Request.

---

# Author

**Satyam Rai**

DevOps Engineer • Cloud Engineer • Terraform • Microsoft Azure

> Learning in public. Building with code. Automating the cloud.

---

# License

Distributed under the MIT License.

---

<div align="center">

### ⭐ If you found this repository useful, consider giving it a Star.

**Happy Learning 🚀**

</div>
