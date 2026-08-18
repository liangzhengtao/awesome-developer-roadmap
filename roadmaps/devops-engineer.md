# DevOps Engineer Roadmap

> A complete roadmap from Junior to Staff DevOps/SRE Engineer

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    DEVOPS ENGINEER                           │
                           │                    Junior → Staff                            │
                           └─────────────────────────────────────────────────────────────┘
                                                    │
          ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
          │                                         │                                         │
          ▼                                         ▼                                         ▼
   ┌──────────────┐                        ┌──────────────┐                        ┌──────────────┐
   │   INTERN /   │                        │    JUNIOR     │                        │    INTERN     │
   │  BEGINNER    │                        │   ENGINEER    │                        │   (0-6 mo)    │
   └──────┬───────┘                        └──────┬───────┘                        └──────────────┘
          │                                         │
          ▼                                         ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              FOUNDATIONS (6-12 months)                                       │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Linux  │  Networking  │  Scripting  │  Git  │  Cloud Basics  │  Containers Intro            │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              CONTAINERS & ORCHESTRATION (12-24 months)                       │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐                        │
   │    │     DOCKER      │    │  KUBERNETES     │    │   PODMAN        │                        │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │                        │
   │    │  • Containers   │    │  • Pods/Deploy  │    │  • Rootless     │                        │
   │    │  • Images       │    │  • Services     │    │  • Docker-compat│                        │
   │    │  • Compose      │    │  • ConfigMap    │    │  • Pods         │                        │
   │    │  • Networking   │    │  • Helm Charts  │    │  • K8s compat   │                        │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘                        │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              CI/CD & AUTOMATION (18-30 months)                               │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  GitHub Actions  │  GitLab CI  │  Jenkins  │  ArgoCD  │  Terraform  │  Ansible              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              CLOUD PLATFORMS (24-36 months)                                  │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  AWS  │  GCP  │  Azure  │  Serverless  │  Managed Services  │  Cost Optimization           │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              OBSERVABILITY & RELIABILITY (30-42 months)                      │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Prometheus  │  Grafana  │  ELK Stack  │  Jaeger  │  PagerDuty  │  SLO/SLI/SLA             │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SENIOR+ (4+ years)                                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Platform Engineering  │  GitOps  │  Service Mesh  │  FinOps  │  Security (DevSecOps)      │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Stage 1: Foundations (0-12 months)

### Skills Checklist

- [ ] **Linux Administration**
  - [ ] Command line proficiency
  - [ ] File system hierarchy
  - [ ] Process management (systemd, cron)
  - [ ] User and group management
  - [ ] Package management (apt, yum, dnf)
  - [ ] Log management (/var/log, journalctl)
  - [ ] SSH key management
  - [ ] Firewall basics (iptables, ufw)

- [ ] **Networking**
  - [ ] TCP/IP model
  - [ ] DNS (records, resolution)
  - [ ] HTTP/HTTPS
  - [ ] Load balancing concepts
  - [ ] VPN basics
  - [ ] Subnetting and CIDR
  - [ ] OSI model

- [ ] **Scripting**
  - [ ] Bash scripting
  - [ ] Python scripting
  - [ ] AWK/SED
  - [ ] Regular expressions
  - [ ] YAML/JSON parsing

- [ ] **Version Control**
  - [ ] Git fundamentals
  - [ ] Branching strategies
  - [ ] Git hooks
  - [ ] Monorepo vs polyrepo

- [ ] **Cloud Basics**
  - [ ] IaaS, PaaS, SaaS concepts
  - [ ] Virtual machines
  - [ ] Storage types (block, file, object)
  - [ ] Basic cloud networking

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Linux Command Line | Book | Free | https://linuxcommand.org |
| Networking Fundamentals | Course | Free | https://www.youtube.com/watch?v=qiQR5rTSshw |
| AWS Free Tier | Hands-on | Free | https://aws.amazon.com/free |
| DevOps Roadmap | Guide | Free | https://roadmap.sh/devops |
| KodeKloud | Courses | Paid | https://kodekloud.com |
| A Cloud Guru | Courses | Paid | https://acloudguru.com |

### Project Ideas

1. **Bash Automation Scripts** - Server monitoring, backup automation
2. **Static Website Hosting** - Nginx/Apache configuration
3. **CI Pipeline** - GitHub Actions for a simple project
4. **Monitoring Dashboard** - Basic server metrics collection

---

