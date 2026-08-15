<div align="center">
  <img src="assets/data-engineering-banner.svg" alt="Adarsh Damarla — Cloud and Big Data Engineer" width="100%" />
</div>

<h1 align="center">Hi, I'm Adarsh Damarla 👋</h1>

<p align="center">
  <strong>Cloud & Big Data Engineer</strong><br/>
  Cloud Data Engineer building reliable batch, streaming, and lakehouse platforms that turn source data into analytics-ready models.
</p>

<p align="center">
  <a href="https://github.com/AdarshDamarla-DataEngineer-Git?tab=repositories"><img src="https://img.shields.io/badge/Explore-My%20Projects-181717?style=for-the-badge&logo=github" alt="GitHub projects" /></a>
  <a href="mailto:d29adarsh@gmail.com"><img src="https://img.shields.io/badge/Email-Let's%20Connect-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## About me

I design and build end-to-end cloud data platforms for reliable batch and real-time analytics using Azure, AWS, Google Cloud, Databricks, Spark, Kafka, Airflow, and dbt—from data ingestion and orchestration to governed lakehouse layers and analytics-ready models.

## What I build

- Metadata-driven ingestion from databases, files, APIs, and event streams
- Batch and streaming transformations with PySpark and Structured Streaming
- Governed Bronze, Silver, and Gold lakehouse layers using Delta Lake and Unity Catalog
- Incremental processing, CDC, and SCD Type 1/2 history management
- Cross-platform orchestration with Azure Data Factory and Apache Airflow
- Analytics-ready facts, dimensions, and serverless SQL datasets

## Featured projects

| Project | Engineering highlights | Stack |
| --- | --- | --- |
| [🎧 Spotify Azure Incremental Lakehouse](https://github.com/AdarshDamarla-DataEngineer-Git/Spotify-Azure-Project) | Metadata-driven incremental ingestion from Azure SQL to ADLS Gen2; Auto Loader processing; SCD Type 2 dimensions and a Type 1 streaming fact | ADF, ADLS Gen2, Databricks, PySpark, Delta Lake |
| [🚕 Real-Time Uber Ride Lakehouse](https://github.com/AdarshDamarla-DataEngineer-Git/Uber-Project) | Streams FastAPI-generated ride events through Event Hubs; unifies historical and real-time data; publishes an enriched OBT and SCD-managed dimensional model | FastAPI, Event Hubs, Structured Streaming, Lakeflow, Unity Catalog |
| [🌬️ Airflow + dbt + Databricks](https://github.com/AdarshDamarla-DataEngineer-Git/Airflow-DBT-Databricks) | Airflow 3 orchestrates Databricks ingestion and a dependency-aware dbt graph using deferrable execution and a containerized Celery platform | Airflow, dbt, Databricks, Celery, Redis, PostgreSQL, Docker |
| [🛰️ NASA GCN Fermi Streaming Pipeline](https://github.com/AdarshDamarla-DataEngineer-Git/Kafka-Databricks-Nasa) | OAuth-authenticated Kafka ingestion of NASA gamma-ray burst notices; native Spark parsing; governed analytical snowflake schema | Kafka, OAuth 2.0, PySpark, Databricks, Delta Lake |

### More portfolio work

- [E-commerce Databricks Pipeline](https://github.com/AdarshDamarla-DataEngineer-Git/Ecommerce-Databricks-Pipeline) — Six data domains processed through Bronze, Silver, and Gold layers with data-quality expectations, CDC, SCD Type 2, and dimensional modeling.
- [Olist Azure Big Data Platform](https://github.com/AdarshDamarla-DataEngineer-Git/BigDataProjects) — Approximately 1.56 million marketplace records ingested from HTTP, SQL, and MongoDB, transformed with PySpark, and served through Synapse Serverless SQL.


## Platform architecture

```mermaid
flowchart LR
    A["Sources<br/>SQL · Files · APIs · Events"] --> B["Ingestion & orchestration<br/>ADF · Airflow · Kafka"]
    B --> C["Cloud storage<br/>ADLS · Object storage"]
    C --> D["Processing<br/>Spark · PySpark · dbt"]
    D --> E["Lakehouse<br/>Bronze · Silver · Gold"]
    E --> F["Serving<br/>Facts · Dimensions · SQL · BI"]
```

## Technical skills

### Cloud platforms

![AWS](https://img.shields.io/badge/Amazon%20Web%20Services-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

### AWS data services

![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![AWS Glue](https://img.shields.io/badge/AWS%20Glue-8C4FFF?style=flat-square&logo=amazonwebservices&logoColor=white)
![Amazon EMR](https://img.shields.io/badge/Amazon%20EMR-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![Amazon Kinesis](https://img.shields.io/badge/Amazon%20Kinesis-8C4FFF?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)

### Google Cloud data services

![Cloud Storage](https://img.shields.io/badge/Cloud%20Storage-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Dataproc](https://img.shields.io/badge/Dataproc-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Pub/Sub](https://img.shields.io/badge/Pub%2FSub-AECBFA?style=flat-square&logo=googlecloud&logoColor=1A73E8)
![Dataflow](https://img.shields.io/badge/Dataflow-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

### Azure data services demonstrated in projects

![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![ADLS Gen2](https://img.shields.io/badge/ADLS%20Gen2-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Event Hubs](https://img.shields.io/badge/Event%20Hubs-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Synapse](https://img.shields.io/badge/Synapse%20Analytics-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

`Multi-Cloud Data Architecture` · `Cloud Object Storage` · `Managed Spark` · `Serverless Warehousing` · `Event Streaming` · `Metadata-Driven Ingestion`

### Databricks and distributed processing

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=flat-square)
![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-1B3139?style=flat-square)
![Lakeflow](https://img.shields.io/badge/Lakeflow-FF3621?style=flat-square&logo=databricks&logoColor=white)

### Streaming and orchestration

![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Languages, databases, and modeling

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

`Medallion Architecture` · `Dimensional Modeling` · `CDC` · `SCD Type 1/2` · `Data Quality` · `Incremental Loading` · `Star/Snowflake Schemas`

## Currently strengthening

- Automated data testing, pipeline observability, and operational reliability
- CI/CD and environment-based deployment for Databricks and cloud data platforms
- Spark and Delta Lake performance tuning

## Let's connect

I'm interested in Cloud Data Engineer, Databricks Data Engineer, and Big Data Engineer opportunities where I can build reliable batch, streaming, and lakehouse platforms.

- Email: [d29adarsh@gmail.com](mailto:d29adarsh@gmail.com)
- Projects: [View all repositories](https://github.com/AdarshDamarla-DataEngineer-Git?tab=repositories)

---

<p align="center"><em>Designing reliable paths from source systems to analytics-ready data.</em></p>
