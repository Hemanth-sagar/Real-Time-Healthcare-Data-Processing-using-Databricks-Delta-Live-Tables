# Real-Time-Healthcare-Data-Processing-using-Databricks-Delta-Live-Tables
 
## **📝 Project Overview**  
This project implements a **real-time data processing pipeline** for healthcare data using **Databricks Delta Live Tables (DLT)**. The pipeline processes patient records in multiple stages (**Bronze, Silver, and Gold**) to ensure high data quality, efficient transformations, and readiness for analytics.  

## **🚀 Features**  
- **Delta Live Tables (DLT):** Automates data transformation and lineage tracking.  
- **Multi-Layered Architecture:** Implements **Bronze (Raw), Silver (Cleansed), and Gold (Aggregated)** tables.  
- **Real-Time Data Ingestion:** Processes live patient data for timely insights.  
- **Optimized Performance:** Uses **Delta Tables** for fast querying and reduced storage costs.  
- **Scalable Workflow:** Runs on **Databricks** with **PySpark** for efficient execution.  

## **🛠️ Tech Stack**  
- 🟢 **PySpark** – Distributed data processing  
- 🔣 **Databricks** – Cloud-based data platform  
- 👈 **Delta Tables** – Optimized storage for faster queries  
- ⚡ **Delta Live Tables (DLT)** – Automated ETL pipeline management  

## **📂 Project Structure**  
```
💃 healthcare-dlt-pipeline
 ┣ 💃 notebooks/
 ┃ ┣ 💃 01_bronze_layer.py
 ┃ ┣ 💃 02_silver_layer.py
 ┃ ┣ 💃 03_gold_layer.py
 ┣ 💃 data/               # Sample input data files
 ┣ 💃 scripts/            # Helper scripts
 ┣ 💃 README.md           # Project documentation
 ┣ 💃 requirements.txt     # Dependencies
```

## **⚙️ Setup Instructions**  

### **1⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/healthcare-dlt-pipeline.git
cd healthcare-dlt-pipeline
```

### **2⃣ Upload to Databricks**  
- Create a **Databricks Notebook**.  
- Upload the scripts from the **notebooks/** folder.  
- Configure a **Delta Live Table pipeline** in Databricks.  

### **3⃣ Run the DLT Pipeline**  
- Navigate to **Workflows → Delta Live Tables** in Databricks.  
- Create a new pipeline and attach the **Bronze, Silver, and Gold notebooks**.  
- Click **Start** to process data in real time.  

## **📊 Data Pipeline Flow**  
1⃣ **Bronze Layer** – Ingests raw healthcare data from sources (CSV, API, Streams).  
2⃣ **Silver Layer** – Cleans and standardizes patient records.  
3⃣ **Gold Layer** – Aggregates data for reporting & analytics.  

## **🤝 Contributing**  
Want to improve this project? Feel free to **fork** the repository, make changes, and submit a **pull request**.  
