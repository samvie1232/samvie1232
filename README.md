# Hi, I'm Santiago 👋

**Data Engineer** based in Cali, Colombia (UTC-5) · open to remote and hybrid roles.

I build data pipelines that are reliable, cheap to run and easy to maintain, from the source API or database to the dashboard. Today I work with healthcare data, where I built a Python engine that prices claims from 16 healthcare providers against their contracts on 25M+ rows a month.

## How I work

- **Tested, not just working:** CI on every push, data-quality checks between layers, and controls that prove the pipeline can catch what it claims to catch.
- **Cost-aware:** a daily AWS platform for under USD 0.10 in total; serverless and pay-per-query by default.
- **Documented decisions:** every project explains its architecture, trade-offs, limitations and roadmap.

## Featured projects

| Project | What it does | Stack |
| --- | --- | --- |
| [SECOP II Procurement Risk Platform](https://github.com/samvie1232/secop-procurement-risk-platform) · [live dashboard](https://secop-riesgo-contratacion.streamlit.app) | Ingests 2.1M Colombian public contracts daily and ranks entities and suppliers by risk signals. Total AWS cost under USD 0.10. | AWS (S3, Glue, Athena), Iceberg, dbt, Airflow, Terraform, GitHub Actions, Streamlit |
| [Colombian Electricity Market on Microsoft Fabric](https://github.com/samvie1232/colombia-energy-market-fabric) | Loads the wholesale power market daily (~12.3M hourly generation rows since 2022) into a Lakehouse → Warehouse star schema, with real-time price alerts. | Microsoft Fabric (Lakehouse, Warehouse, Eventstream, Eventhouse/KQL, Activator), PySpark, T-SQL, Power BI Direct Lake |
| [Health Claims Audit Lakehouse](https://github.com/samvie1232/health-claims-audit-lakehouse) | Medallion lakehouse that audits 90,430 healthcare services and flags COP 54.9M in potential claim denials. | Databricks, PySpark, Delta Lake, Unity Catalog, Auto Loader, Lakeflow Jobs |
| [Trading Strategy Validation Lab](https://github.com/samvie1232/trading-strategy-validation-lab) | MT5 → Python pipeline that tests 3 strategy families on 13 markets (~1.1M bars) with walk-forward and Monte Carlo, and proves why none survives real costs. | Python, pandas, MQL5, pytest, GitHub Actions |

## Tech stack

**Languages:** Python (Pandas, Polars, PySpark), SQL, T-SQL, KQL, R
**Data engineering:** dbt, Apache Airflow, Databricks, Microsoft Fabric, Apache Spark, Delta Lake, Apache Iceberg, Parquet
**Cloud and infrastructure:** AWS (S3, Glue, Athena, IAM), Terraform, Docker, GitHub Actions
**Quality and testing:** pytest, dbt tests, ruff, data contracts
**Databases:** SQL Server, PostgreSQL, Athena
**BI:** Power BI (DAX, Direct Lake), Streamlit

## Currently

- Preparing the **Databricks Data Engineer Associate** and **Microsoft Fabric DP-700** certifications.

## Contact

[LinkedIn](https://www.linkedin.com/in/santiago-martinez-dataengineer/) · Spanish (native), English (B1)
