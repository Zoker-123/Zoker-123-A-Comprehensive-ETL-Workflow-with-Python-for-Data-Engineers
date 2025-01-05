
# A Comprehensive ETL Workflow with Python for Data Engineers

## Project Overview
This project demonstrates the implementation of an Extract, Transform, Load (ETL) process using Python, aimed at data engineers who need to handle data from various formats and transform it into a structured format for further processing. The process involves extracting data from CSV, JSON, and XML files, transforming it (including unit conversions), and loading the transformed data into a CSV file for future use.

## Technologies Used
Python
Data Formats: CSV, JSON, XML

## Objectives
* Extract data from CSV, JSON, and XML files.
* Transform the extracted data, including performing unit conversions (e.g., from inches to meters for height, and from pounds to kilograms for weight).
* Load the transformed data into a CSV file for future use or database import.
* Log the progress of the ETL operations for traceability and monitoring.

## Dataset
You can download the dataset for this project from the following link:
-> wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0221EN-SkillsNetwork/labs/module%206/Lab%20-%20Extract%20Transform%20Load/data/source.zip

After extracting, the project folder will contain CSV, JSON, and XML files for processing.

## Project Steps
* Step 1: Gather Data Files
Download the dataset using the wget command.
Unzip the dataset to access the CSV, JSON, and XML files.

* Step 2: Import Libraries and Set Paths
Import necessary libraries:
glob for file handling.
pandas for working with CSV and JSON files.
xml.etree.ElementTree for parsing XML files.
datetime for logging timestamps.
Install pandas if it's not already installed.
Set paths for log files and the final transformed data CSV file.

* Step 3: Define Functions for ETL
Extract Data: Write separate functions for extracting data from CSV, JSON, and XML files, and combine them into a DataFrame.
Transform Data: Implement transformations such as unit conversions (height in inches to meters, weight in pounds to kilograms).
Load Data: Save the transformed data into a structured CSV file for future use or database insertion.
Logging: Implement logging to monitor each phase of the ETL process (Extraction, Transformation, Loading), along with timestamps for traceability.

* Step 4: ETL Execution
Extraction Phase: Extract data from CSV, JSON, and XML files and combine them into a single DataFrame.
Transformation Phase: Perform the required unit conversions.
Loading Phase: Write the transformed data to a CSV file.
Logging: Track the progress of each phase in a log file.

## Conclusion
This project illustrates the core ETL process using Python, providing data engineers with the skills to handle data extraction, transformation, and loading in a real-world workflow. The use of logging ensures smooth operation and easy troubleshooting.
