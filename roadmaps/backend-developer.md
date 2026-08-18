# Backend Developer Roadmap

> A complete roadmap from Junior to Staff Backend Engineer

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    BACKEND DEVELOPER                         │
                           │                    Junior → Staff                            │
                           └─────────────────────────────────────────────────────────────┘
                                                    │
          ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
          │                                         │                                         │
          ▼                                         ▼                                         ▼
   ┌──────────────┐                        ┌──────────────┐                        ┌──────────────┐
   │   INTERN /   │                        │    JUNIOR     │                        │    INTERN     │
   │  BEGINNER    │                        │   DEVELOPER   │                        │   (0-6 mo)    │
   └──────┬───────┘                        └──────┬───────┘                        └──────────────┘
          │                                         │
          ▼                                         ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              FOUNDATIONS (6-12 months)                                       │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Programming Language  │  Linux  │  Git  │  HTTP/HTTPS  │  Data Structures  │  Algorithms   │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              LANGUAGE PATHS (12-24 months)                                   │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐ │
   │    │    NODE.JS      │    │     PYTHON      │    │       GO        │    │      JAVA       │ │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │ │
   │    │  • Express      │    │  • Django       │    │  • Gin/Echo     │    │  • Spring Boot  │ │
   │    │  • NestJS       │    │  • FastAPI      │    │  • Goroutines   │    │  • Spring Cloud │ │
   │    │  • TypeORM      │    │  • SQLAlchemy   │    │  • Channels     │    │  • Hibernate    │ │
   │    │  • Mongoose     │    │  • Celery       │    │  • GORM         │    │  • Maven/Gradle │ │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘    └─────────────────┘ │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              DATABASES & CACHING (18-24 months)                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  PostgreSQL  │  MySQL  │  MongoDB  │  Redis  │  Elasticsearch  │  DynamoDB  │  Cassandra    │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              ADVANCED (24-36 months)                                         │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  API Design  │  Auth  │  Message Queues  │  Docker  │  CI/CD  │  Testing  │  Monitoring     │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SENIOR (3-5 years)                                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  System Design  │  Microservices  │  Distributed Systems  │  Performance  │  Security       │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              STAFF+ (5+ years)                                               │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Architecture  │  Technical Strategy  │  Platform Engineering  │  Innovation  │  Mentoring  │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Stage 1: Foundations (0-12 months)

### Skills Checklist

- [ ] **Programming Language** (Choose one to start)
  - [ ] Variables, data types, control structures
  - [ ] Functions and scope
  - [ ] Object-oriented programming
  - [ ] Error handling
  - [ ] File I/O
  - [ ] Modules and packages

- [ ] **Linux Fundamentals**
  - [ ] Command line basics
  - [ ] File system navigation
  - [ ] Process management
  - [ ] User permissions
  - [ ] Shell scripting basics
  - [ ] Package management (apt/yum)

- [ ] **Git Version Control**
  - [ ] Basic commands (init, add, commit, push, pull)
  - [ ] Branching and merging
  - [ ] Conflict resolution
  - [ ] Git flow / GitHub flow
  - [ ] Pull requests and code review

- [ ] **HTTP/HTTPS**
  - [ ] HTTP methods (GET, POST, PUT, DELETE, PATCH)
  - [ ] Status codes (2xx, 3xx, 4xx, 5xx)
  - [ ] Headers and cookies
  - [ ] REST principles
  - [ ] TLS/SSL basics

- [ ] **Data Structures**
  - [ ] Arrays and linked lists
  - [ ] Stacks and queues
  - [ ] Hash tables
  - [ ] Trees (binary, BST, AVL)
  - [ ] Graphs basics
  - [ ] Heaps

- [ ] **Algorithms**
  - [ ] Sorting (merge, quick, heap)
  - [ ] Searching (binary search)
  - [ ] Big O notation
  - [ ] Recursion
  - [ ] Basic dynamic programming

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| The Linux Command Line | Book | Free | https://linuxcommand.org/tlcl.php |
| Pro Git | Book | Free | https://git-scm.com/book |
| MIT OpenCourseWare | Course | Free | https://ocw.mit.edu |
| LeetCode | Practice | Free/Paid | https://leetcode.com |
| NeetCode | Practice | Free/Paid | https://neetcode.io |
| System Design Primer | GitHub | Free | https://github.com/donnemartin/system-design-primer |

### Project Ideas

1. **CLI Tool** - Build a command-line tool (file organizer, task manager)
2. **Simple Web Server** - HTTP server from scratch (no framework)
3. **URL Shortener** - Basic CRUD API with a database
4. **File Storage Service** - Upload, download, list files
5. **Markdown Parser** - Parse markdown to HTML

---

## Stage 2: Language-Specific Paths (12-24 months)

