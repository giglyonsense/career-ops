# SIVA SARAN GONDI (SHARAN)

**Senior Software Engineer — Backend & Data Platform**

Bengaluru, India | +91 9482268123 | gondi.sharan@gmail.com | linkedin.com/in/gondisharan
Open to: Remote | Hybrid | Bengaluru on-site

---

## PROFESSIONAL SUMMARY

Senior Software Engineer with 8+ years of experience building high-throughput distributed systems and data platforms at scale. Proven track record of designing, optimizing, and shipping production-grade backend systems and real-time streaming pipelines that serve enterprise-scale e-commerce and content workloads.

At Sitecore, engineered a data streaming pipeline (Apache Flink) that scaled throughput 8.6x — from 5,000 to 43,000 records per minute — and cut a catalog processing job from 4 hours to 35 minutes. Core expertise spans Apache Kafka, Apache Flink, Apache Spark, Apache Airflow, Python, Java, Golang, and cloud infrastructure on AWS and Azure. Experienced in microservices architecture, ETL pipeline development, real-time data processing, and backend system design for large-scale distributed environments.

Seeking a Senior or Staff Software Engineer role at a top-tier product company where I can architect systems that handle billions to trillions of records, with a path to technical leadership.

---

## TECHNICAL SKILLS

**Programming Languages:** Python, Java, Golang (Go), Bash / Shell Scripting

**Big Data & Streaming:** Apache Kafka, Apache Flink, Apache Spark, SparkSQL, Apache Airflow, Stream Processing, Batch Processing, ETL (Extract Transform Load), Real-time Data Processing, Event-Driven Architecture

**Databases & Storage:** PostgreSQL, MySQL, Snowflake, MongoDB, DynamoDB, Elasticsearch, Redis, Delta Lake, AWS Redshift

**Cloud — AWS:** EC2, S3, ECS, Lambda, AWS Batch, CloudWatch, IAM, Redshift
**Cloud — Azure:** Azure Databricks, Azure Data Factory, Azure EventHub, Azure Blob Storage, Hadoop (on-prem to cloud migration)

**Backend & Architecture:** Distributed Systems, Microservices Architecture, REST API Design and Development, Backend System Architecture, Data Warehousing, Data Pipeline Development, High-Throughput Systems, Performance Optimization

**DevOps & Tooling:** Docker, CI/CD, Git, Jira, Apigee, Apache Unomi
**ML & Analytics:** Machine Learning (XGBoost, Random Forest, Linear Regression), Feature Engineering, Big Data Analytics, Data Analysis

**IDEs & Tools:** IntelliJ, PyCharm, GoLand, VS Code, DBeaver, Jupyter, Google Colab

---

## PROFESSIONAL EXPERIENCE

### Sitecore | Senior Software Engineer
**Bengaluru, India | Mar 2022 – Present**
*Data Platform Team — Sitecore Search (AI-powered content discovery & personalization platform)*

- **Scaled a production Apache Flink streaming pipeline 8.6x**, increasing throughput from 5,000 to 43,000 records per minute (RPM), directly improving SLA compliance for enterprise e-commerce and content customers.
- **Reduced catalog sync processing time by 85%** (4 hours → 35 minutes) by re-architecting and migrating a catalog syncing job from a legacy e-commerce framework to a new content search platform.
- **Designed and built an end-to-end offline transaction ingestion workflow**, transforming raw offline store transaction data into structured user sessions and actionable analytics for enterprise e-commerce clients.
- **Engineered a document denormalization feature** enabling seamless incremental updates across interconnected dependent entities; automated update propagation for all related documents, eliminating manual re-indexing overhead — adopted by multiple enterprise e-commerce clients.
- **Conducted comprehensive load testing** across a distributed system of 7 microservices and associated subsystems; identified, profiled, and resolved critical performance bottlenecks, improving system reliability and throughput.
- **Resolved a cloud security vulnerability** in Apache Airflow's AWS resource access by migrating from IAM Users to IAM Roles, eliminating manual key rotation overhead and enforcing least-privilege access control.
- **Developed analytics batch processing scripts** to compute engagement metrics (views, clicks, CVR, CTR) for a suite of AI-powered personalization widgets (trending items, new arrivals, best sellers, top deals) — enabling clients to measure and optimize recommendation performance at scale.
- **Built a real-time Flink streaming job** for an in-house Segment Builder tool that ingests e-commerce user activity events and writes them to Apache Unomi (open-source CDP) in real time, powering customer segmentation workflows.

*Key technologies: Apache Flink, Apache Kafka, Apache Airflow, Python, Java, AWS (ECS, S3, Lambda, Batch, CloudWatch, IAM), Microservices, Elasticsearch, Docker, CI/CD*

