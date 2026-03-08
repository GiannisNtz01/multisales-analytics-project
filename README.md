# Project: Unified Sales Analytics Lakehouse for Multisales, a Mid-Size Distribution Company
Data engineering solution for a sales analytics lakehouse using Databricks, Delta tables, Microsoft Fabric, and Power BI.

### The data flows through three  layers to ensure quality and reliability:

Bronze (Raw): Data is stored in its original format.

Silver (Cleansed): Data is cast to correct types, duplicates are removed, and basic business logic is applied.

Gold (Curated): Final business-ready tables organized in a Galaxy Schema. This layer is optimized for Power BI consumption.

### Data Quality Challenges

Mixed Date Formats, Currency Normalization, Join Integrity, Deduplication

### The Gold Star Schema
Fact Tables: fact_sales (daily transactions) and fact_target (monthly performance goals).
Dimension Tables: dim_date, dim_product, dim_salesperson, dim_region, and dim_reseller
