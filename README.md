# 🚀 Nexus DataLens  
**End-to-End Automated AWS Data Analytics Pipeline**  

Empowering data insights through automation, intelligence, and visualization.  

Nexus DataLens is a **serverless, cloud-native data pipeline** designed to simplify CSV ingestion, cleaning, transformation, and visualization. Leveraging **AWS Lambda, Glue, Athena, and QuickSight**, it transforms raw datasets into interactive dashboards — enabling faster and smarter decision-making.  

---

## 📌 Features  
- **Automated Ingestion** – Upload CSVs into S3 to trigger the pipeline  
- **Data Cleaning & Transformation** – Glue jobs ensure schema detection and quality  
- **Serverless Architecture** – Event-driven and fully managed on AWS  
- **Dynamic Dashboards** – QuickSight & Power BI dashboards auto-generated per dataset  
- **Scalable & Cost-Efficient** – Pay-as-you-go model with seamless scaling  

---

## 🛠️ Tech Stack  
- **AWS S3** – Secure data lake  
- **AWS Lambda** – Event-driven orchestration  
- **AWS Glue** – ETL and schema discovery  
- **Amazon Athena** – Serverless query engine  
- **Amazon QuickSight / Power BI** – Visualization & BI  
- **Frontend (HTML, CSS, JS)** – Upload interface with Cognito authentication  

---

# 📂 Repository Structure


- nexus-datalens/
  - README.md
  - LICENSE
  - .gitignore
  - docs/
    - Nexus_DataLens_Documentation.pdf
  - assets/
    - diagrams/
      - architecture_diagram.svg
    - screenshots/
      - quicksight_dashboard.png
  - lambda/
    - lambda_function.py
  - glue_jobs/
    - csv_cleaning_job.py
  - frontend/
    - index.html
    - style.css
    - script.js
  - infra/
    - kms-policy.json
    - cloudformation-template.yaml




---

##  Architecture Overview

## 🏗️ Architecture
<img width="1379" height="917" alt="Architecture" src="https://github.com/user-attachments/assets/b187f773-43bc-4667-913b-9ff20a2276e1" />


---

---

##  Dashboards Preview

###  Power BI
![Power BI Dashboard](./assets/screenshots/powerBI_dashboard.jpg)

###  Amazon QuickSight
![QuickSight Dashboard](./assets/screenshots/quicksight_dashboard.jpg)

---

##  Getting Started

### Prerequisites
- AWS account with access to S3, Lambda, Glue, Athena, QuickSight  
- Node.js & npm (to run the frontend locally)

### Quick Setup
```bash
# Clone the repo
git clone https://github.com/prince07-bot/Nexus-Datalens-2.0.git
cd Nexus-Datalens-2.0

# Deploy backend (Lambda & Glue)
cd infra/
# Use CloudFormation or deploy manually via AWS Console

# Upload CSVs to your configured S3 bucket

# View dashboards via QuickSight or Power BI

# (Optional) Launch the frontend locally
cd ../frontend
npm install
npm start


📖 Documentation

Find full project documentation here:
👉 Nexus DataLens Documentation (PDF)

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License
.

📬 Contact

LinkedIn: www.linkedin.com/in/prince-pal

Email: princepal8780@gmail.com

💡 Closing Note

✨ Nexus DataLens is more than a pipeline — it’s about making data accessible, actionable, and insightful.

