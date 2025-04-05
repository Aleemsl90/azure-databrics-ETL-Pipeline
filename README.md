# azure-databrics-ETL-Pipeline
Production-grade ETL pipeline on Azure transforming raw GitHub data into  analytics-ready star schema with: • Extraction: GitHub → Azure SQL via Data Factory • Bronze: Raw data landing in Azure Data Lake • Silver: Databricks transformations (Parquet) • Gold: Delta Lake star schema with SCD Type 1 UPSERTs • Visualization: Power BI integration
