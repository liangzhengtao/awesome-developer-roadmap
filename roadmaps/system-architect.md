# System Architect Roadmap

> A complete roadmap from Senior Engineer to Principal/Staff Architect

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    SYSTEM ARCHITECT                          │
                           │                    Senior → Principal                        │
                           └─────────────────────────────────────────────────────────────┘
                                                    │
          ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
          │                                         │                                         │
          ▼                                         ▼                                         ▼
   ┌──────────────┐                        ┌──────────────┐                        ┌──────────────┐
   │   SENIOR     │                        │    STAFF      │                        │   PRINCIPAL   │
   │  ENGINEER    │                        │   ARCHITECT   │                        │   ARCHITECT   │
   │  (3-5 yrs)   │                        │   (5-8 yrs)   │                        │   (8+ yrs)    │
   └──────┬───────┘                        └──────┬───────┘                        └──────────────┘
          │                                         │
          ▼                                         ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              FOUNDATIONS (Transition from Senior)                            │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  System Design  │  Architecture Patterns  │  Trade-offs  │  Communication  │  Leadership    │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              ARCHITECTURE PATTERNS (6-18 months)                             │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐                        │
   │    │   MONOLITHIC    │    │  MICROSERVICES  │    │   EVENT-DRIVEN  │                        │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │                        │
   │    │  • Modular Mono │    │  • Service Mesh │    │  • Event Sourcing│                       │
   │    │  • Clean Arch   │    │  • API Gateway  │    │  • CQRS         │                        │
   │    │  • Hexagonal    │    │  • Service Disc │    │  • Saga Pattern │                        │
   │    │  • DDD          │    │  • Circuit Break│    │  • Pub/Sub      │                        │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘                        │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              DISTRIBUTED SYSTEMS (12-24 months)                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  CAP Theorem  │  Consensus  │  Consistency  │  Partitioning  │  Replication  │  Sharding    │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SCALABILITY & PERFORMANCE (18-30 months)                        │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Load Balancing  │  Caching  │  CDN  │  Database Optimization  │  Async Processing          │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              CLOUD & INFRASTRUCTURE (24-36 months)                           │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Multi-Cloud  │  Kubernetes  │  Serverless  │  IaC  │  Observability  │  Cost Optimization  │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              ARCHITECTURE GOVERNANCE (30-42 months)                          │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  ADRs  │  RFCs  │  Architecture Reviews  │  Standards  │  Security  │  Compliance          │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              PRINCIPAL+ (5+ years as architect)                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Technology Strategy  │  Business Alignment  │  Innovation  │  Industry Leadership         │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## The Architect's Mindset

A system architect is not just a senior engineer who writes design docs. Key differences:

- **Think in trade-offs**, not in best solutions
- **Communicate in diagrams**, not just code
- **Consider operational concerns** from day one
- **Align technical decisions** with business goals
- **Manage complexity** rather than eliminate it
- **Document decisions** for future teams

---

## Stage 1: Architecture Foundations (Transition from Senior)

### Skills Checklist

- [ ] **System Design Fundamentals**
  - [ ] Requirements gathering (functional and non-functional)
  - [ ] High-level design
  - [ ] Component design
  - [ ] API design
  - [ ] Data model design
  - [ ] Capacity planning
  - [ ] Cost estimation

- [ ] **Architecture Patterns**
  - [ ] Monolithic architecture
  - [ ] Microservices architecture
  - [ ] Event-driven architecture
  - [ ] Serverless architecture
  - [ ] Hexagonal architecture
  - [ ] Clean architecture
  - [ ] Domain-Driven Design (DDD)

- [ ] **Design Principles**
  - [ ] SOLID principles
  - [ ] DRY, KISS, YAGNI
  - [ ] Separation of concerns
  - [ ] Single responsibility
  - [ ] Dependency inversion
  - [ ] Interface segregation

