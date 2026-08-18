# Security Engineer Roadmap

> A complete roadmap from Junior to Staff Security Engineer

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    SECURITY ENGINEER                         │
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
   │  Networking  │  Linux  │  Programming  │  Security Basics  │  Cryptography Intro            │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              CORE SECURITY (12-24 months)                                    │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐                        │
   │    │  APP SECURITY   │    │  INFRA SECURITY │    │  CLOUD SECURITY │                        │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │                        │
   │    │  • OWASP Top 10 │    │  • Network Sec  │    │  • AWS/GCP/Azure│                        │
   │    │  • SAST/DAST    │    │  • Firewall     │    │  • IAM          │                        │
   │    │  • Code Review  │    │  • IDS/IPS      │    │  • KMS          │                        │
   │    │  • Pen Testing  │    │  • Hardening    │    │  • CSPM         │                        │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘                        │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              DEVSECOPS (18-30 months)                                        │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  SAST  │  DAST  │  SCA  │  Container Security  │  IaC Security  │  CI/CD Security          │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              ADVANCED (24-36 months)                                         │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Incident Response  │  Threat Intelligence  │  Red Team  │  Forensics  │  Compliance        │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SENIOR (3-5 years)                                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Security Architecture  │  Risk Management  │  Governance  │  Leadership  │  Strategy       │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              STAFF+ (5+ years)                                               │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  CISO Track  │  Security Research  │  Program Management  │  Innovation  │  Mentoring       │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Stage 1: Foundations (0-12 months)

### Skills Checklist

- [ ] **Networking**
  - [ ] TCP/IP model and protocols
  - [ ] DNS (records, resolution, security)
  - [ ] HTTP/HTTPS (headers, methods, status codes)
  - [ ] TLS/SSL (certificates, handshake)
  - [ ] VPN technologies
  - [ ] Firewall concepts
  - [ ] Network segmentation
  - [ ] Subnetting

- [ ] **Linux Security**
  - [ ] File permissions and ownership
  - [ ] User and group management
  - [ ] SSH hardening
  - [ ] Firewall configuration (iptables, ufw)
  - [ ] Log analysis (/var/log, journalctl)
  - [ ] Service management
  - [ ] System hardening

- [ ] **Programming**
  - [ ] Python (scripting, automation)
  - [ ] Bash scripting
  - [ ] JavaScript (web security understanding)
  - [ ] SQL (injection understanding)
  - [ ] Go (security tools)

- [ ] **Security Fundamentals**
  - [ ] CIA triad (Confidentiality, Integrity, Availability)
  - [ ] Authentication vs authorization
  - [ ] Defense in depth
  - [ ] Least privilege principle
  - [ ] Security by design

- [ ] **Cryptography Basics**
  - [ ] Symmetric encryption (AES)
  - [ ] Asymmetric encryption (RSA, ECC)
  - [ ] Hashing (SHA-256, bcrypt)
  - [ ] Digital signatures
  - [ ] PKI (Public Key Infrastructure)
  - [ ] TLS/SSL certificates

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| OWASP | Documentation | Free | https://owasp.org |
| PortSwigger Web Security | Course | Free | https://portswigger.net/web-security |
| TryHackMe | Interactive | Free/Paid | https://tryhackme.com |
| HackTheBox | Interactive | Paid | https://www.hackthebox.com |
| Cybrary | Course | Free/Paid | https://www.cybrary.it |
| Security+ Study Guide | Book | Paid | Various |

### Project Ideas

1. **Vulnerability Scanner** - Basic port scanner in Python
2. **Password Manager** - Encrypted password storage
3. **Network Monitor** - Traffic analysis tool
4. **CTF Challenges** - Solve beginner CTF problems

---

## Stage 2: Core Security Skills (12-24 months)

### Application Security

- [ ] **OWASP Top 10**
  - [ ] Injection (SQL, NoSQL, LDAP)
  - [ ] Broken Authentication
  - [ ] Sensitive Data Exposure
  - [ ] XML External Entities (XXE)
  - [ ] Broken Access Control
  - [ ] Security Misconfiguration
  - [ ] Cross-Site Scripting (XSS)
  - [ ] Insecure Deserialization
  - [ ] Using Components with Known Vulnerabilities
  - [ ] Insufficient Logging & Monitoring

