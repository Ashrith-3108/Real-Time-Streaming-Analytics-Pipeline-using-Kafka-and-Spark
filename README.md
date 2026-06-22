# ⚡ Real-Time Data Streaming & Processing Platform

### Kafka • Spark Structured Streaming • Debezium CDC • PostgreSQL • MySQL • Spring Boot • React

> Enterprise-grade real-time data engineering platform that captures database changes using Change Data Capture (CDC), streams events through Apache Kafka, processes data with Spark Structured Streaming, and delivers real-time analytics dashboards for business intelligence and operational monitoring.

![Kafka](https://img.shields.io/badge/Apache-Kafka-black)
![Spark](https://img.shields.io/badge/Apache-Spark-orange)
![Debezium](https://img.shields.io/badge/Debezium-CDC-red)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![MySQL](https://img.shields.io/badge/MySQL-Analytics-green)
![Spring Boot](https://img.shields.io/badge/SpringBoot-Backend-success)
![React](https://img.shields.io/badge/React-Frontend-blue)

---

# 📖 Overview

Modern organizations rely on real-time data processing to support operational analytics, fraud detection, customer monitoring, IoT workloads, and business intelligence.

This project demonstrates a complete end-to-end streaming data platform using:

* Apache Kafka
* Spark Structured Streaming
* Debezium CDC
* PostgreSQL
* MySQL
* Spring Boot
* React
* Docker

The system captures live database changes from PostgreSQL using Debezium Change Data Capture (CDC), streams events through Kafka topics, processes them using Spark Structured Streaming, stores aggregated analytics in MySQL, and presents insights through a real-time dashboard.

The architecture simulates production-grade streaming systems used in modern data-driven organizations.

---

# 🎯 Business Problem

Organizations generate thousands of transactions every second.

Traditional batch processing introduces delays in:

* Analytics
* Monitoring
* Reporting
* Alerting
* Business Decisions

This project solves the problem by enabling:

✅ Near real-time data ingestion

✅ Continuous stream processing

✅ Live dashboard updates

✅ Automated notifications

✅ Scalable event-driven architecture

---

# 🏗️ System Architecture

```text id="aw9z8w"
                    PostgreSQL Database
                           │
                           ▼
                  Debezium CDC Connector
                           │
                           ▼
                    Apache Kafka Topics
                           │
                           ▼
               Spark Structured Streaming
                           │
           ┌───────────────┴───────────────┐
           ▼                               ▼
      MySQL Analytics DB            Alert Engine
           │                               │
           ▼                               ▼
    Spring Boot APIs              Email Notifications
           │
           ▼
      React Dashboard
```

---

# 🚀 Key Features

## Change Data Capture (CDC)

Implemented using Debezium.

Features:

* Real-time database change capture
* Insert event tracking
* Update event tracking
* Event streaming without polling
* Low-latency synchronization

---

## Real-Time Data Streaming

Implemented using Apache Kafka.

Capabilities:

* High-throughput event ingestion
* Fault-tolerant messaging
* Topic-based architecture
* Distributed event processing
* Scalability and reliability

---

## Stream Processing

Implemented using Spark Structured Streaming.

Features:

* Continuous data consumption
* Event filtering
* Window aggregations
* Real-time metrics generation
* Stream transformations

---

## Analytics Layer

Generated business metrics including:

* Total Smartphones
* Phones Per Brand
* Phones Per SIM Type
* Maximum Price Analysis
* Maximum RAM Analysis
* Maximum Battery Analysis
* Screen Size Analytics
* Brand Performance Metrics

---

## Real-Time Dashboard

Provides:

* Live KPI Monitoring
* Interactive Visualizations
* Brand Analytics
* Device Distribution Insights
* Operational Monitoring

---

## Alerting System

Email notifications are triggered when predefined thresholds are exceeded.

Examples:

* Price Threshold Alert
* Inventory Alert
* Business Rule Violations

---

# 🛠 Technology Stack

## Data Engineering

* Apache Kafka
* Apache Spark
* Spark Structured Streaming
* Debezium CDC

## Programming Languages

* Python
* Java
* SQL
* JavaScript

## Databases

### Source Database

* PostgreSQL

### Analytics Database

* MySQL

## Backend

* Spring Boot
* REST APIs

## Frontend

* React.js
* HTML5
* CSS3

## DevOps

* Docker
* Docker Compose

## Development Tools

* IntelliJ IDEA
* VS Code
* PyCharm
* Git
* GitHub

---

# 📊 Data Pipeline Flow

```text id="9jqw7f"
Database Transaction
          │
          ▼
   Debezium CDC Event
          │
          ▼
      Kafka Topic
          │
          ▼
 Spark Streaming Job
          │
          ▼
 Business Aggregation
          │
          ▼
    MySQL Storage
          │
          ▼
   Spring Boot APIs
          │
          ▼
   React Dashboard
```

---

# ⚡ Streaming Analytics Implemented

## Aggregations

* Count by Brand
* Count by SIM Type
* Maximum Price per Brand
* Maximum RAM per Brand
* Maximum Battery per Brand
* Maximum Screen Size per SIM Type

## Statistical Metrics

* Total Devices
* Price Trends
* Device Distribution
* Product Analytics

---

# 🔒 Reliability & Scalability Features

### Kafka

* Fault Tolerance
* Event Persistence
* Horizontal Scalability

### Spark Streaming

* Distributed Processing
* Stateful Computation
* Stream Recovery

### Debezium CDC

* Guaranteed Change Capture
* Low-Latency Processing
* Consistent Event Delivery

### Docker

* Reproducible Deployments
* Environment Consistency

---

# 📈 Business Use Cases

This architecture can be extended for:

### E-Commerce

* Order Tracking
* Inventory Monitoring
* Sales Analytics

### Banking

* Fraud Detection
* Transaction Monitoring
* Risk Analytics

### Telecommunications

* Call Data Processing
* Customer Usage Analytics

### IoT

* Sensor Monitoring
* Real-Time Alerts

### Healthcare

* Patient Monitoring
* Medical Event Processing

---

# 📸 Dashboard Screenshots

Add screenshots for:

```markdown id="m0l0pz"
Dashboard Overview
Brand Analytics
Price Analytics
Streaming Metrics
Kafka Topics
Spark Job Monitoring
CDC Event Flow
Email Alerts
```

---

# 📂 Project Structure

```text id="r2h7fi"
Real-Time-Streaming-Kafka-Debezium-Spark/

│
├── postgres/
├── kafka/
├── debezium/
├── spark-streaming/
├── mysql-storage/
├── spring-boot-backend/
├── react-dashboard/
├── dashboards/
├── images/
├── docker-compose.yml
└── README.md
```

---

# 💼 Resume Project Description

### Real-Time Streaming Analytics Platform | Data Engineer

* Designed and implemented a real-time data engineering platform using Apache Kafka, Spark Structured Streaming, Debezium CDC, PostgreSQL, MySQL, Spring Boot, and React.
* Developed CDC-based event pipelines to capture database changes, stream events through Kafka, and process high-throughput data streams with low-latency analytics.
* Built scalable streaming workflows including filtering, aggregation, windowing, and real-time KPI generation for business intelligence applications.
* Implemented fault-tolerant event processing, automated monitoring, and dashboard visualization to support near real-time operational decision-making.

---

# 🎓 Skills Demonstrated

## Data Engineering

* Real-Time Data Processing
* Event-Driven Architecture
* CDC Pipelines
* Streaming Analytics
* ETL Development

## Big Data

* Apache Kafka
* Apache Spark
* Spark Structured Streaming

## Databases

* PostgreSQL
* MySQL
* Data Modeling

## Backend Engineering

* Spring Boot
* REST APIs

## Frontend Development

* React.js
* Dashboard Development

## DevOps

* Docker
* Containerization

---

# 🔮 Future Enhancements

* Apache Airflow Orchestration
* Kafka Streams
* Schema Registry
* Apache Flink Integration
* Cloud Deployment on AWS
* Kubernetes Deployment
* Grafana Monitoring
* Prometheus Metrics
* Delta Lake Integration
* Real-Time Machine Learning

---

# 🔍 ATS Keywords

Data Engineer, Apache Kafka, Spark Structured Streaming, Apache Spark, Debezium, CDC, Change Data Capture, Event Streaming, Real-Time Analytics, Data Pipeline, Streaming Architecture, PostgreSQL, MySQL, Spring Boot, React.js, ETL, Event-Driven Architecture, Distributed Systems, Big Data, Docker, Cloud Data Engineering, Streaming Data Processing, Low Latency Analytics.

---

# 👨‍💻 Author

**Vavillapally Ashrith**

B.Tech Artificial Intelligence & Machine Learning (2026)

Aspiring Data Engineer | Apache Kafka | Spark | Databricks | Cloud Data Engineering

📧 [ashrith.31083124@gmail.com](mailto:ashrith.31083124@gmail.com)

🔗 LinkedIn: linkedin.com/in/vavillapally-ashrith-9823482a1

💻 GitHub: github.com/Ashrith-3108
