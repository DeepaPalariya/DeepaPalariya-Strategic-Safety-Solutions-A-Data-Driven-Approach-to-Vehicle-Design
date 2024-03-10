**Strategic Safety Solutions: A Data-Driven Approach to Vehicle Design**
## a) Organization Description, Problem Statement, and Approach Used
The project aims to utilize crash investigation data from the National Highway Traffic Safety Administration (NHTSA) to enhance vehicle safety features. By analyzing the Fatality Analysis Reporting System (FARS) dataset, covering fatal traffic crash data from all 50 states, the District of Columbia, and Puerto Rico, the project focuses on identifying trends, patterns, and contributing factors in crash occurrences. The primary objective is to guide the development, adjustment, or introduction of safety solutions for vehicles while adhering to safety regulations mandated by organizations like the NHTSA. The approach involves leveraging crash investigation data to inform safety solutions, emphasizing data collection, cleaning, validation, and analysis to create a robust data warehouse with master and transaction tables.

## b) Overview of Decision-Making Challenges and the Role of DW/BI Applications
Analyzing Crash Causes: The DW/BI application enables the identification of trends and patterns in crash occurrences, shedding light on primary causes such as human error, mechanical failure, or environmental factors.
Assessing Safety Measures: Stakeholders can evaluate the effectiveness of existing safety features and protocols in vehicles, guiding decisions on enhancements or the introduction of new safety measures.
Prioritizing Safety Solutions: Examination of crash severity and incident frequency allows stakeholders to prioritize safety solutions to reduce severe crashes or address common contributing factors.
Monitoring Performance: Real-time monitoring of safety performance metrics facilitates tracking the impact of implemented safety solutions and allows for timely adjustments.

## c) Sample Master Table and Transaction Table Structure
The database comprises six master tables and 11 transaction tables, with each master table serving as a dimension table and each transaction table as a Fact table, embodying a snowflake schema. These tables collectively facilitate the derivation of essential KPIs necessary for devising strategic safety solutions for vehicles.

## d) Specifications for the DW/BI Solution and Schema and Design of the DW/BI Application
Utilizing Excel, MSSQL, Access, and SSIS, data was effectively managed. Although cubes were not employed, their functionality was integrated during the normalization of data and creation of master and transaction tables. A normalization process rectified redundant and denormalized data, optimizing the dataset for efficiency, integrity, and usability. The schema for the DW/BI is of a snowflakes variety, allowing BI analysis and keeping the system flexible for future expansions.

## e) Views and Queries Created to Account for the KPIs
Views and queries were established using MSSQL to calculate KPIs, serving as the basis for querying and building KPIs for visualization purposes.

## f) Final Analysis/Findings
Key observations from the analysis include identifying demographic trends, vehicle involvement, crash characteristics, and safety measures. Proposed safety solutions based on findings include educational campaigns, integration of advanced driver assistance systems, state-specific road safety initiatives, weather-awareness systems, speed limiters, alcohol ignition interlock devices, and more.

## g) Summary/Lessons Learned/Limitations
The project highlights the value of collecting and preparing data for analyzing crashes and deriving necessary solutions. Implementing measures can significantly enhance road safety, but limitations such as the absence of detailed vehicle information must be acknowledged.

This comprehensive approach to utilizing crash investigation data underscores the importance of data-driven decision-making in enhancing vehicle safety standards and reducing the frequency and severity of traffic crashes.


**Data Warehouse and Business Intelligence Application Setup Guide** 
## Overview
This repository contains resources for setting up and running a Data Warehouse (DW) and Business Intelligence (BI) application designed to analyze crash investigation data sourced from the FARS dataset. The application provides comprehensive insights for informed decision-making and safety solution development.

## Essential Components
To run the entire DW/BI application, you'll need the following essential components:

## 1.Database Management System (DBMS): Microsoft SQL Server (MSSQL)

## 2. BI Tool:Power BI

**Instructions**
## Database Setup:
Attach the provided .mdf file named Capstone to your MSSQL server. The folder MSSQL .mdf DW_Capstone contains the complete MSSQL database, including the .mdf file and log file (Capstone.mdf and Capstone_log).

Import the data directly into Power BI via SQL Database. The dataset is extensive, containing approximately 20 million rows in one table.

**Files Included:**
## 1. MSSQL .mdf DW_Capstone: Contains the complete MSSQL database, including the .mdf file and log file (Capstone.mdf and Capstone_log), for attachment to any MSSQL server.

## 2. PowerBIAnalysis: Contains the Power BI dashboard files (.pbix and .pbit formats) along with a PDF version for convenience.

## 3. Scripts: Includes scripts for Create, Insert, Views, and KPIs queries, covering the entire database.

## 4. VisioDiagrams: Contains diagrams illustrating the table structure and demo utilized in this report.

**FinalReport:** Houses the final project report ("Deepa Palariya_Final Project Report") in both Word document and PDF formats.

**Note**
Attempting to execute scripts in alternative DBMS platforms like PostgreSQL or Oracle may encounter issues due to differences in syntax, as the tables are created using MSSQL queries.
