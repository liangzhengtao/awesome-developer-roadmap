# Data Engineer Roadmap

> A complete roadmap from Junior to Staff Data Engineer

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    DATA ENGINEER                             │
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
   │  Python  │  SQL  │  Git  │  Linux  │  Data Modeling  │  Cloud Basics                        │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              DATA WAREHOUSING (12-24 months)                                 │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐                        │
   │    │   TRADITIONAL   │    │   MODERN DATA   │    │   LAKEHOUSE     │                        │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │                        │
   │    │  • Snowflake    │    │  • BigQuery     │    │  • Databricks   │                        │
   │    │  • Redshift     │    │  • Redshift     │    │  • Delta Lake   │                        │
   │    │  • Star Schema  │    │  • dbt          │    │  • Apache Iceberg│                       │
   │    │  • ETL          │    │  • ELT          │    │  • Apache Hudi  │                        │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘                        │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              DATA PIPELINES (18-30 months)                                   │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Apache Airflow  │  dbt  │  Kafka  │  Spark  │  Flink  │  Luigi                             │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              BIG DATA & STREAMING (24-36 months)                             │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Hadoop  │  Spark  │  Kafka  │  Flink  │  Hive  │  Presto  │  HDFS                          │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              DATA GOVERNANCE (30-42 months)                                  │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Data Quality  │  Data Catalog  │  Lineage  │  Privacy  │  Compliance  │  Master Data       │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SENIOR+ (4+ years)                                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Data Architecture  │  Platform Engineering  │  Strategy  │  Leadership  │  Innovation      │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Stage 1: Foundations (0-12 months)

### Skills Checklist

- [ ] **Python for Data**
  - [ ] Core Python (data types, control flow, functions)
  - [ ] Pandas (DataFrames, data manipulation)
  - [ ] NumPy (arrays, operations)
  - [ ] File I/O (CSV, JSON, Parquet)
  - [ ] Virtual environments
  - [ ] Error handling
  - [ ] Type hints

- [ ] **SQL Mastery**
  - [ ] Basic queries (SELECT, WHERE, ORDER BY)
  - [ ] JOINs (INNER, LEFT, RIGHT, FULL)
  - [ ] Aggregations (GROUP BY, HAVING)
  - [ ] Window functions (ROW_NUMBER, RANK, LAG, LEAD)
  - [ ] Common Table Expressions (CTEs)
  - [ ] Subqueries
  - [ ] Indexes and query optimization
  - [ ] Stored procedures
  - [ ] Schema design (normalization, denormalization)

- [ ] **Data Modeling**
  - [ ] Star schema
  - [ ] Snowflake schema
  - [ ] Fact and dimension tables
  - [ ] Slowly changing dimensions (SCD)
  - [ ] Entity-relationship diagrams
  - [ ] Data vault modeling

- [ ] **Linux & Command Line**
  - [ ] File operations
  - [ ] Text processing (grep, awk, sed)
  - [ ] Shell scripting
  - [ ] Process management
  - [ ] Cron jobs

- [ ] **Git Version Control**
  - [ ] Basic commands
  - [ ] Branching strategies
  - [ ] Pull requests

- [ ] **Cloud Basics**
  - [ ] AWS / GCP / Azure overview
  - [ ] Object storage (S3, GCS)
  - [ ] Compute services
  - [ ] IAM and security

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| SQLZoo | Interactive | Free | https://sqlzoo.net |
| Mode SQL Tutorial | Tutorial | Free | https://mode.com/sql-tutorial |
| Data Engineering Zoomcamp | Course | Free | https://github.com/DataTalksClub/data-engineering-zoomcamp |
| Fundamentals of Data Engineering | Book | Paid | https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/ |
| The Data Warehouse Toolkit | Book | Paid | https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books/ |

### Project Ideas

1. **SQL Analysis** - Complex queries on a real dataset
2. **Data Pipeline** - Simple ETL with Python
3. **Data Model** - Design a star schema for e-commerce
4. **CSV Processing** - Clean and transform messy data

---

## Stage 2: Data Warehousing (12-24 months)

### Skills Checklist

- [ ] **Data Warehouse Platforms**
  - [ ] Snowflake
    - [ ] Virtual warehouses
    - [ ] Data sharing
    - [ ] Time travel
    - [ ] Cloning
    - [ ] Snowpipe (auto-ingest)
  - [ ] BigQuery
    - [ ] Datasets and tables
    - [ ] Partitioning and clustering
    - [ ] BigQuery ML
    - [ ] Scheduled queries
  - [ ] Amazon Redshift
    - [ ] Cluster management
    - [ ] Distribution keys
    - [ ] Sort keys
    - [ ] Spectrum (data lake queries)

- [ ] **ETL/ELT Patterns**
  - [ ] ETL (Extract, Transform, Load)
  - [ ] ELT (Extract, Load, Transform)
  - [ ] CDC (Change Data Capture)
  - [ ] Batch vs streaming
  - [ ] Data quality checks

- [ ] **dbt (data build tool)**
  - [ ] Models and materializations
  - [ ] Tests and documentation
  - [ ] Sources and exposures
  - [ ] Macros and packages
  - [ ] Incremental models
  - [ ] Snapshots

