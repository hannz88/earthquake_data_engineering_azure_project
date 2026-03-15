# Earthquake Data Engineering Project Leveraging Azure Services



This project is a data engineering leveraging the Azure services to build a scalable data pipeline in Azure, namely Databricks, Azure Data Factory, and Synapse Analytics.



## Architecture

This is the architecture of the project

![Design of the pipeline](Image/Data_design.png)



The pipeline is designed to follow Medallion Architecture.



## Summary

The tutorial guides you through setting up the core Azure services — Databricks, ADLS Gen2 storage, Synapse Analytics, and Data Factory — and securely connecting them using managed identities and IAM role assignments. You then build three Python notebooks in Databricks that progressively clean and enrich raw earthquake data from the USGS API across bronze, silver, and gold storage layers following a Medallion architecture. Finally, the notebooks are orchestrated into an automated daily pipeline using Azure Data Factory, with the processed data queryable via Synapse Analytics and visualisable in Power BI.

