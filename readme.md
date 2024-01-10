# README for Practicum2 Project
## Overview
### Title: Practicum2
### Authors: Yang He, Yidan Zhu, Yixing Chen, Zheng Zheng

This project entails the creation and management of a database schema for the analysis of academic articles, particularly focusing on data from PubMed. The project utilizes R for data processing and SQLite for database management.

## Contents
Schema Design: A relational schema design for managing article, journal, and author data.
Database Preparation: Scripts for setting up and preparing the XML data source and SQLite database.
Database Management: SQL and R scripts to create, drop, and manipulate database tables.
Data Loading: Instructions and scripts for loading data from an XML file into the database.
Data Analysis: Implementation of a star schema for OLAP queries and data analysis.
## Requirements
R and RStudio
SQLite
XML and RSQLite packages in R
## Setup and Usage
Schema Design: Review the provided schema for understanding the database structure.
Database Preparation: Run R scripts to set up the database and prepare the XML file for data extraction.
Database Management: Execute SQL and R scripts to manage database tables including creating and dropping tables.
Data Loading: Use R scripts to load data into the database from the XML file.
Data Analysis: Implement star schema for advanced data analysis and execute provided queries for insights.

## Part 1: Database Creation and Management
Schema Design: Visualize the database schema.
Prepare XML and Database: Configure paths and connections to XML data and SQLite database.
Table Management: Scripts for creating and dropping tables.
Load Tables: Populate tables with data extracted from the XML file.
## Part 2: Star Schema Implementation
Schema Creation: Instructions for creating a star schema in the database.
Data Loading: Populate the star schema using data from the previous database or by re-importing it from R.
Summary Fact Table: Create and populate a summary fact table for OLAP queries.
## Part 3: Data Exploration and Mining
Queries and Analysis: Write SQL queries to explore data, e.g., publications' seasonal pattern.
Graphical Visualization: Implement line graphs to visualize the number of publications per quarter.
Gap Analysis: Calculate the average number of days between submission and publication of articles.
## Contribute
Contributions to this project are welcome. Please contact any of the authors for collaboration.

## License
This project is open-source and available under [license type].

Acknowledgments
Special thanks to all contributors and the academic community for providing the dataset and resources for this project.