- [ ] **Communication Skills**
  - [ ] Technical writing
  - [ ] Diagram creation (C4 model, UML)
  - [ ] Presentation skills
  - [ ] Stakeholder management
  - [ ] Trade-off analysis documentation

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Designing Data-Intensive Applications | Book | Paid | https://dataintensive.net |
| System Design Primer | GitHub | Free | https://github.com/donnemartin/system-design-primer |
| Software Architecture Patterns | Book | Free | https://www.oreilly.com/content/software-architecture-patterns/ |
| Fundamentals of Software Architecture | Book | Paid | https://www.oreilly.com/library/view/fundamentals-of-software/9781663728357/ |
| Architecture Decision Records | Guide | Free | https://adr.github.io |

### Project Ideas

1. **Architecture Review** - Review and document an existing system
2. **ADRs** - Write Architecture Decision Records for past decisions
3. **System Design** - Design a complex system from scratch
4. **Migration Plan** - Plan a monolith to microservices migration

---

## Stage 2: Architecture Patterns (6-18 months)

### Skills Checklist

- [ ] **Microservices Architecture**
  - [ ] Service decomposition strategies
  - [ ] API Gateway pattern
  - [ ] Service discovery
  - [ ] Circuit breaker pattern
  - [ ] Saga pattern (choreography vs orchestration)
  - [ ] Service mesh (Istio, Linkerd)
  - [ ] Strangler fig pattern (migration)

- [ ] **Event-Driven Architecture**
  - [ ] Event sourcing
  - [ ] CQRS (Command Query Responsibility Segregation)
  - [ ] Pub/Sub patterns
  - [ ] Event streaming (Kafka)
  - [ ] Event schema evolution
  - [ ] Eventually consistent systems

- [ ] **Domain-Driven Design (DDD)**
  - [ ] Bounded contexts
  - [ ] Aggregates and entities
  - [ ] Value objects
  - [ ] Domain events
  - [ ] Ubiquitous language
  - [ ] Context mapping

- [ ] **API Design**
  - [ ] RESTful API design
  - [ ] GraphQL schema design
  - [ ] gRPC and Protocol Buffers
  - [ ] API versioning strategies
  - [ ] API security
  - [ ] API documentation

### Project Ideas

1. **Microservices System** - Design a multi-service application
2. **Event-Driven Platform** - Implement event sourcing with Kafka
3. **API Design** - Create a complete API design document

---

## Stage 3: Distributed Systems (12-24 months)

### Skills Checklist

- [ ] **Distributed System Concepts**
  - [ ] CAP theorem
  - [ ] PACELC theorem
  - [ ] Fallacies of distributed computing
  - [ ] Consistency models (strong, eventual, causal)
  - [ ] Consensus algorithms (Raft, Paxos)
  - [ ] Distributed transactions (2PC, Saga)

- [ ] **Data Distribution**
  - [ ] Sharding strategies
  - [ ] Replication (leader-follower, multi-leader)
  - [ ] Partitioning (hash, range, geo)
  - [ ] Consistent hashing
  - [ ] Vector clocks
  - [ ] CRDTs

- [ ] **Reliability Patterns**
  - [ ] Redundancy
  - [ ] Failover
  - [ ] Retry and backoff
  - [ ] Timeout patterns
  - [ ] Bulkhead pattern
  - [ ] Health checks

- [ ] **Messaging Systems**
  - [ ] Message queues (RabbitMQ, SQS)
  - [ ] Event streaming (Kafka, Kinesis)
  - [ ] Pub/Sub (Google Pub/Sub)
  - [ ] Dead letter queues
  - [ ] Message ordering
  - [ ] Exactly-once semantics

### Project Ideas

1. **Distributed Cache** - Design a consistent distributed cache
2. **Message Queue** - Implement a simple message queue
3. **Consensus Algorithm** - Implement Raft consensus

---

## Stage 4: Scalability & Performance (18-30 months)

