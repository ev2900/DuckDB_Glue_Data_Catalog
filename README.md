# DuckDB example with Glue Data Catalog

<img width="85" alt="map-user" src="https://img.shields.io/badge/views-000-green"> <img width="125" alt="map-user" src="https://img.shields.io/badge/unique visits-000-green">

DuckDB is an in-process, analytical SQL database designed for OLAP queries directly on local data files. 

DuckDB can be used to process data in Iceberg format stored in S3. Specifically, DuckDB can connect to the AWS Glue Data Catalog and read, insert, update and delete data in Iceberg format. 

These code samples include a [Jupyter notebook](https://github.com/ev2900/DuckDB_Glue_Data_Catalog/blob/main/duckdb-gdc.ipynb) to connect and work with an Iceberg table via. the Glue Data Catalog. 

This example is designed to be run on SageMaker AI with an existing Iceberg table already created. If you want to deploy the required infra. on AWS to test this code sample you can deploy the CloudFormation in the [PyIceberg_Glue_Data_Catalog](https://github.com/ev2900/PyIceberg_Glue_Data_Catalog) repository.