- [ ] **Data Formats**
  - [ ] Parquet
  - [ ] Avro
  - [ ] ORC
  - [ ] JSON / JSONL
  - [ ] Delta Lake
  - [ ] Apache Iceberg

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Snowflake Documentation | Docs | Free | https://docs.snowflake.com |
| dbt Learn | Course | Free | https://courses.getdbt.com |
| BigQuery Documentation | Docs | Free | https://cloud.google.com/bigquery/docs |
| The Analytics Engineering Course | Course | Paid | https://www.analyticshero.com |

### Project Ideas

1. **Data Warehouse** - Build a complete warehouse on Snowflake/BigQuery
2. **dbt Project** - Transform raw data into analytics-ready models
3. **Data Pipeline** - End-to-end ETL with data quality checks
4. **Dashboard** - Connect warehouse to BI tool (Looker, Tableau)

---

## Stage 3: Data Pipelines (18-30 months)

### Skills Checklist

- [ ] **Apache Airflow**
  - [ ] DAGs (Directed Acyclic Graphs)
  - [ ] Operators and tasks
  - [ ] Scheduling
  - [ ] XComs (data passing)
  - [ ] Connections and hooks
  - [ ] Sensors
  - [ ] Dynamic task mapping
  - [ ] Error handling and retries

- [ ] **Stream Processing**
  - [ ] Apache Kafka
    - [ ] Producers and consumers
    - [ ] Topics and partitions
    - [ ] Consumer groups
    - [ ] Kafka Connect
    - [ ] Schema Registry
    - [ ] Kafka Streams
  - [ ] Apache Flink
    - [ ] DataStream API
    - [ ] Table API
    - [ ] Windowing
    - [ ] State management
    - [ ] Exactly-once semantics

- [ ] **Batch Processing**
  - [ ] Apache Spark
    - [ ] RDDs and DataFrames
    - [ ] Spark SQL
    - [ ] PySpark
    - [ ] Catalyst optimizer
    - [ ] Partitioning strategies

- [ ] **Orchestration Patterns**
  - [ ] Idempotency
  - [ ] Backfilling
  - [ ] Data partitioning
  - [ ] Dependency management
  - [ ] Monitoring and alerting

### Project Ideas

1. **Airflow Pipeline** - Multi-step data pipeline with dependencies
2. **Streaming Pipeline** - Real-time data processing with Kafka
3. **Spark ETL** - Large-scale data transformation
4. **CDC Pipeline** - Change data capture from database to warehouse

---

## Stage 4: Big Data & Streaming (24-36 months)

### Skills Checklist

- [ ] **Hadoop Ecosystem**
  - [ ] HDFS (Hadoop Distributed File System)
  - [ ] MapReduce
  - [ ] YARN
  - [ ] Hive (SQL on Hadoop)
  - [ ] HBase (NoSQL)
  - [ ] ZooKeeper

- [ ] **Advanced Spark**
  - [ ] Spark Streaming
  - [ ] MLlib
  - [ ] GraphX
  - [ ] Performance tuning
  - [ ] Cluster management

- [ ] **Query Engines**
  - [ ] Presto / Trino
  - [ ] Apache Drill
  - [ ] Amazon Athena
  - [ ] Interactive queries

- [ ] **Data Lake**
  - [ ] Data lake architecture
  - [ ] Schema evolution
  - [ ] Data lake vs warehouse
  - [ ] Lakehouse architecture
  - [ ] Table formats (Delta, Iceberg, Hudi)

- [ ] **Performance Optimization**
  - [ ] Partitioning strategies
  - [ ] Bucketing
  - [ ] Indexing
  - [ ] Caching
  - [ ] Query optimization
  - [ ] Resource management

### Project Ideas

1. **Data Lake** - Build a data lake on S3/GCS
2. **Streaming Analytics** - Real-time dashboards with Kafka + Spark
3. **Query Optimization** - Performance tuning exercise
4. **Multi-source Integration** - Combine data from multiple sources

---

## Stage 5: Data Governance (30-42 months)

### Skills Checklist

- [ ] **Data Quality**
  - [ ] Data validation frameworks
  - [ ] Great Expectations
  - [ ] Data profiling
  - [ ] Anomaly detection
  - [ ] Data contracts
  - [ ] SLA management

- [ ] **Data Catalog**
  - [ ] Metadata management
  - [ ] Data discovery
  - [ ] Business glossary
  - [ ] Technical metadata
  - [ ] Tools (DataHub, Amundsen, OpenMetadata)

- [ ] **Data Lineage**
  - [ ] Column-level lineage
  - [ ] Impact analysis
  - [ ] Dependency tracking
  - [ ] Tools (OpenLineage, Marquez)

- [ ] **Privacy & Compliance**
  - [ ] GDPR / CCPA compliance
  - [ ] Data classification
  - [ ] PII handling
  - [ ] Data masking
  - [ ] Consent management
  - [ ] Retention policies

- [ ] **Master Data Management**
  - [ ] Golden records
  - [ ] Data matching
  - [ ] Data stewardship
  - [ ] Reference data