### Skills Checklist

- [ ] **Load Balancing**
  - [ ] Load balancing algorithms (round-robin, least connections, hash)
  - [ ] L4 vs L7 load balancing
  - [ ] Health checks
  - [ ] Sticky sessions
  - [ ] Global load balancing

- [ ] **Caching**
  - [ ] Caching strategies (write-through, write-behind, cache-aside)
  - [ ] Cache invalidation
  - [ ] Multi-level caching
  - [ ] CDN caching
  - [ ] Browser caching
  - [ ] Distributed caching (Redis, Memcached)

- [ ] **Database Optimization**
  - [ ] Query optimization
  - [ ] Indexing strategies
  - [ ] Connection pooling
  - [ ] Read replicas
  - [ ] Database sharding
  - [ ] Polyglot persistence

- [ ] **Async Processing**
  - [ ] Message queues
  - [ ] Background jobs
  - [ ] Event-driven processing
  - [ ] Batch processing
  - [ ] Stream processing

- [ ] **Performance Engineering**
  - [ ] Load testing (k6, JMeter, Gatling)
  - [ ] Profiling
  - [ ] Capacity planning
  - [ ] Performance budgets
  - [ ] SLA definition

### Project Ideas

1. **High-Traffic System** - Design for 1M+ concurrent users
2. **Caching Architecture** - Multi-level caching strategy
3. **Performance Optimization** - Optimize a slow system

---

## Stage 5: Cloud & Infrastructure (24-36 months)

### Skills Checklist

- [ ] **Cloud Architecture**
  - [ ] AWS / GCP / Azure services
  - [ ] Multi-region deployment
  - [ ] Multi-cloud strategy
  - [ ] Cloud-native patterns
  - [ ] Well-Architected Framework

- [ ] **Kubernetes Architecture**
  - [ ] Cluster design
  - [ ] Namespace strategy
  - [ ] Resource management
  - [ ] Networking (CNI, service mesh)
  - [ ] Security (RBAC, network policies)
  - [ ] GitOps (ArgoCD, Flux)

- [ ] **Serverless Architecture**
  - [ ] FaaS (Lambda, Cloud Functions)
  - [ ] API Gateway
  - [ ] Event-driven serverless
  - [ ] Cold start optimization
  - [ ] Serverless trade-offs

- [ ] **Infrastructure as Code**
  - [ ] Terraform modules
  - [ ] Pulumi
  - [ ] Crossplane
  - [ ] GitOps workflows
  - [ ] Environment management

- [ ] **Observability**
  - [ ] Monitoring (Prometheus, Grafana)
  - [ ] Logging (ELK, Loki)
  - [ ] Tracing (Jaeger, OpenTelemetry)
  - [ ] Alerting strategies
  - [ ] SLO/SLI/SLA

- [ ] **Cost Optimization**
  - [ ] Resource rightsizing
  - [ ] Reserved instances
  - [ ] Spot instances
  - [ ] Cost allocation
  - [ ] FinOps practices

### Project Ideas

1. **Cloud Migration** - Plan migration from on-premise to cloud
2. **Multi-Region Architecture** - Design for high availability
3. **Cost Optimization** - Reduce cloud spending by 30%

---

## Stage 6: Architecture Governance (30-42 months)

### Skills Checklist

- [ ] **Architecture Decision Records (ADR)**
  - [ ] ADR format and templates
  - [ ] Decision-making process
  - [ ] Trade-off documentation
  - [ ] Review and approval workflow

- [ ] **Request for Comments (RFC)**
  - [ ] RFC process design
  - [ ] Technical proposals
  - [ ] Stakeholder feedback
  - [ ] Implementation tracking

- [ ] **Architecture Reviews**
  - [ ] Review process
  - [ ] Quality attributes assessment
  - [ ] Risk identification
  - [ ] Mitigation strategies

