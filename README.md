# Hi, I'm Paepilai! 👋
**Data Pipeline Architect | Full-Time IT Student | Walker | Deep Talker | Growth Mindset Junkie**

Welcome to my GitHub! I am a Data Engineer passionate about transforming manual, time-consuming workflows into high-performance, automated data systems. Currently balancing my IT degree at KMUTT with my role as a Part-Time Data Engineer, I specialize in building scalable ETL/ELT pipelines, architecting data quality frameworks, and creating dynamic business dashboards.

> 🔒 **PDPA & Confidentiality Notice:** > *To comply with Thailand's Personal Data Protection Act (PDPA) and strict enterprise confidentiality agreements, the source code, specific business logic, and datasets for the enterprise projects listed below cannot be shared publicly. The descriptions serve to demonstrate the system architecture, tools utilized, and the engineering challenges solved.*

---

## 🚀 Part-Time Data Engineer Projects

### 1. Enterprise POS Automated Reporting & Distribution System
**Overview**
This project demonstrates the automation of complex data reporting and distribution for enterprise Point of Sale (POS) systems. [cite_start]It replaces manual Excel reporting with a fully orchestrated, programmatic workflow[cite: 56, 57].

**Project Components**
* [cite_start]**Data Processing:** Complex SQL queries to extract and transform pre-curated POS data[cite: 55, 56].
* [cite_start]**Data Formatting:** Dynamic formatting of data into standardized Excel templates[cite: 57].
* [cite_start]**Data Distribution:** Automated delivery pipelines via SharePoint and Email APIs[cite: 55, 56].

**Tools & Technologies**
* [cite_start]**Python & SQL:** Core logic for heavy data transformation, query execution, and template formatting[cite: 232, 233, 366, 367].
* [cite_start]**Apache Airflow:** Orchestrates the scheduling and execution of the reporting jobs[cite: 71, 72].
* [cite_start]**SharePoint API:** Automates file placement into specific enterprise directories[cite: 55].

**Key Features**
* [cite_start]**Advanced Data Extraction:** Utilized complex SQL logic to pull exact reporting metrics from vast curated datasets[cite: 233, 295, 296].
* [cite_start]**Automated Report Delivery:** Formatted Excel templates dynamically and delivered them directly to stakeholders via email and SharePoint APIs, completely eliminating manual export tasks[cite: 55, 56, 57].

**Learnings & Skills**
* [cite_start]**API Integration:** Learned to seamlessly integrate data pipelines with enterprise file-sharing systems (SharePoint)[cite: 55, 342].
* [cite_start]**Business Logic Implementation:** Translated complex POS reporting requirements into automated SQL/Python scripts[cite: 56, 57].

---

### 2. Secure Enterprise Pipeline & On-Premise Synchronization
**Overview**
[cite_start]Designed to handle highly sensitive data, this project involves building a secure ETL pipeline that routes data across DEV, QA, and Production environments while enforcing strict PII (Personally Identifiable Information) encryption on on-premise databases[cite: 53, 54, 55].

**Project Components**
* [cite_start]**Data Ingestion:** Airbyte Connections[cite: 53].
* [cite_start]**Data Security:** SHA-256 Hashing and Encryption layer[cite: 53, 54].
* [cite_start]**Data Storage:** On-Premise Database[cite: 53, 54].

**Tools & Technologies**
* [cite_start]**Airbyte:** Open-source data integration tool for ELT processes[cite: 73, 74].
* [cite_start]**SQL:** For defining schema structures and executing data merges/inserts[cite: 54].
* [cite_start]**GitLab & Jenkins:** Used for version control, code review, and CI/CD deployment to Production[cite: 162, 163, 362].

**Key Features**
* [cite_start]**PII Protection:** Implemented robust hashing and encryption logic for sensitive data before it reaches the on-premise storage[cite: 53, 54].
* [cite_start]**Multi-Environment Deployment:** Managed data flow across Development, QA, and Production environments securely[cite: 53, 54, 55, 165, 166, 167, 168].

**Learnings & Skills**
* [cite_start]**Data Privacy Compliance:** Mastered the handling of sensitive PII data within strict enterprise environments[cite: 270, 271, 272].
* [cite_start]**CI/CD Workflows:** Gained hands-on experience deploying complex DAGs and SQL scripts using Jenkins[cite: 54, 55, 162, 163].

---

### 3. Serverless Alerting System for Data Pipelines
**Overview**
This project overhauls the standard Apache Airflow alerting mechanism. [cite_start]By integrating Power Automate and MS Teams Webhooks, it provides real-time, detailed pipeline status alerts without relying on premium API connectors[cite: 557, 558, 559, 560, 561].

**Project Components**
* [cite_start]**Trigger Event:** Airflow Task Success/Failure[cite: 559, 563].
* [cite_start]**Workflow Automation:** Power Automate HTTP Webhooks[cite: 559, 561].
* [cite_start]**Notification System:** MS Teams Adaptive Cards[cite: 559, 563].

**Tools & Technologies**
* [cite_start]**Apache Airflow:** Workflow orchestrator[cite: 71, 72].
* [cite_start]**Power Automate:** Microsoft's low-code workflow automation platform[cite: 323, 324].
* [cite_start]**MS Teams Webhooks:** For real-time messaging integration[cite: 331, 332].

