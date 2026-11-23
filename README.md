# Nidhi Desai

**Senior Software Engineer | Trading Systems · Event-Driven Architecture · AI-Driven Engineering**

📧 **Email**: nidhi.desai990@gmail.com  
📍 **Location**: New York, NY  
🔗 **LinkedIn**: [linkedin.com/in/nidhi-desai-843b4a24](https://www.linkedin.com/in/nidhi-desai-843b4a24)  
📄 **Resume**: [Download PDF](Nidhi-Desai-Resume.pdf)  

---

## 👋 About

Senior Software Engineer with 9+ years building Java trading, brokerage, and payments systems on AWS and Kubernetes. I work across the order flow, including the retail order management system (OMS), FIX connectivity, market data streaming (ACTIV, Reuters), and Kafka-based order events, as well as clearing, asset transfers, KYC/KYB, and money movement. I build AI agent skills and plugins that automate engineering work, cutting per-app Kubernetes migration time from 1 month to 10 days. I run sprint planning and mentor engineers.

---

## 📊 Highlights

| Impact | Result |
|---|---|
| DynamoDB GSI cost | **$24K → $4K per day** |
| Infrastructure cost (EC2 → EKS) | **$20K → $2–4K per month** |
| Account loading (batch → event-driven) | **45 min → milliseconds** |
| Kubernetes migration time with AI tooling | **1 month → 10 days per app** |
| Trump Account launch | **4M accounts, $4B in assets, shipped in 1 month** |
| ACAT transfer review | **15 days → 4 days** |
| Manual wire review | **80% → 5%** |
| KYC vendor integration | **3 months → 5 days** |
| Notification Service throughput | **Up to 2M events per minute** |

---

## 💼 Experience

### **DriveWealth**
_New York, NY / Jersey City, NJ_

#### Senior Software Engineer | Execution Services
_Jun 2026 – Present_
- Cut DynamoDB GSI cost from $24K to $4K per day by redesigning the table's sharding strategy and coordinating the rollout across 200 dependent JARs that use the table.
- Reduced account-loading time from 45 minutes to milliseconds by converting batch processing jobs into event-driven microservices.
- Improved order-event processing performance by 25% by migrating the retail OMS messaging layer from ActiveMQ to Kafka, enabling scalable, high-throughput distribution of order events.
- Improved observability of legacy trading applications by adding end-to-end Prometheus metrics.
- Served as L3 incident support for production trading systems, investigating root causes and making rollback vs. roll-forward decisions based on the impact on dependent applications and customers.
- Ran sprint planning and mentored 3 software engineers on the team.

#### Senior Software Engineer | Partner Engineering
_Jan 2024 – Jun 2026_
- Cut ACAT transfer review time from 15 days to 4 days by building Asset Transfer Automation, a fully API-driven platform for internal, external, and ACAT transfers (full and partial) across equities, options, mutual funds, and fixed income that replaced PDF forms with auto-review and manual-review fallback.
- Shipped Trump Account onboarding in 1 month as a company priority, onboarding 4 million accounts and $4B in assets ($1K government contribution per account) in a single launch.
- Cut infrastructure cost by ~80–90% ($20K to $2–4K per month) by migrating trading services from EC2 to Kubernetes (EKS), after first raising legacy test coverage from 40% to 85% with event replay and adding performance tests to the ArgoCD pipeline.
- Cut per-app EKS migration time in dev from 1 month to 10 days by building org-wide AI agent skills and plugins that automate Helm charts, observability, alert setup, and pre-promotion checklist reviews.
- Upgraded legacy trading applications from Java 8 to Java 21 at an average of 4 apps per quarter using a phased Day 0–Day N migration plan, and tuned garbage collection, heap allocation, and core usage to lower CPU usage and core allocation on EKS.
- Built a FIX connectivity API that routes orders into the retail OMS, and market data streaming integrations with ACTIV and Reuters feeds that every OMS relies on to submit orders to the street.
- Increased release cadence from monthly to weekly by decomposing monolithic API applications into independently deployable microservices with a per-service Git release strategy.
- Cut manual review of business applications from 80% to 10% by building an automated Business KYB workflow that supports international customers.
- Designed domain events on the most heavily used DynamoDB tables with Redpanda (Kafka) and config-driven transforms in Redpanda Connect, letting cross-functional teams consume data without custom integrations.

#### Software Engineer II | API
_May 2021 – Dec 2023_
- Reduced manual wire review from 80% to 5%, letting 95% of deposits post directly to customer accounts, by building a Wire Payment Review system on JPMorgan Virtual Accounts with fraud and compliance checks and a name-matching score that parses NACHA files, matches senders to trading accounts, and auto-rejects mismatches.
- Cut KYC vendor integration time from 3 months to 5 days and KYC review time from 2 days to 5 minutes by building a single-API, multi-vendor KYC platform that lets AML analysts reroute traffic to a new vendor within a day when approval rates drop.
- Built event-driven Kafka microservices for clearing systems and contributed to CAT reporting.

#### Software Engineer I | API
_Jul 2018 – Apr 2021_
- Designed and built from scratch a config-driven Notification Service that delivers real-time events to all partners across the organization through AWS SQS, now handling up to 2M events per minute during market hours across every business domain.
- Built a migration tool that transferred millions of assets between systems without disruption.
- Improved API latency and throughput through performance optimization, and led incident management and partner-facing API documentation.

### **Wells Fargo**
_New York, NY_

#### Junior Java Developer | Collateral Management
_Oct 2017 – Jul 2018_
- Built a rule engine to enforce business rules across multiple lines of business, plus algorithms for analytical reporting, using Spring Boot and AngularJS.

---

## 🛠 Skills

**Languages and Frameworks:** Java (8–21), JVM Performance Tuning (GC, Heap), Python, Spring Boot, REST APIs, Microservices, Event-Driven Architecture  
**Data and Messaging:** Kafka, Redpanda, ActiveMQ, DynamoDB, PostgreSQL  
**Cloud and DevOps:** AWS (EKS, EC2, Lambda, SQS), Kubernetes, Helm, ArgoCD, CI/CD, Prometheus  
**AI Engineering:** AI agent skills and plugins for automating migrations, Helm, observability, and release checklists  
**Domain:** Retail OMS, FIX Protocol, Market Data Streaming (ACTIV, Reuters), Clearing, ACAT and Asset Transfers, KYC/KYB/AML, Money Movement and Settlement, CAT Reporting

---

## 🎓 Education

**New York Institute of Technology**  
_MS in Computer Science_ | New York, NY | 2017