- [ ] **Security Testing**
  - [ ] SAST (Static Application Security Testing)
    - [ ] SonarQube
    - [ ] Semgrep
    - [ ] CodeQL
  - [ ] DAST (Dynamic Application Security Testing)
    - [ ] OWASP ZAP
    - [ ] Burp Suite
    - [ ] Nikto
  - [ ] SCA (Software Composition Analysis)
    - [ ] Snyk
    - [ ] Dependabot
    - [ ] OWASP Dependency-Check
  - [ ] Penetration testing basics

- [ ] **Web Security**
  - [ ] Content Security Policy (CSP)
  - [ ] CORS configuration
  - [ ] HTTP security headers
  - [ ] Cookie security
  - [ ] Session management
  - [ ] OAuth/OIDC security

### Infrastructure Security

- [ ] **Network Security**
  - [ ] Firewall rules and management
  - [ ] IDS/IPS (Snort, Suricata)
  - [ ] Network monitoring
  - [ ] VPN configuration
  - [ ] Zero Trust architecture
  - [ ] Network segmentation

- [ ] **System Hardening**
  - [ ] CIS benchmarks
  - [ ] Security baselines
  - [ ] Patch management
  - [ ] Vulnerability scanning (Nessus, OpenVAS)
  - [ ] Configuration management

- [ ] **Identity & Access Management**
  - [ ] Active Directory security
  - [ ] LDAP security
  - [ ] SSO implementation
  - [ ] MFA implementation
  - [ ] Privileged access management

### Cloud Security

- [ ] **AWS Security**
  - [ ] IAM policies and roles
  - [ ] VPC security
  - [ ] Security groups and NACLs
  - [ ] KMS (Key Management Service)
  - [ ] CloudTrail
  - [ ] GuardDuty
  - [ ] AWS WAF

- [ ] **GCP Security**
  - [ ] IAM and service accounts
  - [ ] VPC security
  - [ ] Cloud KMS
  - [ ] Security Command Center

- [ ] **Azure Security**
  - [ ] Azure AD
  - [ ] Network security groups
  - [ ] Key Vault
  - [ ] Azure Security Center

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| PortSwigger Academy | Interactive | Free | https://portswigger.net/web-security |
| OWASP WebGoat | Practice | Free | https://owasp.org/www-project-webgoat/ |
| AWS Security Specialty | Course | Paid | https://aws.amazon.com/certification |
| Cloud Security Alliance | Documentation | Free | https://cloudsecurityalliance.org |
| SANS Reading Room | Papers | Free | https://www.sans.org/reading-room/ |

### Project Ideas

1. **Security Audit** - Perform security assessment on a web app
2. **WAF Rules** - Create custom WAF rules
3. **Vulnerability Report** - Document findings with remediation
4. **Cloud Security Posture** - Implement security controls in cloud

---

## Stage 3: DevSecOps (18-30 months)

### Skills Checklist

- [ ] **Security in CI/CD**
  - [ ] SAST integration in pipelines
  - [ ] DAST automation
  - [ ] SCA scanning
  - [ ] Secret scanning
  - [ ] Policy enforcement
  - [ ] Security gates

- [ ] **Container Security**
  - [ ] Image scanning (Trivy, Snyk Container)
  - [ ] Runtime security (Falco)
  - [ ] Container hardening
  - [ ] Registry security
  - [ ] Dockerfile proven patterns

- [ ] **Kubernetes Security**
  - [ ] RBAC configuration
  - [ ] Network policies
  - [ ] Pod security standards
  - [ ] Secret management
  - [ ] Admission controllers
  - [ ] Service mesh security

- [ ] **Infrastructure as Code Security**
  - [ ] Terraform security (tfsec, Checkov)
  - [ ] CloudFormation security
  - [ ] Policy as Code (OPA, Sentinel)
  - [ ] Drift detection

- [ ] **Secrets Management**
  - [ ] HashiCorp Vault
  - [ ] AWS Secrets Manager
  - [ ] Azure Key Vault
  - [ ] Secret rotation
  - [ ] Dynamic secrets

### Project Ideas

1. **Secure Pipeline** - End-to-end secure CI/CD
2. **Policy as Code** - OPA policies for infrastructure
3. **Container Security** - Hardened container deployment
4. **Secrets Rotation** - Automated secret management

---

## Stage 4: Advanced Security (24-36 months)

### Skills Checklist

- [ ] **Incident Response**
  - [ ] Incident response plan
  - [ ] Detection and triage
  - [ ] Containment strategies
  - [ ] Eradication and recovery
  - [ ] Post-incident review
  - [ ] Tabletop exercises

