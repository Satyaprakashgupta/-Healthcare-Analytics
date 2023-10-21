# -Healthcare-Analytics
Data Engineerings Assignment Healthcare Analytics-Wednesday Solution
# Healthcare Analytics: Data Engineering Assignment - Summary

# Approach: Used Databricks for ETL, PySpark for transformations, and Amazon S3 for storage.
Steps:
1. Ingestion: Downloaded and unzipped data using Databricks.
2. Transformation: Cleaned, categorized, and merged data into 'Young' and 'Older' age groups.
3. Storage: Stored the transformed data as 'final.csv' in Databricks, later copied to an S3 bucket.

# How to Run:
- Refer to the provided Colab notebook for dataset download and authentication.
- Use Databricks notebooks for transformations.
- Copy the resulting 'final.csv' to your desired storage location for analysis.

# Note: 
Unit testing details not provided. Ensure correct permissions for data access and storage.