## Stage 2: Containers & Orchestration (12-24 months)

### Skills Checklist

- [ ] **Docker**
  - [ ] Container concepts (images, containers, volumes)
  - [ ] Dockerfile proven patterns
  - [ ] Multi-stage builds
  - [ ] Docker Compose
  - [ ] Container networking
  - [ ] Container security scanning
  - [ ] Registry management (Docker Hub, ECR, GCR)

- [ ] **Kubernetes**
  - [ ] Cluster architecture
  - [ ] Pods, ReplicaSets, Deployments
  - [ ] Services (ClusterIP, NodePort, LoadBalancer)
  - [ ] ConfigMaps and Secrets
  - [ ] Persistent Volumes
  - [ ] Namespaces
  - [ ] Ingress controllers
  - [ ] Helm package manager
  - [ ] kubectl commands
  - [ ] RBAC and security

- [ ] **Container Alternatives**
  - [ ] Podman (rootless containers)
  - [ ] containerd
  - [ ] CRI-O

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Docker Official Docs | Documentation | Free | https://docs.docker.com |
| Kubernetes Official Docs | Documentation | Free | https://kubernetes.io/docs |
| KodeKloud Kubernetes | Course | Paid | https://kodekloud.com |
| KillerCoda | Interactive | Free | https://killercoda.com |
| Certified Kubernetes Admin | Certification | Paid | https://www.cncf.io/certification/cka/ |

### Project Ideas

1. **Multi-Container App** - Docker Compose with frontend, backend, database
2. **Kubernetes Cluster** - Deploy apps on local K8s (minikube/kind)
3. **Helm Chart** - Package an application for K8s deployment
4. **Container Registry** - Private registry with image scanning

---

## Stage 3: CI/CD & Automation (18-30 months)

### Skills Checklist

- [ ] **CI/CD Platforms**
  - [ ] GitHub Actions
    - [ ] Workflow syntax
    - [ ] Matrix builds
    - [ ] Caching strategies
    - [ ] Self-hosted runners
    - [ ] Reusable workflows
  - [ ] GitLab CI
    - [ ] .gitlab-ci.yml
    - [ ] Stages and jobs
    - [ ] Artifacts and caching
    - [ ] Runners
  - [ ] Jenkins
    - [ ] Pipeline as code
    - [ ] Jenkinsfile
    - [ ] Shared libraries
    - [ ] Blue Ocean

- [ ] **Infrastructure as Code (IaC)**
  - [ ] Terraform
    - [ ] HCL syntax
    - [ ] State management
    - [ ] Modules
    - [ ] Workspaces
    - [ ] Remote backends
    - [ ] Import existing resources
  - [ ] Pulumi (alternative)
  - [ ] AWS CloudFormation
  - [ ] Crossplane

- [ ] **Configuration Management**
  - [ ] Ansible
    - [ ] Playbooks
    - [ ] Roles
    - [ ] Inventory
    - [ ] Galaxy
  - [ ] Chef / Puppet (legacy)

- [ ] **GitOps**
  - [ ] ArgoCD
  - [ ] Flux
  - [ ] GitOps principles
  - [ ] Declarative infrastructure

- [ ] **Artifact Management**
  - [ ] Nexus / Artifactory
  - [ ] Container registries
  - [ ] Package registries (npm, PyPI)

### Project Ideas

1. **Full CI/CD Pipeline** - Build, test, deploy automation
2. **Terraform Modules** - Reusable infrastructure modules
3. **GitOps Workflow** - ArgoCD with K8s deployment
4. **Ansible Playbook** - Server provisioning automation

---

## Stage 4: Cloud Platforms (24-36 months)

### Skills Checklist

- [ ] **AWS** (Most popular)
  - [ ] EC2, ECS, EKS
  - [ ] S3, RDS, DynamoDB
  - [ ] VPC, Security Groups, IAM
  - [ ] Lambda, API Gateway
  - [ ] CloudWatch, CloudTrail
  - [ ] Route 53
  - [ ] SQS, SNS
  - [ ] Cost Explorer and budgets

- [ ] **GCP**
  - [ ] Compute Engine, GKE
  - [ ] Cloud Storage, Cloud SQL
  - [ ] VPC, IAM
  - [ ] Cloud Functions
  - [ ] Cloud Monitoring

- [ ] **Azure**
  - [ ] Virtual Machines, AKS
  - [ ] Blob Storage, Azure SQL
  - [ ] Virtual Network, Azure AD
  - [ ] Azure Functions
  - [ ] Azure Monitor

