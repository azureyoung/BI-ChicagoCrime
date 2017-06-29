# BI-ChicagoCrime
Analyze Chicago crime (2002-2016) with SQL/SSIS/SSRS

This project is to analyze Chicago crime between 2002 and 2016 with business intelligence tools as SQL server, SSIS and SSRS.

The original dataset was downloaded from Data Portal of City of Chicago. The original dataset including multiple csv files for different periods.

The original data crime data, community information crime information were exported, combined, transformed and loading into respective staging tables in SQL server by SSIS. The data warehouse/marts were constructed by dimensional model.

The analyzed data were reported by SSRS using stored procedures. 

With this BI solution,  the crime data can be mapped, checked and analyzed basing on year, type and location. The details can be read in the document named Chicago Crime Report.