- [ ] **Standards & Guidelines**
  - [ ] Technology standards
  - [ ] Coding standards
  - [ ] API standards
  - [ ] Security standards
  - [ ] Documentation standards

- [ ] **Security Architecture**
  - [ ] Security patterns
  - [ ] Threat modeling
  - [ ] Zero Trust architecture
  - [ ] Compliance requirements

### Project Ideas

1. **ADR Repository** - Create and maintain ADRs
2. **Architecture Review Board** - Establish review process
3. **Technical Standards** - Define organization standards

---

## Stage 7: Principal+ Architect (5+ years)

### Skills Checklist

- [ ] **Technology Strategy**
  - [ ] Technology roadmap
  - [ ] Innovation pipeline
  - [ ] Build vs buy decisions
  - [ ] Vendor evaluation
  - [ ] Technology radar

- [ ] **Business Alignment**
  - [ ] Business domain understanding
  - [ ] Cost-benefit analysis
  - [ ] ROI of technical decisions
  - [ ] Stakeholder management
  - [ ] Executive communication

- [ ] **Organizational Impact**
  - [ ] Architecture community
  - [ ] Mentoring programs
  - [ ] Technical culture
  - [ ] Hiring strategy
  - [ ] Knowledge sharing

- [ ] **Industry Leadership**
  - [ ] Conference speaking
  - [ ] Technical writing
  - [ ] Open source contributions
  - [ ] Industry standards participation

---

## Key Architecture Documents

### 1. Architecture Decision Record (ADR)
```markdown
# ADR-001: Use PostgreSQL as Primary Database

## Status
Accepted

## Context
We need a relational database for our core application...

## Decision
We will use PostgreSQL 15 as our primary database...

## Consequences
- Positive: Strong ACID compliance, rich feature set
- Negative: Requires DBA expertise for tuning
- Risks: Single point of failure without proper replication
```

### 2. C4 Model Diagrams
- **Level 1**: System Context (big picture)
- **Level 2**: Container diagram (applications and data stores)
- **Level 3**: Component diagram (containers internals)
- **Level 4**: Code diagram (class level)

### 3. RFC Template
```markdown
# RFC: [Title]

## Summary
One paragraph explanation

## Motivation
Why are we doing this?

## Detailed Design
The design details

## Alternatives Considered
What other approaches were considered?

## Unresolved Questions
What needs to be figured out?
```

---

## Interview Preparation

### Common Interview Topics

1. **System Design**
   - Design a URL shortener
   - Design a social media feed
   - Design a chat system
   - Design a distributed cache
   - Design a video streaming platform
   - Design an e-commerce platform

2. **Architecture Discussion**
   - Monolith vs microservices trade-offs
   - Database selection criteria
   - Caching strategies
   - Message queue selection

3. **Technical Deep Dives**
   - CAP theorem applications
   - Consensus algorithms
   - Distributed transactions
   - Event sourcing patterns

4. **Leadership & Communication**
   - Stakeholder management
   - Technical decision-making
   - Conflict resolution
   - Mentoring experiences

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Senior | 4-7 | $165,000 | $140K - $200K | $140K - $185K |
| Staff | 7-10 | $220,000 | $190K - $275K | $185K - $255K |
| Principal | 10-15 | $285,000 | $245K - $370K | $240K - $330K |
| Distinguished | 15+ | $350,000 | $300K - $450K | $290K - $400K |
| Fellow | 20+ | $450,000+ | $400K - $600K+ | $380K - $500K+ |

*Note: Architecture roles at FAANG/MAANG companies often have total compensation 2-3x these base figures when including stock.*

---

## 中文版本 - 系统架构师路线图

### 概述

这是一份从高级工程师到首席架构师的完整成长路线图。系统架构师不仅需要深厚的技术功底，更需要出色的沟通能力和商业思维。

### 架构师的思维方式