- [ ] **Threat Intelligence**
  - [ ] Threat modeling (STRIDE, PASTA)
  - [ ] MITRE ATT&CK framework
  - [ ] IOC (Indicators of Compromise)
  - [ ] Threat feeds
  - [ ] Attribution analysis

- [ ] **Red Team / Offensive Security**
  - [ ] Penetration testing methodology
  - [ ] Exploitation frameworks (Metasploit)
  - [ ] Social engineering
  - [ ] Physical security testing
  - [ ] Bug bounty programs

- [ ] **Digital Forensics**
  - [ ] Disk forensics
  - [ ] Memory forensics
  - [ ] Network forensics
  - [ ] Log analysis
  - [ ] Chain of custody
  - [ ] Forensic tools (Autopsy, Volatility)

- [ ] **Compliance & Frameworks**
  - [ ] SOC 2
  - [ ] ISO 27001
  - [ ] NIST Cybersecurity Framework
  - [ ] PCI DSS
  - [ ] HIPAA
  - [ ] GDPR

### Project Ideas

1. **Incident Response Playbook** - Document response procedures
2. **Threat Model** - Security assessment of an application
3. **Penetration Test** - Full security assessment
4. **Compliance Framework** - Implement SOC 2 controls

---

## Stage 5: Senior Security Engineer (3-5 years)

### Skills Checklist

- [ ] **Security Architecture**
  - [ ] Zero Trust implementation
  - [ ] Security patterns and frameworks
  - [ ] Secure SDLC
  - [ ] Architecture review
  - [ ] Security design patterns

- [ ] **Risk Management**
  - [ ] Risk assessment methodology
  - [ ] Risk quantification
  - [ ] Risk treatment plans
  - [ ] Third-party risk management
  - [ ] Business continuity planning

- [ ] **Governance**
  - [ ] Security policies and standards
  - [ ] Security awareness training
  - [ ] Metrics and reporting
  - [ ] Audit management
  - [ ] Vendor security assessment

- [ ] **Leadership**
  - [ ] Team management
  - [ ] Budget planning
  - [ ] Stakeholder communication
  - [ ] Security roadmap
  - [ ] Cross-functional collaboration

### Project Ideas

1. **Security Program** - Build a security program from scratch
2. **Risk Assessment** - Enterprise-wide risk assessment
3. **Security Architecture** - Design secure infrastructure

---

## Stage 6: Staff+ Security Engineer (5+ years)

### Skills Checklist

- [ ] **CISO Track**
  - [ ] Security strategy
  - [ ] Board communication
  - [ ] Budget management
  - [ ] Regulatory compliance
  - [ ] Crisis management

- [ ] **Security Research**
  - [ ] Vulnerability research
  - [ ] Exploit development
  - [ ] Malware analysis
  - [ ] Security tool development
  - [ ] Academic publications

- [ ] **Program Management**
  - [ ] Security program maturity
  - [ ] Metrics-driven security
  - [ ] Security culture
  - [ ] Industry collaboration

- [ ] **Innovation**
  - [ ] AI/ML in security
  - [ ] Quantum computing threats
  - [ ] Zero Trust evolution
  - [ ] Security automation

---

## Certifications

| Certification | Provider | Difficulty | Value |
|---------------|----------|------------|-------|
| CompTIA Security+ | CompTIA | Medium | High (Entry) |
| CEH (Certified Ethical Hacker) | EC-Council | Medium | Medium |
| OSCP (Offensive Security) | OffSec | Very Hard | Very High |
| CISSP | (ISC)² | Hard | Very High |
| AWS Security Specialty | AWS | Hard | High |
| CCSP (Cloud Security) | (ISC)² | Hard | High |
| CISM | ISACA | Hard | High |

---

## Interview Preparation

### Common Interview Topics

1. **Application Security**
   - OWASP Top 10
   - XSS types and prevention
   - SQL injection prevention
   - Authentication vulnerabilities

2. **Infrastructure Security**
   - Network security architecture
   - Firewall design
   - Incident response
   - Vulnerability management

3. **Cloud Security**
   - IAM proven patterns
   - Security group design
   - Encryption at rest/in transit
   - Compliance requirements

4. **Security Scenarios**
   - Respond to a data breach
   - Design a secure architecture
   - Perform a security assessment
   - Prioritize vulnerabilities

5. **Technical Deep Dives**
   - Cryptography implementation
   - PKI and certificate management
   - Zero Trust architecture
   - DevSecOps pipeline design

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Junior | 0-2 | $75,000 | $55K - $95K | $60K - $85K |
| Mid | 2-4 | $115,000 | $90K - $140K | $95K - $130K |
| Senior | 4-7 | $160,000 | $135K - $200K | $135K - $185K |
| Staff | 7-10 | $215,000 | $185K - $270K | $180K - $250K |
| Principal | 10+ | $275,000 | $235K - $360K | $225K - $310K |