- [ ] **Serverless**
  - [ ] Lambda/Cloud Functions
  - [ ] API Gateway
  - [ ] Step Functions
  - [ ] Cold start optimization
  - [ ] Serverless frameworks

- [ ] **Managed Services**
  - [ ] Managed Kubernetes (EKS/GKE/AKS)
  - [ ] Managed databases
  - [ ] Message queues (SQS, Pub/Sub)
  - [ ] CDN (CloudFront, Cloud CDN)

### Project Ideas

1. **Multi-Cloud Setup** - Deploy across AWS and GCP
2. **Serverless Application** - Lambda + API Gateway + DynamoDB
3. **Infrastructure Repository** - Terraform for complete environment
4. **Cost Optimization** - Implement tagging, budgets, rightsizing

---

## Stage 5: Observability & Reliability (30-42 months)

### Skills Checklist

- [ ] **Monitoring**
  - [ ] Prometheus
    - [ ] PromQL
    - [ ] Alert rules
    - [ ] Service discovery
    - [ ] Exporters
  - [ ] Grafana
    - [ ] Dashboard design
    - [ ] Alerting
    - [ ] Data source integration
  - [ ] CloudWatch / Cloud Monitoring

- [ ] **Logging**
  - [ ] ELK Stack (Elasticsearch, Logstash, Kibana)
  - [ ] Fluentd / Fluent Bit
  - [ ] Loki
  - [ ] Structured logging
  - [ ] Log aggregation patterns

- [ ] **Tracing**
  - [ ] Jaeger / Zipkin
  - [ ] OpenTelemetry
  - [ ] Distributed tracing
  - [ ] Span and context propagation

- [ ] **Reliability Engineering**
  - [ ] SLO/SLI/SLA definitions
  - [ ] Error budgets
  - [ ] Incident response
  - [ ] Post-incident reviews
  - [ ] Chaos engineering basics
  - [ ] Disaster recovery planning

- [ ] **Alerting**
  - [ ] PagerDuty / OpsGenie
  - [ ] Alert fatigue management
  - [ ] Escalation policies
  - [ ] On-call proven patterns

### Project Ideas

1. **Observability Stack** - Prometheus + Grafana + Loki + Jaeger
2. **SLO Dashboard** - Track and visualize service reliability
3. **Chaos Engineering** - Netflix Chaos Monkey style experiments
4. **Incident Management** - Automated response and escalation

---

## Stage 6: Senior+ DevOps (4+ years)

### Skills Checklist

- [ ] **Platform Engineering**
  - [ ] Internal developer platforms
  - [ ] Self-service infrastructure
  - [ ] Developer portals (Backstage)
  - [ ] Golden paths
  - [ ] Platform as a product

- [ ] **Service Mesh**
  - [ ] Istio / Linkerd
  - [ ] Traffic management
  - [ ] mTLS
  - [ ] Observability integration

- [ ] **FinOps**
  - [ ] Cost allocation
  - [ ] Rightsizing
  - [ ] Reserved instances / Savings Plans
  - [ ] Spot instances
  - [ ] Cost anomaly detection

- [ ] **DevSecOps**
  - [ ] Security scanning in CI/CD
  - [ ] Container image scanning
  - [ ] Secrets management (Vault)
  - [ ] Policy as code (OPA, Kyverno)
  - [ ] Compliance automation

- [ ] **Leadership**
  - [ ] Architecture decisions
  - [ ] Team mentoring
  - [ ] Vendor evaluation
  - [ ] Capacity planning
  - [ ] Business continuity planning

---

## Certifications

| Certification | Provider | Difficulty | Value |
|---------------|----------|------------|-------|
| AWS Solutions Architect | AWS | Medium | High |
| Certified Kubernetes Admin (CKA) | CNCF | Hard | Very High |
| Certified Kubernetes Security (CKS) | CNCF | Hard | High |
| HashiCorp Terraform Associate | HashiCorp | Medium | Medium |
| Google Cloud Professional | Google | Hard | High |
| Azure Solutions Architect | Microsoft | Medium | High |

---

## Interview Preparation

### Common Interview Topics

1. **Linux & Networking**
   - Process management and troubleshooting
   - DNS resolution flow
   - TCP vs UDP
   - HTTP/2 and HTTP/3

2. **Containers & Kubernetes**
   - Container vs VM
   - K8s architecture
   - Pod lifecycle
   - Service types and networking
   - Helm chart design