### Node.js Path

- [ ] **Node.js Core**
  - [ ] Event loop and async I/O
  - [ ] Streams and buffers
  - [ ] File system operations
  - [ ] Child processes
  - [ ] Cluster module

- [ ] **Express.js**
  - [ ] Routing and middleware
  - [ ] Error handling
  - [ ] Template engines
  - [ ] Static files serving

- [ ] **NestJS**
  - [ ] Modules, controllers, services
  - [ ] Dependency injection
  - [ ] Guards and interceptors
  - [ ] Pipes and filters
  - [ ] Microservices transport

- [ ] **ORM/ODM**
  - [ ] TypeORM / Prisma
  - [ ] Mongoose (MongoDB)
  - [ ] Database migrations
  - [ ] Query optimization

### Python Path

- [ ] **Python Core**
  - [ ] Pythonic idioms
  - [ ] Generators and decorators
  - [ ] Context managers
  - [ ] Type hints
  - [ ] Virtual environments

- [ ] **Django**
  - [ ] Models and ORM
  - [ ] Views and URL routing
  - [ ] Templates
  - [ ] Admin interface
  - [ ] Django REST Framework

- [ ] **FastAPI**
  - [ ] Pydantic models
  - [ ] Path operations
  - [ ] Dependency injection
  - [ ] Background tasks
  - [ ] WebSocket support

- [ ] **Async Python**
  - [ ] asyncio
  - [ ] aiohttp
  - [ ] Celery for task queues

### Go Path

- [ ] **Go Core**
  - [ ] Goroutines and channels
  - [ ] Interfaces
  - [ ] Error handling patterns
  - [ ] Concurrency patterns
  - [ ] Context package

- [ ] **Web Frameworks**
  - [ ] Gin / Echo / Fiber
  - [ ] Middleware patterns
  - [ ] Template rendering

- [ ] **Go Ecosystem**
  - [ ] GORM (ORM)
  - [ ] go-kit / go-micro
  - [ ] Protocol Buffers
  - [ ] Testing with testify

### Java Path

- [ ] **Java Core**
  - [ ] JVM internals
  - [ ] Collections framework
  - [ ] Concurrency (ExecutorService, CompletableFuture)
  - [ ] Streams API
  - [ ] Modules (Java 9+)

- [ ] **Spring Boot**
  - [ ] Dependency injection
  - [ ] Spring MVC
  - [ ] Spring Data JPA
  - [ ] Spring Security
  - [ ] Spring Cloud (microservices)

- [ ] **Build Tools**
  - [ ] Maven / Gradle
  - [ ] Dependency management
  - [ ] Plugin ecosystem

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Node.js Official Docs | Documentation | Free | https://nodejs.org |
| Django Official Tutorial | Tutorial | Free | https://docs.djangoproject.com |
| Go Tour | Interactive | Free | https://go.dev/tour |
| Spring Official Guides | Tutorials | Free | https://spring.io/guides |
| Designing Data-Intensive Apps | Book | Paid | https://dataintensive.net |
| High Performance Browser Networking | Book | Free | https://hpbn.co |

### Project Ideas

1. **RESTful API** - Full CRUD with authentication and pagination
2. **Real-time Chat Server** - WebSocket implementation
3. **Task Queue System** - Background job processing with retries
4. **Blog API** - Posts, comments, tags, user roles
5. **Rate Limiter** - Token bucket or sliding window implementation

---

## Stage 3: Databases & Data (18-24 months)

### Skills Checklist

- [ ] **Relational Databases**
  - [ ] PostgreSQL / MySQL
  - [ ] SQL queries (JOINs, subqueries, CTEs)
  - [ ] Indexing strategies
  - [ ] Transactions and ACID
  - [ ] Normalization (1NF, 2NF, 3NF)
  - [ ] Query optimization and EXPLAIN
  - [ ] Stored procedures and triggers

- [ ] **NoSQL Databases**
  - [ ] MongoDB (document store)
  - [ ] Redis (key-value, caching)
  - [ ] Elasticsearch (search engine)
  - [ ] DynamoDB (key-value)
  - [ ] Cassandra (wide-column)

- [ ] **Caching**
  - [ ] Redis / Memcached
  - [ ] Cache strategies (write-through, write-behind, cache-aside)
  - [ ] Cache invalidation patterns
  - [ ] CDN caching

- [ ] **ORM/ODM Patterns**
  - [ ] Active Record vs Data Mapper
  - [ ] N+1 query problem
  - [ ] Lazy vs eager loading
  - [ ] Connection pooling

### Project Ideas

1. **Data Pipeline** - ETL process with multiple data sources
2. **Search Service** - Full-text search with Elasticsearch
3. **Caching Layer** - Implement Redis caching for an API
4. **Database Migration Tool** - Schema versioning and migration

