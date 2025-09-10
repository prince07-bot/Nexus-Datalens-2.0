Nexus DataLens

End-to-End Automated AWS Data Analytics Pipeline
Empowering data insights through automation, intelligence, and visualization.
Nexus DataLens is a serverless, cloud-native data pipeline designed to simplify CSV ingestion, cleaning, transformation, and visualization. Leveraging AWS Lambda, Glue, Athena, and QuickSight, it transforms raw datasets into interactive dashboards — enabling faster and smarter decision-making.

Features

Automated Ingestion – Upload CSVs into S3 to trigger the pipeline

Data Cleaning & Transformation – Glue jobs ensure schema detection and quality

Serverless Architecture – Event-driven and fully managed on AWS

Dynamic Dashboards – QuickSight dashboards auto-generated per dataset

Scalable & Cost-Efficient – Pay-as-you-go model with seamless scaling

🛠️ Tech Stack

AWS S3 – Secure data lake

AWS Lambda – Event-driven orchestration

AWS Glue – ETL and schema discovery

Amazon Athena – Serverless query engine

Amazon QuickSight / Power BI – Visualization & BI

Frontend (HTML, CSS, JS) – Simple upload interface with Cognito authentication

# 📂 Repository Structure

nexus-datalens/
│── README.md
│── LICENSE
│── .gitignore
│── docs/
│ └── Nexus_DataLens_Documentation.pdf
│── assets/
│ ├── diagrams/
│ │ └── architecture_diagram.svg
│ └── screenshots/
│ └── quicksight_dashboard.png
│── lambda/
│ └── lambda_function.py
│── glue_jobs/
│ └── csv_cleaning_job.py
│── frontend/
│ ├── index.html
│ ├── style.css
│ └── script.js
│── infra/
│ ├── kms-policy.json
│ └── cloudformation-template.yaml
