# Dynamic Pipeline for Incremental Data Load

**Source**: Azure SQL Database  
**Destination**: Azure Data Lake Storage (ADLS)  
**ADF Activities Used**: Lookup, Copy Data, Stored Procedure

This is a dynamic and reusable Azure Data Factory (ADF) pipeline designed to perform **incremental data loads** from an Azure SQL Database to ADLS. The pipeline uses **parameterization** to ingest any CSV data with minimal hardcoding, making it scalable and production-ready.