### Project Ideas

1. **Data Quality Framework** - Automated data validation
2. **Data Catalog** - Self-service data discovery
3. **Lineage Tracker** - Track data from source to dashboard
4. **Privacy Compliance** - PII detection and masking

---

## Stage 6: Senior+ Data Engineer (4+ years)

### Skills Checklist

- [ ] **Data Architecture**
  - [ ] Modern data stack design
  - [ ] Lambda vs Kappa architecture
  - [ ] Data mesh principles
  - [ ] Domain-driven data
  - [ ] Self-serve data platform

- [ ] **Platform Engineering**
  - [ ] Internal developer platform
  - [ ] Self-service data tools
  - [ ] Infrastructure as code
  - [ ] Cost optimization
  - [ ] Multi-cloud strategy

- [ ] **Leadership**
  - [ ] Technical mentoring
  - [ ] Architecture reviews
  - [ ] Vendor evaluation
  - [ ] Data strategy
  - [ ] Stakeholder management

- [ ] **Innovation**
  - [ ] Real-time ML pipelines
  - [ ] DataOps practices
  - [ ] Data mesh implementation
  - [ ] AI/ML data infrastructure
  - [ ] Open source contributions

---

## Certifications

| Certification | Provider | Difficulty | Value |
|---------------|----------|------------|-------|
| Snowflake SnowPro | Snowflake | Medium | High |
| Google Professional Data Engineer | Google | Hard | Very High |
| AWS Data Analytics Specialty | AWS | Hard | High |
| Databricks Certified Engineer | Databricks | Medium | High |
| dbt Analytics Engineering | dbt Labs | Medium | Medium |

---

## Interview Preparation

### Common Interview Topics

1. **SQL**
   - Complex JOINs and subqueries
   - Window functions
   - Query optimization
   - Schema design

2. **Data Modeling**
   - Star vs snowflake schema
   - Slowly changing dimensions
   - Fact vs dimension tables
   - Normalization vs denormalization

3. **System Design**
   - Design a data pipeline
   - Design a data warehouse
   - Design a real-time analytics system
   - Design a data lake

4. **Python**
   - Pandas operations
   - Data transformation
   - Error handling
   - Testing

5. **Architecture**
   - ETL vs ELT trade-offs
   - Batch vs streaming
   - Data lake vs warehouse
   - Data mesh principles

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Junior | 0-2 | $80,000 | $60K - $100K | $65K - $90K |
| Mid | 2-4 | $120,000 | $95K - $145K | $100K - $135K |
| Senior | 4-7 | $160,000 | $135K - $200K | $135K - $185K |
| Staff | 7-10 | $210,000 | $180K - $265K | $175K - $240K |
| Principal | 10+ | $265,000 | $225K - $350K | $215K - $300K |

*Note: Data Engineering is one of the fastest-growing roles in tech with strong demand.*

---

## 中文版本 - 数据工程师路线图

### 概述

这是一份从数据工程初级工程师到高级技术专家的完整成长路线图。

### 阶段一：基础入门（0-12个月）

**必学技能：**
- [ ] Python 数据处理（Pandas、NumPy）
- [ ] SQL 精通（JOIN、窗口函数、CTE、索引优化）
- [ ] 数据建模（星型模型、雪花模型）
- [ ] Linux 命令行
- [ ] 云服务基础

**推荐学习资源：**
- SQLZoo 在线练习
- 《数据仓库工具箱》（Kimball）
- Data Engineering Zoomcamp（免费）

**练手项目：**
1. SQL 复杂查询分析
2. Python ETL 数据管道
3. 电商星型模型设计

### 阶段二：数据仓库（12-24个月）

- [ ] Snowflake / BigQuery / Redshift
- [ ] dbt 数据转换工具
- [ ] ETL/ELT 模式
- [ ] 数据格式（Parquet、Delta Lake）

**练手项目：**
1. 完整数据仓库搭建
2. dbt 项目（增量模型、测试、文档）

### 阶段三：数据管道（18-30个月）

- [ ] Apache Airflow 任务编排
- [ ] Apache Kafka 流处理
- [ ] Apache Spark 批处理
- [ ] 流批一体架构

**练手项目：**
1. Airflow 多步骤数据管道
2. Kafka 实时数据流处理
3. Spark 大规模数据转换

### 阶段四：大数据与流处理（24-36个月）

- [ ] Hadoop 生态（HDFS、Hive、HBase）
- [ ] 高级 Spark（Streaming、MLlib）
- [ ] 查询引擎（Presto/Trino）
- [ ] 数据湖架构（Delta Lake、Iceberg）

### 阶段五：数据治理（30-42个月）

- [ ] 数据质量（Great Expectations、数据合同）
- [ ] 数据目录（DataHub、Amundsen）
- [ ] 数据血缘（OpenLineage）
- [ ] 隐私合规（GDPR、PII 处理）

### 阶段六：高级数据工程师（4年以上）

- [ ] 数据架构（Data Mesh、Lambda/Kappa）
- [ ] 平台工程（自助数据平台）
- [ ] 数据战略规划
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
