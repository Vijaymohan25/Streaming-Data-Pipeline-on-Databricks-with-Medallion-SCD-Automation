# Streaming-Data-Pipeline-on-Databricks-with-Medallion-SCD-Automation
Engineered a real-time data pipeline on Databricks Lakehouse using Medallion Architecture and Delta Live Tables. Ingested GitHub, Kaggle, and synthetic data; built SCD Type 1 logic for automated upserts; and structured data into normalized fact/dimension tables for downstream analytics.

______________________________________________________________________________________________________________________________________________________________________________________________________________________

Designed and implemented a scalable, end-to-end data engineering pipeline on the Databricks Lakehouse Platform, integrating heterogeneous data sources including GitHub repositories, Kaggle datasets, and synthetic generators. The pipeline ingests and processes data in real time using Delta Live Tables, enabling declarative orchestration and continuous ingestion with minimal manual intervention.

Structured the pipeline using the Medallion Architecture (Bronze, Silver, Gold), ensuring modularity, data quality, and lineage tracking. Bronze layers capture raw ingested data, Silver layers apply cleansing and normalization, and Gold layers deliver analytics-ready fact and dimension tables.

Engineered a dynamic Slowly Changing Dimensions (SCD) Type 1 framework to automate upserts and change detection across dimensional tables, enhancing data consistency and reducing maintenance overhead. The solution supports schema evolution and ensures readiness for downstream BI tools and machine learning workflows.

Optimized the pipeline for performance and scalability, leveraging Delta Lake features such as schema enforcement, time travel, and ACID transactions. The entire workflow is designed for extensibility, enabling rapid onboarding of new data sources and seamless integration with telemetry dashboards and financial analytics platforms.

______________________________________________________________________________________________________________________________________________________________________________________________________________________

Relationship of Data Tables


<img width="861" height="684" alt="Screenshot 2025-09-02 055322" src="https://github.com/user-attachments/assets/17885999-b0a7-4e4e-989c-82a5161bde97" />


____________________________________________________________________________________________________________________________________________________________________________________________________________________

Silver DLT Pipeline


<img width="1604" height="848" alt="Screenshot 2025-09-02 060738" src="https://github.com/user-attachments/assets/e7a771b9-9528-47c0-8873-cd7803201c85" />

____________________________________________________________________________________________________________________________________________________________________________________________________________________

PowerBI Dashboard


<img width="1261" height="736" alt="Screenshot 2025-09-02 055231" src="https://github.com/user-attachments/assets/6de3ea77-9eba-4887-8451-16da8e44182e" />

____________________________________________________________________________________________________________________________________________________________________________________________________________________


Thankyou

