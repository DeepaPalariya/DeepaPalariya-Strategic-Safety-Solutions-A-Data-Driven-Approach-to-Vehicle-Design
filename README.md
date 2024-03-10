(**Strategic Safety Solutions: A Data-Driven Approach to Vehicle Design**)

**Data Warehouse and Business Intelligence Application Setup Guide** 
**Overview**
This repository contains resources for setting up and running a Data Warehouse (DW) and Business Intelligence (BI) application designed to analyze crash investigation data sourced from the FARS dataset. The application provides comprehensive insights for informed decision-making and safety solution development.

**Essential Components**
To run the entire DW/BI application, you'll need the following essential components:

**Database Management System (DBMS):** Microsoft SQL Server (MSSQL)

**BI Tool:** Power BI

**Instructions**
**Database Setup:**
Attach the provided .mdf file named Capstone to your MSSQL server. The folder MSSQL .mdf DW_Capstone contains the complete MSSQL database, including the .mdf file and log file (Capstone.mdf and Capstone_log).

Import the data directly into Power BI via SQL Database. The dataset is extensive, containing approximately 20 million rows in one table.

**Files Included:**
**MSSQL .mdf DW_Capstone:** Contains the complete MSSQL database, including the .mdf file and log file (Capstone.mdf and Capstone_log), for attachment to any MSSQL server.

**PowerBIAnalysis:** Contains the Power BI dashboard files (.pbix and .pbit formats) along with a PDF version for convenience.

**Scripts:** Includes scripts for Create, Insert, Views, and KPIs queries, covering the entire database.

**VisioDiagrams:** Contains diagrams illustrating the table structure and demo utilized in this report.

**FinalReport:** Houses the final project report ("Deepa Palariya_Final Project Report") in both Word document and PDF formats.

**Note**
Attempting to execute scripts in alternative DBMS platforms like PostgreSQL or Oracle may encounter issues due to differences in syntax, as the tables are created using MSSQL queries.
