---
layout: page
title: Med-Insight
---

# Med-Data Subsystem

**med-data** is a subsystem of the med-insight application that provides mock data in support of local development and testing. This subsystem simulates two external data sources and provides sample extract file generation, as summarized below:  

 - A **Microsoft SQL Server database** mimics a data warehouse with representative schemas and tables
 - An **unstructured file storage location** simulates Azure Data Lake Storage Gen2 for Parquet file storage
 - A **sample extract generation tool** creates fixed-length ASCII clinical data files

The data available within med-data is **synthetic** and does not contain PHI or PII.  

[← Back to Med-Insight](/med-insight/)
