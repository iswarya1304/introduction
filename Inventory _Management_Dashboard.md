In my previous project, I worked with a client in the Oil & Gas sector to migrate historical data from local systems, including SQL Server, flat CSV files, 
and ERP systems, to the cloud for demand planning and inventory optimization. Using Azure Data Factory (ADF), I automated data ingestion into 
Azure Data Lake Storage Gen2 (ADLS Gen2). Implementing the Medallion Architecture (Bronze, Silver, and Gold layers) in Databricks, 
I performed schema validation and stored raw data in the Bronze layer. In the Silver layer, I used PySpark to clean data by handling null values, 
removing duplicates, and adding new columns as required. The Gold layer involved aggregations to create structured datasets for analytics. 
Data security was maintained using Azure Key Vault, and I conducted rigorous validation and performance tuning to optimize pipelines. 
This project enabled the Supply Chain Team to analyze trends, forecast demand, and optimize inventory levels, reducing stockouts and improving operational efficiency.
