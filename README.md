# BI-ChicagoCrime

This project is to provide a business intelligence solution to present and analyze Chicago crime. 

BI tools in this project :SQL server 2016, SSIS and SSRS.

The original dataset was downloaded from Data Portal of City of Chicago. 
https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

The original data about crime, community information and crime information were exported, combined, transformed, cleaned and loaded into respective staging tables in SQL server by SSIS. The data warehouse/marts were constructed by dimensional model.

The analyzed data were reported by SSRS using stored procedures wrote in SQL server. 

With this BI solution,  the crime data can be checked and analyzed basing on year, type and location. The crime data can be presented in formats such map, chart and table. The examples were presented in the powerpoint document named BI-Chicago Crime.
