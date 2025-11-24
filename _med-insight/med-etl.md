---
layout: page
title: Med-Insight
---

# Med-ETL Subsystem

**med-etl** is a subsystem of the med-insight application that provides ETL functionality to retrieve data from external systems and store transformed data in a data mart.

It performs two primary functions:

* **Data Preparation Pipeline** - Extracts mock VA healthcare data from source systems, transforms/cleans it according to business rules, and loads prepared data into target databases for consumption by downstream applications (e.g., **med-risk** - a future medication risk management application).

* **ASCII Extract Generation** - Generates fixed-width ASCII files for various healthcare domains. This serves as a learning tool for Python, SQL Server, and data processing skill development and will be retained as the application evolves.

The Med-ETL technology stack includes Python 3.11, SQL Server 2019, MinIO, and Docker Desktop.

[← Back to Med-Insight](/med-insight/)
