# Philippine Fuel Price Monitoring Dashboard

## Overview

This project is a data-driven dashboard that analyzes fuel price trends in the Philippines, specifically in Region IV-A (CALABARZON). It combines automation and business intelligence tools to transform structured data into meaningful insights.

## Features

* Interactive Power BI dashboard for fuel price trends
* Regional and city-level comparisons
* Weekly fuel price analysis
* Identification of price gaps and changes
* Clean and structured dataset

## Data Pipeline

This project implements a semi-automated workflow:

1. User prepares structured Excel data
2. Power Automate Desktop processes the file
3. Data is appended into a master dataset (`Gas2026.xlsx`)
4. Power BI connects to the dataset
5. Dashboard updates through refresh

## Automation Workflow

The automation performs:

* Reading Excel files from a designated folder
* Extracting structured fuel price records
* Appending data into a master dataset
* Maintaining consistent schema for analysis

## Tools Used

* Power BI
* Power Automate Desktop
* Microsoft Excel
* OneDrive

## How to Use

1. Add a new Excel file with fuel data
2. Run the Power Automate Desktop flow
3. Open Power BI
4. Click **Refresh**
5. View updated dashboard

## Notes

Due to platform limitations, the automation workflow is documented using screenshots and step descriptions instead of exported flow files.

## Author

Zymon Yuri R. Espela
Computer Science - Data Science Student
