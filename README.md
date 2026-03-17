# Hi, I'm Paepilai! 👋
**Part-Time Data Engineer | Full-Time Learner | Pro-Walker | Deep Talk Seeker**

I am a Data Engineer passionate about transforming manual, time-consuming workflows into high-performance, automated data systems. Currently balancing my IT degree at KMUTT with my role as a Part-Time Data Engineer, I specialize in building scalable ETL/ELT pipelines, architecting data quality frameworks, and creating dynamic business dashboards.

> 🔒 **PDPA & Confidentiality Notice:**
> *To comply with Thailand's Personal Data Protection Act (PDPA) and strict enterprise confidentiality agreements, the source code, specific business logic, and datasets for the enterprise projects listed below cannot be shared publicly. The descriptions serve to demonstrate the system architecture, tools utilized, and the engineering challenges solved.*

---

## 🚀 Part-Time Data Engineer Projects

### 1. Enterprise POS Automated Reporting & Distribution System
**Overview**
This project demonstrates the automation of complex data reporting and distribution for enterprise Point of Sale (POS) systems. It replaces manual Excel reporting with a fully orchestrated, programmatic workflow.

**Project Components**
* **Data Processing:** Complex SQL queries to extract and transform pre-curated POS data.
* **Data Formatting:** Dynamic formatting of data into standardized Excel templates.
* **Data Distribution:** Automated delivery pipelines via SharePoint and Email APIs.

**Tools & Technologies**
* **Python & SQL:** Core logic for heavy data transformation, query execution, and template formatting.
* **Apache Airflow:** Orchestrates the scheduling and execution of the reporting jobs.
* **SharePoint API:** Automates file placement into specific enterprise directories.

**Key Features**
* **Advanced Data Extraction:** Utilized complex SQL logic to pull exact reporting metrics from vast curated datasets.
* **Automated Report Delivery:** Formatted Excel templates dynamically and delivered them directly to stakeholders via email and SharePoint APIs, completely eliminating manual export tasks.

**Learnings & Skills**
* **API Integration:** Learned to seamlessly integrate data pipelines with enterprise file-sharing systems (SharePoint).
* **Business Logic Implementation:** Translated complex POS reporting requirements into automated SQL/Python scripts.

---

### 2. Secure Enterprise Pipeline & On-Premise Synchronization
**Overview**
Designed to handle highly sensitive data, this project involves building a secure ETL pipeline that routes data across DEV, QA, and Production environments while enforcing strict PII (Personally Identifiable Information) encryption on on-premise databases.

**Project Components**
* **Data Ingestion:** Airbyte Connections.
* **Data Security:** SHA-256 Hashing and Encryption layer.
* **Data Storage:** On-Premise Database.

**Tools & Technologies**
* **Airbyte:** Open-source data integration tool for ELT processes.
* **SQL:** For defining schema structures and executing data merges/inserts/upserts.
* **GitLab & Jenkins:** Used for version control, code review, and CI/CD deployment to Production.

**Key Features**
* **PII Protection:** Implemented robust hashing and encryption logic for sensitive data before it reaches the on-premise storage.
* **Multi-Environment Deployment:** Managed data flow across Development, QA, and Production environments securely.

**Learnings & Skills**
* **Data Privacy Compliance:** Mastered the handling of sensitive PII data within strict enterprise environments.
* **CI/CD Workflows:** Gained hands-on experience deploying complex DAGs and SQL scripts using Jenkins.

---

### 3. Serverless Alerting System for Data Pipelines
**Overview**
This project overhauls the standard Apache Airflow alerting mechanism. By integrating Power Automate and MS Teams Webhooks, it provides real-time, detailed pipeline status alerts without relying on premium API connectors.

**Project Components**
* **Trigger Event:** Airflow Task Success/Failure.
* **Workflow Automation:** Power Automate HTTP Webhooks.
* **Notification System:** MS Teams Adaptive Cards.

**Tools & Technologies**
* **Apache Airflow:** Workflow orchestrator.
* **Power Automate:** Microsoft's low-code workflow automation platform.
* **MS Teams Webhooks:** For real-time messaging integration.

