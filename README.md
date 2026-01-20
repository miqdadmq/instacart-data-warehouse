# Instacart Data Warehouse

End-to-end data pipeline using Apache Airflow, BigQuery, and GCP.

## Architecture
- Source: Instacart Kaggle Dataset
- Orchestration: Apache Airflow
- Storage: Google Cloud Storage
- Warehouse: BigQuery
- Visualization: Looker Studio

## Data Flow
Kaggle → GCS → BigQuery (Staging → EDW → Mart)

## How to Run
1. Clone repo
2. Run Airflow using Docker
3. Deploy to GCP VM