- **权衡思维**：没有完美的方案，只有合适的权衡
- **图表思维**：用图表而非代码沟通设计
- **运维思维**：从第一天就考虑运维需求
- **业务对齐**：技术决策要与业务目标一致
- **复杂性管理**：管理而非消除复杂性
- **决策记录**：为未来团队记录决策过程

### 阶段一：架构基础（从高级工程师转型）

- [ ] 系统设计基础（需求分析、高层设计、容量规划）
- [ ] 架构模式（单体、微服务、事件驱动、Serverless）
- [ ] 设计原则（SOLID、DRY、KISS、YAGNI）
- [ ] 沟通技能（技术文档、C4 模型、利益相关者管理）

**推荐学习资源：**
- 《设计数据密集型应用》（DERTA）
- 《软件架构基础》
- System Design Primer（GitHub）
- 架构决策记录（ADR）模板

### 阶段二：架构模式（6-18个月）

- [ ] 微服务架构（服务拆分、API 网关、服务网格、Saga 模式）
- [ ] 事件驱动架构（事件溯源、CQRS、Pub/Sub）
- [ ] 领域驱动设计（DDD）（限界上下文、聚合、领域事件）
- [ ] API 设计（REST、GraphQL、gRPC）

### 阶段三：分布式系统（12-24个月）

- [ ] 分布式概念（CAP 定理、一致性模型、共识算法）
- [ ] 数据分布（分片、复制、分区、一致性哈希）
- [ ] 可靠性模式（冗余、故障转移、重试退避）
- [ ] 消息系统（消息队列、事件流、死信队列）

### 阶段四：扩展性与性能（18-30个月）

- [ ] 负载均衡（L4/L7、算法选择）
- [ ] 缓存策略（多级缓存、CDN、失效策略）
- [ ] 数据库优化（索引、读写分离、分库分表）
- [ ] 异步处理（消息队列、后台任务、流处理）
- [ ] 性能工程（压测、容量规划、SLA 定义）

### 阶段五：云与基础设施（24-36个月）

- [ ] 云架构（AWS/GCP/Azure、多云策略）
- [ ] Kubernetes 架构（集群设计、资源管理）
- [ ] Serverless 架构
- [ ] 基础设施即代码（Terraform、GitOps）
- [ ] 可观测性（监控、日志、链路追踪）
- [ ] 成本优化（FinOps）

### 阶段六：架构治理（30-42个月）

- [ ] 架构决策记录（ADR）
- [ ] RFC 技术提案流程
- [ ] 架构评审机制
- [ ] 技术标准与规范
- [ ] 安全架构

### 阶段七：首席架构师（5年以上）

- [ ] 技术战略规划（技术路线图、创新管道）
- [ ] 业务对齐（ROI 分析、利益相关者沟通）
- [ ] 组织影响力（架构社区、导师计划、技术文化）
- [ ] 行业领导力（技术大会、开源贡献）

### 关键架构文档

**架构决策记录（ADR）：**
```markdown
# ADR-001: 使用 PostgreSQL 作为主数据库

## 状态
已接受

## 背景
我们需要一个关系型数据库来支撑核心应用...

## 决策
使用 PostgreSQL 15 作为主数据库...

## 影响
- 正面：强 ACID 合规、功能丰富
- 负面：需要 DBA 专业技能进行调优
```

### 薪资参考（人民币/年）

| 级别 | 经验 | 一线城市 | 二线城市 | 远程 |
|------|------|----------|----------|------|
| 高级 | 4-7年 | 50-80万 | 35-55万 | 40-65万 |
| 资深 | 7-10年 | 80-130万 | 55-85万 | 60-100万 |
| 首席 | 10-15年 | 130-200万 | 85-130万 | 100-160万 |
| 杰出 | 15年+ | 200-300万 | 120-200万 | 150-250万 |

*注：大厂架构师总包（含股票）通常是上述数字的 2-3 倍。*

---

*Last updated: 2024*
*Contributions welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md)*