---

## Stage 4: Advanced Backend (24-36 months)

### Skills Checklist

- [ ] **API Design**
  - [ ] RESTful API proven patterns
  - [ ] GraphQL (queries, mutations, subscriptions)
  - [ ] gRPC and Protocol Buffers
  - [ ] API versioning strategies
  - [ ] API documentation (OpenAPI/Swagger)
  - [ ] Rate limiting and throttling
  - [ ] Pagination (cursor vs offset)

- [ ] **Authentication & Authorization**
  - [ ] JWT tokens
  - [ ] OAuth 2.0 / OpenID Connect
  - [ ] Session-based auth
  - [ ] RBAC / ABAC
  - [ ] API keys and HMAC

- [ ] **Message Queues**
  - [ ] RabbitMQ
  - [ ] Apache Kafka
  - [ ] Amazon SQS
  - [ ] Pub/Sub patterns
  - [ ] Dead letter queues
  - [ ] Event sourcing basics

- [ ] **Testing**
  - [ ] Unit testing
  - [ ] Integration testing
  - [ ] API testing
  - [ ] Load testing (k6, JMeter)
  - [ ] Mocking and test doubles
  - [ ] Test containers

- [ ] **Docker**
  - [ ] Container fundamentals
  - [ ] Dockerfile proven patterns
  - [ ] Multi-stage builds
  - [ ] Docker Compose
  - [ ] Container security

- [ ] **CI/CD**
  - [ ] GitHub Actions / GitLab CI
  - [ ] Build pipelines
  - [ ] Automated testing
  - [ ] Deployment strategies (blue-green, canary)
  - [ ] Artifact management

- [ ] **Monitoring & Observability**
  - [ ] Logging (structured logging)
  - [ ] Metrics (Prometheus, Grafana)
  - [ ] Distributed tracing (Jaeger, Zipkin)
  - [ ] Alerting strategies
  - [ ] Error tracking (Sentry)

### Project Ideas

1. **Microservice Application** - 3-5 services with API gateway
2. **Event-Driven System** - Kafka/RabbitMQ with multiple consumers
3. **GraphQL API** - Schema design, resolvers, dataloaders
4. **CI/CD Pipeline** - Automated build, test, deploy workflow

---

## Stage 5: Senior Backend (3-5 years)

### Skills Checklist

- [ ] **System Design**
  - [ ] Scalability patterns
  - [ ] Load balancing
  - [ ] Database sharding and replication
  - [ ] CAP theorem
  - [ ] Consistent hashing
  - [ ] Rate limiting at scale

- [ ] **Microservices**
  - [ ] Service decomposition
  - [ ] Service mesh (Istio, Linkerd)
  - [ ] API gateway patterns
  - [ ] Saga pattern
  - [ ] Circuit breaker pattern
  - [ ] Service discovery

- [ ] **Distributed Systems**
  - [ ] Consensus algorithms (Raft, Paxos)
  - [ ] Distributed transactions
  - [ ] Eventual consistency
  - [ ] CQRS pattern
  - [ ] Distributed caching

- [ ] **Performance**
  - [ ] Profiling tools
  - [ ] Database query optimization
  - [ ] Connection pooling
  - [ ] Async processing
  - [ ] Caching strategies at scale

- [ ] **Security**
  - [ ] OWASP Top 10
  - [ ] Input validation
  - [ ] SQL injection prevention
  - [ ] Secrets management
  - [ ] Security headers

### Project Ideas

1. **Distributed Task Scheduler** - Fault-tolerant, horizontally scalable
2. **Real-time Analytics Platform** - Stream processing, aggregation
3. **Multi-tenant SaaS Backend** - Tenant isolation, resource management

---

## Stage 6: Staff+ Backend Engineer (5+ years)

### Skills Checklist

- [ ] **Architecture**
  - [ ] Domain-Driven Design (DDD)
  - [ ] Hexagonal / Clean Architecture
  - [ ] Event-driven architecture
  - [ ] Platform engineering
  - [ ] API strategy

- [ ] **Technical Strategy**
  - [ ] Technology radar
  - [ ] Migration planning
  - [ ] Technical debt management
  - [ ] Build vs buy decisions
  - [ ] Cost optimization

- [ ] **Leadership**
  - [ ] Architecture decision records
  - [ ] Technical RFC process
  - [ ] Cross-team coordination
  - [ ] Vendor evaluation
  - [ ] Incident management

- [ ] **Innovation**
  - [ ] Serverless architecture
  - [ ] Edge computing
  - [ ] AI/ML integration
  - [ ] WebAssembly for backend
  - [ ] Green computing

---

## Interview Preparation

### Common Interview Topics

