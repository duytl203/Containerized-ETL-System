![image](https://github.com/user-attachments/assets/797bfab9-a3f2-4b51-89d8-dfa35961abb0)
# Containerized-ETL-System
This is a side project I am working on for my uncle, aiming to manage data more efficiently and sustainably in the long term.

**Note that this only applies to the KiotViet data source.**

# Description Content
• Implement Apache Airflow on Docker Container hosted on VirtualBox Machine running Ubuntu 20.04.

• Implement PostgreSQL Database and design schemas, boost performance by applying optimal indexing and partitioning strategy as well as defining various triggers and constraints.

• Define Airflow DAGs to multiple ETLmodes (Daily, Backfill).

• Execute data quality checks.

# Technologies Used:

• **ETL**: Airflow, Spark

• **Containerization**: Docker

• **Storage**: PgAdmin4

• **Other**: Python, Bash, POS system API (kiotviet)

# Getting Started:  

• **Prerequisites**: Install Docker and Docker Compose (**Ubuntu version 20.04** Recommended!)

• **Install** your **Airflow** with the following:

sudo chmod +x start.sh

./start.sh

• Access **Airflow UI**: Open your web browser and go to http://localhost:8080 to view and manage Airflow DAGs.

• Read **README.md** in dags/sonata to build your pipeline to integrate data from **KiotViet** to **PostgreSQL**.

# Contact Information:
**Phone Number**: +84799335499

**Email**: tlduy203@gmail.com