3. **CI/CD & IaC**
   - Pipeline design
   - Terraform state management
   - GitOps workflow
   - Blue-green vs canary deployment

4. **System Design**
   - Design a CI/CD pipeline for microservices
   - Design a monitoring system
   - Design a disaster recovery plan
   - Design a multi-region deployment

5. **Troubleshooting**
   - Debug a failing pod
   - Investigate high CPU/memory usage
   - Network connectivity issues
   - Performance bottleneck analysis

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Junior | 0-2 | $75,000 | $55K - $95K | $60K - $85K |
| Mid | 2-4 | $110,000 | $85K - $135K | $90K - $125K |
| Senior | 4-7 | $150,000 | $125K - $185K | $125K - $170K |
| Staff | 7-10 | $200,000 | $170K - $250K | $165K - $225K |
| Principal | 10+ | $250,000 | $210K - $330K | $200K - $280K |

*Note: DevOps/SRE roles are among the highest-paid engineering roles due to the critical nature of the work.*

---

## 中文版本 - DevOps 工程师路线图

### 概述

这是一份从 DevOps 初级工程师到高级 SRE/平台工程师的完整成长路线图。

### 阶段一：基础入门（0-12个月）

**必学技能：**
- [ ] Linux 系统管理（命令行、进程管理、用户权限）
- [ ] 网络基础（TCP/IP、DNS、HTTP）
- [ ] 脚本编程（Bash、Python）
- [ ] Git 版本控制
- [ ] 云服务基础概念

**推荐学习资源：**
- 《Linux 命令行大全》
- AWS 免费套餐实操
- KodeKloud 在线实验平台

**练手项目：**
1. Bash 自动化脚本（服务器监控、备份）
2. 静态网站托管（Nginx 配置）
3. GitHub Actions CI 流水线

### 阶段二：容器与编排（12-24个月）

- [ ] Docker 容器化（镜像、Compose、多阶段构建）
- [ ] Kubernetes 集群管理（Pod、Service、Deployment、Helm）
- [ ] 容器安全扫描
- [ ] 私有镜像仓库

**认证推荐：**
- CKA（Kubernetes 管理员）
- Docker Certified Associate

**练手项目：**
1. 多容器应用（Docker Compose 编排）
2. K8s 集群部署（minikube/kind）
3. Helm Chart 打包

### 阶段三：CI/CD 与自动化（18-30个月）

- [ ] GitHub Actions / GitLab CI
- [ ] Terraform 基础设施即代码
- [ ] Ansible 配置管理
- [ ] ArgoCD GitOps 工作流
- [ ] 制品管理（Nexus、容器镜像仓库）

### 阶段四：云平台（24-36个月）

- [ ] AWS 核心服务（EC2、S3、RDS、VPC、IAM）
- [ ] GCP / Azure 基础
- [ ] Serverless 架构（Lambda、API Gateway）
- [ ] 托管 Kubernetes（EKS/GKE/AKS）
- [ ] 成本优化

**认证推荐：**
- AWS Solutions Architect
- HashiCorp Terraform Associate

### 阶段五：可观测性与可靠性（30-42个月）

- [ ] 监控（Prometheus、Grafana）
- [ ] 日志（ELK Stack、Loki）
- [ ] 链路追踪（Jaeger、OpenTelemetry）
- [ ] SLO/SLI/SLA 定义
- [ ] 事件响应与复盘
- [ ] 混沌工程

### 阶段六：高级 DevOps（4年以上）

- [ ] 平台工程（内部开发者平台、Backstage）
- [ ] 服务网格（Istio、Linkerd）
- [ ] FinOps 成本管理
- [ ] DevSecOps 安全自动化
- [ ] 技术领导力

### 薪资参考（人民币/年）

| 级别 | 经验 | 一线城市 | 二线城市 | 远程 |
|------|------|----------|----------|------|
| 初级 | 0-2年 | 18-28万 | 12-20万 | 15-22万 |
| 中级 | 2-4年 | 28-45万 | 20-32万 | 22-38万 |
| 高级 | 4-7年 | 45-75万 | 32-50万 | 38-60万 |
| 资深 | 7-10年 | 75-110万 | 50-75万 | 55-90万 |
| 专家 | 10年+ | 110-160万 | 65-100万 | 75-130万 |

---

*Last updated: 2024*
*Contributions welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md)*