*Note: Security engineers are in extremely high demand. CISO roles at large companies can earn $500K+ total compensation.*

---

## 中文版本 - 安全工程师路线图

### 概述

这是一份从安全初级工程师到高级安全专家的完整成长路线图。

### 阶段一：基础入门（0-12个月）

**必学技能：**
- [ ] 网络安全基础（TCP/IP、DNS、HTTP/HTTPS、TLS/SSL）
- [ ] Linux 安全（权限管理、SSH 加固、防火墙）
- [ ] 编程基础（Python、Bash、SQL）
- [ ] 安全基础概念（CIA 三要素、最小权限原则）
- [ ] 密码学基础（对称/非对称加密、哈希、数字签名）

**推荐学习资源：**
- OWASP 官方文档
- PortSwigger Web Security Academy（免费）
- TryHackMe 在线实验平台
- 《白帽子讲 Web 安全》

**练手项目：**
1. Python 端口扫描器
2. 加密密码管理器
3. CTF 入门挑战

### 阶段二：核心安全技能（12-24个月）

**应用安全：**
- [ ] OWASP Top 10 漏洞（SQL 注入、XSS、CSRF 等）
- [ ] SAST/DAST/SCA 安全测试工具
- [ ] Burp Suite 渗透测试
- [ ] Web 安全防护（CSP、CORS、安全头）

**基础设施安全：**
- [ ] 网络安全（防火墙、IDS/IPS、零信任架构）
- [ ] 系统加固（CIS 基准、漏洞扫描）
- [ ] 身份与访问管理（IAM、SSO、MFA）

**云安全：**
- [ ] AWS/GCP/Azure 安全服务
- [ ] IAM 策略与角色
- [ ] KMS 密钥管理

### 阶段三：DevSecOps（18-30个月）

- [ ] CI/CD 安全集成（SAST、DAST、SCA）
- [ ] 容器安全（镜像扫描、运行时安全）
- [ ] Kubernetes 安全（RBAC、网络策略、Pod 安全）
- [ ] 基础设施即代码安全（tfsec、Checkov）
- [ ] 密钥管理（HashiCorp Vault）

### 阶段四：高级安全（24-36个月）

- [ ] 事件响应（检测、遏制、恢复、复盘）
- [ ] 威胁情报（STRIDE、MITRE ATT&CK）
- [ ] 红队/渗透测试（Metasploit、社会工程学）
- [ ] 数字取证（磁盘、内存、网络取证）
- [ ] 合规框架（SOC 2、ISO 27001、等保）

### 阶段五：高级安全工程师（3-5年）

- [ ] 安全架构设计（零信任、安全设计模式）
- [ ] 风险管理（风险评估、量化、处置）
- [ ] 安全治理（政策标准、安全培训、审计管理）
- [ ] 技术领导力

### 阶段六：安全专家（5年以上）

- [ ] CISO 路线（安全战略、董事会沟通、预算管理）
- [ ] 安全研究（漏洞研究、恶意软件分析）
- [ ] 安全项目管理（成熟度模型、指标驱动）

### 认证推荐

| 认证 | 提供方 | 难度 | 价值 |
|------|--------|------|------|
| CompTIA Security+ | CompTIA | 中等 | 高（入门） |
| CEH | EC-Council | 中等 | 中等 |
| OSCP | OffSec | 很高 | 很高 |
| CISSP | (ISC)² | 高 | 很高 |
| CISP | 中国信息安全测评中心 | 中等 | 高（国内） |

### 薪资参考（人民币/年）

| 级别 | 经验 | 一线城市 | 二线城市 | 远程 |
|------|------|----------|----------|------|
| 初级 | 0-2年 | 15-25万 | 10-18万 | 12-20万 |
| 中级 | 2-4年 | 25-40万 | 18-30万 | 20-35万 |
| 高级 | 4-7年 | 40-70万 | 30-50万 | 35-55万 |
| 资深 | 7-10年 | 70-110万 | 45-70万 | 50-90万 |
| 专家 | 10年+ | 110-170万 | 65-110万 | 75-140万 |

*注：安全工程师市场需求极高，CISO 级别年薪可达 200 万以上。*

---

*Last updated: 2024*
*Contributions welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md)*
