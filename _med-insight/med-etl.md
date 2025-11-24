---
layout: page
title: Med-Insight
---

# Med-ETL Subsystem

**med-etl** is a subsystem of the med-insight application that provides ETL functionality to retrieve data from external systems and store transformed data in a data mart.

It performs two primary functions:

* **Data Preparation Pipeline** - Extracts mock VA healthcare data from source systems, transforms/cleans it according to business rules, and loads prepared data into target databases for consumption by downstream applications.  

* **ASCII Extract Generation** - Generates fixed-width ASCII files for various healthcare domains.  

The Med-ETL technology stack includes Python 3.11, SQL Server 2019, MinIO, and Docker Desktop.

[← Back to Med-Insight](/med-insight/)
