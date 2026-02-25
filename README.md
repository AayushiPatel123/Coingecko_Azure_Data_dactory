# End-to-End Crypto Data Pipeline on Azure

## Introduction
This README outlines the architecture and functionality of the end-to-end crypto data pipeline implemented on Azure. The solution collects, processes, and stores cryptocurrency data leveraging various Azure services.

## Architecture Overview
The data pipeline is built using the following key components:
1. **Data Source**: Utilizing CoinGecko API for real-time cryptocurrency data.
2. **Data Ingestion**: Azure Functions are employed to fetch data periodically.
3. **Data Processing**: Azure Data Factory orchestrates data workflows, transforming the data as needed.
4. **Data Storage**: Processed data is stored in Azure Blob Storage and Azure SQL Database for further analysis.
5. **Data Visualization**: Azure Power BI is used to visualize the insights from the data.

## Steps to Set Up the Pipeline
1. **Create Azure Resources**: Set up an Azure account and create necessary resources (Functions, Data Factory, Blob Storage, and SQL Database).
2. **Configure API Access**: Obtain API keys for CoinGecko and configure access within Azure Functions.
3. **Create Azure Functions**: Implement functions to fetch data from the CoinGecko API and trigger them on a schedule using Azure Functions.
4. **Set Up Data Factory**: Create pipelines in Azure Data Factory to orchestrate the movement and transformation of data.
5. **Load Data into Storage**: Configure pipelines to load the fetched data into Blob Storage and SQL Database.
6. **Visualization**: Connect Power BI to Azure SQL Database to create reports and dashboards.

## Monitoring and Logging
Utilize Azure Monitor to track the performance and health of the data pipeline. Implement logging within Azure Functions for better traceability.

## Conclusion
This end-to-end pipeline provides a robust solution for collecting, processing, and analyzing cryptocurrency data in real-time. The architecture can be scaled as required to adapt to changing data loads and requirements.

## Getting Help
For any issues or queries, feel free to reach out on the project’s GitHub Issue tracker or contact the project maintainer.