**Key Features**
* [cite_start]**Cost-Efficient Architecture:** Bypassed premium connectors by configuring HTTP URL triggers in Power Automate[cite: 560, 561].
* [cite_start]**Granular Alerting:** Configured alerts to trigger not just on system failures, but also when a task succeeds technically but fails internal business logic validations[cite: 562, 563].

---

## 🌟 Data Engineer Intern Projects

### 4. Enterprise PII Data Security & Hashing Framework
**Overview**
A critical security infrastructure project aimed at fortifying data privacy compliance across multiple enterprise domains (Customer Profiles, Visitor Logs, Digital Gift Cards). [cite_start]The solution involved developing advanced cryptographic logic to protect sensitive customer data[cite: 520].

**Project Components**
* [cite_start]**Cryptographic Layer:** AES Encryption and SHA-256 Hashing[cite: 277, 278, 289, 521, 522].
* [cite_start]**Query Optimization:** Common Table Expressions (CTEs)[cite: 302, 303, 523, 524].
* [cite_start]**Data Integration:** Merge SQL Files[cite: 527, 528].

**Tools & Technologies**
* [cite_start]**Python (PyCryptodome):** Utilized for robust encryption and hashing algorithms[cite: 285, 286, 287].
* [cite_start]**PostgreSQL (Cloud DWS):** Relational database management[cite: 355, 356].

**Key Features**
* [cite_start]**Irreversible Hashing:** Added dedicated hash columns for emails and phone numbers to allow data analysis without exposing raw PII[cite: 521, 522].
* [cite_start]**Optimized Decryption:** Refactored legacy encryption logic by moving decryption processes into SQL CTEs, drastically reducing redundant calculations and query execution time[cite: 303, 523, 524].

---

### 5. Automated Data Quality & Validation Framework
**Overview**
Architected a comprehensive data quality framework from scratch to ensure the integrity of a major digital voucher data warehouse. [cite_start]This project involved defining data models, writing rigorous validation rules, and automating the checks[cite: 418, 419, 420, 421, 422].

**Project Components**
* [cite_start]**Data Modeling:** Schema and Primary Key definition[cite: 419, 420].
* [cite_start]**Quality Rules:** SQL scripts testing 6 dimensions of data quality[cite: 421, 422].
* [cite_start]**Orchestration:** Airflow Validation and Notification DAGs[cite: 423, 424, 425, 426].

**Tools & Technologies**
* [cite_start]**Apache Airflow:** For scheduling and dependency management[cite: 71, 72, 423].
* [cite_start]**SQL:** For executing validation logic[cite: 421, 422].

**Key Features**
* [cite_start]**Six-Dimensional Checking:** Automated checks for Completeness, Consistency, Validity, Uniqueness, Accuracy, and Freshness[cite: 421, 422].
* [cite_start]**SDLC Standardized Testing:** Developed comprehensive Unit Testing documentation and test cases aligning with standard Software Development Life Cycles[cite: 471, 472, 483, 484].

---

### 6. Global Retail Visitor Analytics Dashboard
**Overview**
Developed a comprehensive Business Intelligence solution to track user engagement and campaign performance. [cite_start]The dashboard integrates data from physical registration kiosks and digital voucher systems to provide actionable insights for Business Analysts[cite: 489, 490].

**Project Components**
* [cite_start]**Data Sources:** Visitor Registrations and Digital Voucher Databases[cite: 490].
* [cite_start]**Data Processing:** Dynamic SQL and Jinja Templating[cite: 290, 291, 292].
* [cite_start]**Visualization:** Interactive BI Dashboards[cite: 489, 490].

**Tools & Technologies**
* [cite_start]**Apache Superset:** Open-source data exploration and visualization platform[cite: 260, 261, 489].
* [cite_start]**Miro:** Used for UI/UX dashboard wireframing and flow mapping[cite: 543, 544, 545].

**Key Features**
* [cite_start]**Advanced Visualizations:** Implemented Sunburst charts for acquisition channels, Funnel charts for user journeys, and Word Clouds for demographics[cite: 495, 496, 507].
* [cite_start]**Dynamic Querying:** Utilized Jinja templates within SQL to create highly flexible and interactive dashboard filters[cite: 291, 292].

---

### 7. Enterprise Tenant Management Pipeline Refactoring
**Overview**
Modernized legacy data pipelines for a retail tenant management system to align with new engineering standards. [cite_start]Addressed missing DAG issues by optimizing variables and resolving critical system timeouts[cite: 401, 402, 403, 404].

**Key Features**
* [cite_start]**Pipeline Optimization:** Refactored Airflow DAGs to utilize Dynamic Task Mapping, reducing pipeline complexity[cite: 462, 463, 467].
* [cite_start]**Performance Enhancements:** Prevented system timeouts and reduced Airflow overload by limiting redundant SQL executions and implementing best practices[cite: 405, 406].

---

### 8. Enterprise Mobile App Historical Data Processing
**Overview**
Engineered the ingestion of massive historical application data. [cite_start]Utilized Python and pandas to clean, transform, and map messy CSV files into the Production Data Warehouse[cite: 442, 443, 444, 445, 446].

**Key Features**
* [cite_start]**Data Transformation:** Handled nulls, extracted regex patterns, formatted timestamps, and fixed broken JSON strings via custom Python scripts[cite: 445, 446].
* [cite_start]**Seamless Ingestion:** Successfully mapped and imported the cleaned data into the DWS Production environment, enabling historical trend analysis for the Data Science team[cite: 449, 450, 451, 452].