1. **Data Structures & Algorithms**
   - Arrays, strings, hash maps
   - Trees and graphs
   - Dynamic programming
   - System design problems

2. **Language-Specific**
   - Node.js: Event loop, streams, clustering
   - Python: GIL, generators, decorators
   - Go: Goroutines, channels, interfaces
   - Java: JVM, concurrency, generics

3. **System Design**
   - Design a URL shortener
   - Design a chat system
   - Design a news feed
   - Design a rate limiter
   - Design a distributed cache

4. **Database Questions**
   - Index optimization
   - Query performance
   - Schema design
   - Replication and sharding

5. **Behavioral**
   - Technical decision examples
   - Incident response stories
   - Mentoring experiences

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Junior | 0-2 | $80,000 | $60K - $100K | $65K - $90K |
| Mid | 2-4 | $115,000 | $90K - $140K | $95K - $130K |
| Senior | 4-7 | $155,000 | $130K - $195K | $130K - $175K |
| Staff | 7-10 | $205,000 | $175K - $260K | $170K - $230K |
| Principal | 10+ | $260,000 | $220K - $350K | $210K - $290K |

*Note: Backend roles typically command 5-10% higher than frontend at equivalent levels.*

---

## 中文版本 - 后端开发路线图

### 概述

这是一份从后端初级工程师到高级技术专家的完整成长路线图，涵盖 Node.js、Python、Go、Java 四大技术栈。

### 阶段一：基础入门（0-12个月）

**必学技能：**
- [ ] 编程语言基础（选择一门：JavaScript/Python/Go/Java）
- [ ] Linux 命令行基础
- [ ] Git 版本控制
- [ ] HTTP/HTTPS 协议
- [ ] 数据结构与算法基础

**推荐学习资源：**
- 《算法导论》/ LeetCode 刷题
- MIT 公开课（计算机科学导论）
- Linux 命令行大全

**练手项目：**
1. 命令行工具（文件管理、任务管理）
2. 简单 HTTP 服务器（不使用框架）
3. URL 短链接服务

### 阶段二：语言深入（12-24个月）

**Node.js 路线：**
- [ ] 事件循环与异步 I/O
- [ ] Express/NestJS 框架
- [ ] TypeORM/Prisma ORM
- [ ] 流（Streams）和缓冲区

**Python 路线：**
- [ ] Django/FastAPI 框架
- [ ] SQLAlchemy ORM
- [ ] Celery 异步任务
- [ ] asyncio 编程

**Go 路线：**
- [ ] Goroutines 和 Channels
- [ ] Gin/Echo 框架
- [ ] GORM ORM
- [ ] 并发模式

**Java 路线：**
- [ ] Spring Boot 框架
- [ ] Spring Cloud 微服务
- [ ] Maven/Gradle 构建
- [ ] JVM 调优

### 阶段三：数据库与缓存（18-24个月）

- [ ] PostgreSQL/MySQL 关系型数据库
- [ ] MongoDB/Redis NoSQL 数据库
- [ ] SQL 优化与索引策略
- [ ] 缓存策略（穿透、雪崩、击穿）
- [ ] 数据库事务与 ACID

### 阶段四：进阶技能（24-36个月）

- [ ] API 设计（REST、GraphQL、gRPC）
- [ ] 认证授权（JWT、OAuth 2.0）
- [ ] 消息队列（RabbitMQ、Kafka）
- [ ] Docker 容器化
- [ ] CI/CD 持续集成
- [ ] 监控与可观测性

### 阶段五：高级后端（3-5年）

- [ ] 系统设计（扩展性、负载均衡、分库分表）
- [ ] 微服务架构（服务拆分、服务网格、API 网关）
- [ ] 分布式系统（一致性算法、分布式事务）
- [ ] 性能优化（数据库优化、异步处理）
- [ ] 安全防护（OWASP Top 10、SQL 注入防护）

### 阶段六：技术专家（5年以上）

- [ ] 领域驱动设计（DDD）
- [ ] 六边形/整洁架构
- [ ] 技术战略规划
- [ ] 平台工程
- [ ] 技术领导力

### 薪资参考（人民币/年）

| 级别 | 经验 | 一线城市 | 二线城市 | 远程 |
|------|------|----------|----------|------|
| 初级 | 0-2年 | 18-30万 | 12-20万 | 15-25万 |
| 中级 | 2-4年 | 30-50万 | 20-35万 | 25-40万 |
| 高级 | 4-7年 | 50-80万 | 35-55万 | 40-65万 |
| 资深 | 7-10年 | 80-120万 | 50-80万 | 60-100万 |
| 专家 | 10年+ | 120-180万 | 70-120万 | 80-140万 |

---

*Last updated: 2024*
*Contributions welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md)*
