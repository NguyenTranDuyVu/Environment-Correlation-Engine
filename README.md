# Environment Correlation Engine

Data platform repository on GCP.

## Folder Structure
- `infra/terraform/`: GCP Infrastructure (IAM, GCS, BigQuery Datasets, External Tables)
- `ingestion/`: Cloud Run ingestion jobs (connectors)
- `orchestration/dags/`: Composer/Airflow DAGs
- `transform/dbt/`: dbt project for BigQuery transformations
- `ddl/`: Manual DDL definitions (optional)
- `.github/workflows/`: CI/CD workflows
