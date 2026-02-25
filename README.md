{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55356 \u57317  Healthcare Claims Analytics Platform  \
### End-to-End Data Engineering + Analytics Project (Databricks \'95 AWS S3 \'95 Power BI)\
![Power BI](https://img.shields.io/badge/PowerBI-Analytics-yellow)\
![Databricks](https://img.shields.io/badge/Databricks-Lakehouse-orange)\
![AWS S3](https://img.shields.io/badge/AWS-S3-blue)\
![Python](https://img.shields.io/badge/Python-Data%20Engineering-green)\
\
An end-to-end healthcare analytics solution designed to simulate real-world insurance claim processing workflows.  \
This project demonstrates modern **data engineering**, **data modeling**, and **interactive business intelligence** practices using cloud and analytics tools.\
\
---\
\
## \uc0\u55357 \u56960  Project Overview\
\
Healthcare organizations generate massive claim datasets that require:\
\
- Data ingestion\
- Cleaning & validation\
- Dimensional modeling\
- Analytical visualization\
\
This project builds a scalable analytics pipeline where raw healthcare claim data is processed using **Databricks**, stored across **Databricks Storage & AWS S3**, modeled into a **Star Schema**, and visualized using **Power BI**.\
\
The final result is an **interactive healthcare dashboard** that enables users to explore claim trends, provider performance, and approval distribution.\
\
---\
\
## \uc0\u55356 \u57263  Problem Statement\
\
Healthcare analytics teams struggle with:\
\
- Disconnected data sources\
- Poor data modeling\
- Static reports with limited interaction\
- Lack of scalable data pipelines\
\
The goal was to design a **modern analytics workflow** that mimics enterprise-level healthcare reporting systems.\
\
---\
\
## \uc0\u55356 \u57263  Objectives\
\
- Build a realistic healthcare claims dataset using Python\
- Simulate cloud-based storage using Databricks & AWS S3\
- Implement dimensional modeling using Star Schema\
- Create interactive analytics dashboards in Power BI\
- Demonstrate data engineering + BI integration skills\
\
---\
\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 ## \uc0\u55357 \u56520  Business Impact\
\
This dashboard enables healthcare stakeholders to:\
\
- Monitor claim approval vs denial trends\
- Identify high-cost provider regions\
- Track monthly healthcare spending behavior\
- Analyze network utilization patterns\
- Support data-driven operational decisions\
\
The project simulates real-world insurance analytics workflows used by healthcare payers.\
\
\'97
\f0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
## \uc0\u55358 \u56817  Architecture Overview\
\
![Architecture Diagram](architecture/architecture_diagram.png)\
\
### Architecture Flow\
\
Python (Databricks) \uc0\u8594  Data Processing \u8594  Cloud Storage \u8594  Power BI \u8594  Interactive Dashboard\
\
**Data Sources**\
\
- Databricks Default Storage  \
- AWS S3 (member dimension table)\
\
---\
\
## \uc0\u55357 \u56580  Project Flow\
\
![Project Flow Diagram](architecture/project_flow_diagram.png)\
\
1. Synthetic healthcare data generation using Pandas & NumPy\
2. Master dataset split into Fact and Dimension tables\
3. Storage across Databricks & AWS S3\
4. Data ingestion into Power BI\
5. Data cleaning & transformation\
6. Star Schema modeling\
7. DAX measure creation\
8. Interactive dashboard design\
\
---\
\
## \uc0\u55358 \u56825  Data Quality & Governance\
\
To simulate real-world analytics challenges:\
\
- Duplicate records were intentionally introduced\
- Power BI transformations were used to clean data\
- Validation steps ensured accurate KPI calculations\
\
This demonstrates real-world data preparation workflows before analytics modeling.\
\
\'97\
\
## \uc0\u55357 \u57056 \u65039  Tech Stack\
\
| Layer | Tools Used | Purpose |\
|------|------------|--------|\
| Data Engineering | Python, Pandas, NumPy | Data generation & transformation |\
| Cloud Processing | Databricks | Data engineering workspace |\
| Cloud Storage | AWS S3 | External data source integration |\
| Data Modeling | Power BI Model View | Star Schema implementation |\
| Analytics | Power BI Desktop | Interactive visualization |\
| Query Language | DAX | KPI calculations & dynamic titles |\
\
---\
\
## 
\f1 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \uc0\u55356 \u57303 \u65039  Architectural Design Decisions
\f0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 \
\
- **Databricks** simulates enterprise-scale data processing\
- **AWS S3** demonstrates multi-cloud integration\
- **Power BI** provides strong data modeling + visualization\
- **DAX** enables dynamic analytics logic\
\
This combination reflects real-world data platform architectures.\
\
---\
\
## \uc0\u55357 \u56522  Dashboard Features\
\
- Dynamic KPI cards\
- Claim status distribution\
- Monthly healthcare spend trends\
- Provider city performance analysis\
- Interactive slicers (Provider Specialty, Network Status)\
- Dynamic dashboard header using DAX\
- Custom Tooltip Pages\
\
Dashboard Preview:\
\
![Dashboard Preview](images/dashboard_preview.png)\
\
---\
\
## \uc0\u55358 \u56810  Data Modeling\
\
A Star Schema was implemented:\
\
**Fact Table**\
- `claims_fact`\
\
**Dimension Tables**\
- `provider_dim`\
- `member_dim`\
\
Relationships created in Power BI Model View to simulate enterprise warehouse modeling.\
\
---\
\
## \uc0\u9881 \u65039  Key DAX Measures\
\
Examples include:\
\
- Total Claims\
- Total Claim Cost\
- Running Cost\
- Approved Claims\
- Dynamic Dashboard Title\
\
Dynamic Title Example:\
\
\
---\
\
## \uc0\u55356 \u57104  Published Interactive Dashboard\
\
\
\uc0\u55357 \u56393  https://app.powerbi.com/view?r=eyJrIjoiNDVhMjExNzctYTU5YS00YTk3LWIzNmQtODk0ZTJjODUyOTQ4IiwidCI6IjcwZGUxOTkyLTA3YzYtNDgwZi1hMzE4LWExYWZjYmEwMzk4MyIsImMiOjN9\
\
\
\uc0\u9888 \u65039  Note: This is a public demo environment using synthetic healthcare data.\
\'97\
\
## \uc0\u55357 \u56960  Deployment\
\
The dashboard is deployed using Power BI Service.\
\
Deployment Steps:\
- Published report from Power BI Desktop\
- Hosted in Power BI Service (Cloud)\
- Embedded public link for interactive viewing\
\
This simulates production BI deployment workflows.\
\
\'97\
\
## \uc0\u55357 \u56513  Repository Structure\
\
\pard\pardeftab720\sa240\partightenfactor0

\f1 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\pard\pardeftab720\partightenfactor0
\cf0 \strokec2 Healthcare-Claims-Analytics-Project/\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  README.md\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  architecture/\
\uc0\u9474  \u9500 \u9472 \u9472  architecture_diagram.png\
\uc0\u9474  \u9492 \u9472 \u9472  project_flow_diagram.png\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  notebooks/\
\uc0\u9474  \u9492 \u9472 \u9472  healthcare_data_generation.ipynb\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  powerbi/\
\uc0\u9474  \u9492 \u9472 \u9472  healthcare_claims_dashboard.pbix\
\uc0\u9474 \
\uc0\u9500 \u9472 \u9472  documentation/\
\uc0\u9474  \u9492 \u9472 \u9472  Healthcare_Claims_Analytics_Project_Documentation.docx\
\uc0\u9474 \
\uc0\u9492 \u9472 \u9472  images/\
\uc0\u9492 \u9472 \u9472  dashboard_preview.png
\f0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\
## \uc0\u55358 \u56800  Skills Demonstrated\
\
### \uc0\u55357 \u56633  Data Engineering & Cloud Integration\
- Synthetic healthcare data generation using Python (Pandas, NumPy)\
- Hybrid cloud architecture using Databricks and AWS S3\
- Multi-source data ingestion into Power BI\
- Secure data access using presigned URLs\
\
### \uc0\u55357 \u56633  Data Modeling & Analytics\
- Star Schema dimensional modeling\
- Fact and Dimension table design\
- Relationship optimization for performance\
- DAX measure development for KPIs and analytics logic\
\
### \uc0\u55357 \u56633  Power BI Advanced Features\
- Dynamic dashboard titles using DAX\
- Custom Tooltip Report Pages\
- Conditional KPI formatting\
- Interactive slicers and cross-filtering\
- Professional UI/UX dashboard design\
\
### \uc0\u55357 \u56633  Business Intelligence & Visualization\
- Healthcare claims trend analysis\
- Provider performance insights\
- Network utilization analytics\
- Data storytelling through interactive visuals\
\
### \uc0\u55357 \u56633  Development & Deployment\
- Databricks Notebook development\
- Power BI Service publishing\
- GitHub project structuring\
- Documentation and architecture design\
}