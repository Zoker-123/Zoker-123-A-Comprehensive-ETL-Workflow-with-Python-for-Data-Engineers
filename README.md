## Project Title
# A Comprehensive ETL Workflow with Python for Data Engineers

## Project Description
This project demonstrates the implementation of an Extract, Transform, Load (ETL) workflow using Python. It involves extracting data from multiple file formats (CSV, JSON, XML), transforming the data (including unit conversions), and loading the transformed data into a structured CSV file. The project also includes a robust logging mechanism for monitoring and auditing purposes.

## Technologies Used
Python
Libraries: pandas, json, xml.etree.ElementTree, datetime
Data Formats: CSV, JSON, XML

## Workflow
1. Extraction: Extract data from CSV, JSON, and XML files in a specified directory.
2. Transformation: Convert height from inches to meters and weight from pounds to kilograms.
3. Loading: Save the transformed data into a CSV file for further use.
4. Logging: Log the progress of each ETL phase with timestamps.