---

### Neudesic (an IBM Company) | Senior Consultant
**Bengaluru, India | Jun 2021 – Mar 2022**
*BI Architecture Modernization — On-premises Hadoop to Azure Cloud migration*

- **Migrated 10+ heterogeneous data sources** (batch and streaming pipelines) from on-premises Hadoop infrastructure to Azure Cloud, modernizing the BI architecture stack end-to-end.
- **Upgraded real-time data streaming** by transitioning from StreamSets to Azure EventHub-capture, significantly improving scalability, fault tolerance, and operational efficiency.
- **Refactored existing Oozie/Hue workflows** to be compatible with Apache Spark, enhancing data processing throughput and enabling complex analytical transformations at scale.
- **Orchestrated cloud data ingestion and workflow automation** using Azure Data Factory (ADF) for ETL pipeline management and Azure Databricks for distributed Spark-based data processing.

*Key technologies: PySpark, Apache Spark, Spark Streaming, Azure Data Factory, Azure Databricks, Azure EventHub, Hadoop, Oozie, SQL, Python*

---

### Infosys Limited | Specialist Programmer
**Bengaluru, India | Nov 2017 – Jun 2021**
*Multiple enterprise-scale data engineering and backend development engagements*

**Backend API Development — Labor Management System (LMS)**
- **Designed and built 3 production REST APIs** within a Labor Management System, enabling external vendor integrations to access critical labor data (shifts, absences, time-tracking) at scale.
- **Implemented AWS Lambda functions** for server-side input validation and automated file generation, improving data accuracy and reducing downstream processing errors.
- **Deployed and managed API gateway** via Apigee with OAuth2 client-credentials security, enabling secure, controlled access for external stakeholders through API-Central.

**Big Data Engineering — B2B Data Extraction Platform (Azure Databricks / Delta Lake)**
- **Built an automated B2B data extraction platform** on Azure Databricks using a high-performance Delta Lake layer, eliminating a manual extract-and-deliver process for retailer-specific data feeds.
- **Implemented custom SQL and PySpark queries** on Delta Lake to generate B2B data extracts in predefined formats and delivery windows, ensuring accurate and timely delivery to downstream systems.
- **Automated delivery of compressed data extracts** to OneDrive, SharePoint, and Amazon S3, streamlining data accessibility across business units.
- **Achieved 70% reduction in manual effort** through full end-to-end automation of the extract generation and delivery pipeline.

**Machine Learning — Europe Dynamic Pricing Model**
- **Developed and deployed a machine learning model** to predict logistics carrier rate ranges (lower, expected, upper bound) from historical transaction data, replacing manual rate estimation.
- **Executed full ML lifecycle**: feature engineering on raw data → model evaluation (XGBoost, Random Forest, Multiple Linear Regression) → production integration.
- **Achieved ~96% model accuracy**; integrated the final model into the client's live order processing system for real-time rate prediction.

**Cloud Infrastructure & Automation**
- **Migrated a production AWS Redshift cluster** along with associated Informatica ETL scripts, mappings, and workflows across AWS accounts, delivering a **28% reduction in cluster maintenance costs**.
- **Automated creation of ~7,000 unique onboarding graphs** on a client's in-house ETL tool using Python scripting with REST API integration, reducing provisioning time from weeks to hours.
- **Implemented a Power Automate workflow** for automated storage remediation, cleaning up stale files in OneDrive and SharePoint to manage storage constraints without manual intervention.

*Key technologies: Python, Java, PySpark, Apache Spark, Delta Lake, Azure Databricks, AWS Redshift, AWS Lambda, AWS S3, Apigee, REST APIs, Informatica ETL, XGBoost, Random Forest, SQL, Power Automate*

---

## EDUCATION

**Bachelor of Engineering — Computer Science & Engineering**
Visvesvaraya Technological University, Bengaluru, India | 2013 – 2017

---

## KEYWORDS (ATS OPTIMIZATION)

Distributed Systems · Data Platform · Backend Engineering · Real-time Data Processing · Stream Processing · Batch Processing · Apache Kafka · Apache Flink · Apache Spark · Apache Airflow · ETL · Data Pipelines · Data Engineering · Big Data · Python · Java · Golang · Go · AWS · Azure · Microservices · REST API · High Throughput · Scalability · Performance Optimization · Cloud Infrastructure · Snowflake · PostgreSQL · MongoDB · DynamoDB · Elasticsearch · Redis · Docker · CI/CD · Machine Learning · MLOps · Delta Lake · Databricks · Data Warehousing · Senior Software Engineer · Staff Software Engineer · Data Engineer · Platform Engineer