**Key Features**
* **Cost-Efficient Architecture:** Bypassed premium connectors by configuring HTTP URL triggers in Power Automate.
* **Granular Alerting:** Configured alerts to trigger not just on system failures, but also when a task succeeds technically but fails internal business logic validations.

---

## 🌟 Data Engineer Intern Projects

### 4. Enterprise PII Data Security & Hashing Framework
**Overview**
A critical security infrastructure project aimed at fortifying data privacy compliance across multiple enterprise domains (Customer Profiles, Visitor Logs, Digital Gift Cards). The solution involved developing advanced cryptographic logic to protect sensitive customer data.

**Project Components**
* **Cryptographic Layer:** AES Encryption and SHA-256 Hashing.
* **Query Optimization:** Common Table Expressions (CTEs).
* **Data Integration:** Merge SQL Files.

**Tools & Technologies**
* **Python (PyCryptodome):** Utilized for robust encryption and hashing algorithms.
* **PostgreSQL (Cloud DWS):** Relational database management.

**Key Features**
* **Irreversible Hashing:** Added dedicated hash columns for emails and phone numbers to allow data analysis without exposing raw PII.
* **Optimized Decryption:** Refactored legacy encryption logic by moving decryption processes into SQL CTEs, drastically reducing redundant calculations and query execution time.

---

### 5. Automated Data Quality & Validation Framework
**Overview**
Architected a comprehensive data quality framework from scratch to ensure the integrity of a major digital voucher data warehouse. This project involved defining data models, writing rigorous validation rules, and automating the checks.

**Project Components**
* **Data Modeling:** Schema and Primary Key definition.
* **Quality Rules:** SQL scripts testing 6 dimensions of data quality.
* **Orchestration:** Airflow Validation and Notification DAGs.

**Tools & Technologies**
* **Apache Airflow:** For scheduling and dependency management.
* **SQL:** For executing validation logic.

**Key Features**
* **Six-Dimensional Checking:** Automated checks for Completeness, Consistency, Validity, Uniqueness, Accuracy, and Freshness.
* **SDLC Standardized Testing:** Developed comprehensive Unit Testing documentation and test cases aligning with standard Software Development Life Cycles.

---

### 6. Global Retail Visitor Analytics Dashboard
**Overview**
Developed a comprehensive Business Intelligence solution to track user engagement and campaign performance. The dashboard integrates data from physical registration kiosks and digital voucher systems to provide actionable insights for Business Analysts.

**Project Components**
* **Data Sources:** Visitor Registrations and Digital Voucher Databases.
* **Data Processing:** Dynamic SQL and Jinja Templating.
* **Visualization:** Interactive BI Dashboards.

**Tools & Technologies**
* **Apache Superset:** Open-source data exploration and visualization platform.
* **Miro:** Used for UI/UX dashboard wireframing and flow mapping.

**Key Features**
* **Advanced Visualizations:** Implemented Sunburst charts for acquisition channels, Funnel charts for user journeys, and Word Clouds for demographics.
* **Dynamic Querying:** Utilized Jinja templates within SQL to create highly flexible and interactive dashboard filters.

---

### 7. Enterprise Tenant Management Pipeline Refactoring
**Overview**
Modernized legacy data pipelines for a retail tenant management system to align with new engineering standards. Addressed missing DAG issues by optimizing variables and resolving critical system timeouts.

**Key Features**
* **Pipeline Optimization:** Refactored Airflow DAGs to utilize Dynamic Task Mapping, reducing pipeline complexity.
* **Performance Enhancements:** Prevented system timeouts and reduced Airflow overload by limiting redundant SQL executions and implementing best practices.

---

### 8. Enterprise Mobile App Historical Data Processing
**Overview**
Engineered the ingestion of massive historical application data. Utilized Python and pandas to clean, transform, and map messy CSV files into the Production Data Warehouse.

**Key Features**
* **Data Transformation:** Handled nulls, extracted regex patterns, formatted timestamps, and fixed broken JSON strings via custom Python scripts.
* **Seamless Ingestion:** Successfully mapped and imported the cleaned data into the DWS Production environment, enabling historical trend analysis for the Data Science team.
