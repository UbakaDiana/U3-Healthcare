# U3 Healthcare 

## Project Overview

This project involved cleaning and analyzing healthcare data using SQL before developing an interactive dashboard in Power BI.

The dataset contained date inconsistencies and duplicate records that needed to be addressed before meaningful analysis could be carried out. After cleaning and validating the data, I used Power BI to explore hospital discharge patterns, patient demographics, and average length of stay.

The goal was to turn a messy healthcare dataset into a more reliable and interactive reporting tool.

## Objectives

The main objectives of this project were to:

* Identify and resolve inconsistent date formats in the healthcare dataset.
* Detect and remove duplicate records using SQL.
* Prepare reliable data for analysis and visualization.
* Analyze discharge patterns across age groups, gender, and months.
* Examine average length of stay and daily discharge rates.
* Build an interactive Power BI dashboard to present key findings.

## Data Cleaning and Preparation (SQL)

One of the main challenges in this project was the inconsistency in the admission and discharge dates. Some dates appeared to follow the MM/DD/YYYY format, while others followed DD/MM/YYYY, making it difficult to determine the correct dates with confidence.

To address this, I:

* Investigated date inconsistencies: Examined the date fields and validated the interpretation of admission dates against the available month and year information.
* Recalculated discharge dates: Used the recorded duration of stay to calculate and cross-check discharge dates, helping to resolve inconsistencies in the original records.
* Removed duplicate records: Identified and removed duplicate entries using SQL to improve data reliability.
* Prepared the cleaned data: Used the cleaned and validated data as the basis for subsequent analysis and dashboard development.

This stage highlighted the importance of data quality, validation, and careful handling of date fields before drawing conclusions from a dataset.

## Dashboard Overview (Power BI)

The cleaned data was used to develop an interactive healthcare dashboard featuring three key performance indicators:

* Total Discharges: 12,488
* Average Daily Discharge Rate: 17
* Average Length of Stay (ALOS): 7 days


## Visualizations

<img width="1666" height="934" alt="Image 01-10-2026 at 11 13" src="https://github.com/user-attachments/assets/66f4de42-1c68-4a07-a2ca-c264b431230d" />


## Key Insights

* Discharge volume: The dataset recorded 12,488 total discharges.
* Age distribution: Seniors accounted for the highest number of discharges (7,370), followed by older adults (4,597).
* Length of stay: Seniors had the highest average length of stay at 7 days, while children had the lowest at 5.2 days.
* Monthly trends: January recorded the highest discharge volume at 1,277, while May recorded the lowest at 829.
* Gender patterns: Discharge volumes and average length of stay varied between female and male patients.

These findings provide a basis for further investigation into patient flow, length of stay, and demographic patterns within the dataset.

## Tools and Skills Demonstrated

### SQL

* Data cleaning and preparation
* Duplicate record removal
* Date validation and inconsistency resolution
* Date calculations and cross-checking
* Data quality management

### Power BI

* KPI development
* Data visualization
* Interactive dashboard design
* Filtering and comparative analysis

### Analytical Skills

* Data validation
* Problem-solving
* Trend analysis
* Healthcare data interpretation

## Conclusion

This project demonstrates the work involved in taking a dataset from its raw state to an interactive analytical dashboard. The SQL stage required investigating inconsistent dates, validating records, and removing duplicates before the data could be used confidently for analysis.

The final Power BI dashboard provides an overview of hospital discharges, patient demographics, monthly trends, and average length of stay.

It reinforced an important part of data analysis: building a dashboard is only one stage of the process. The quality of the insights depends heavily on the quality of the data behind them.


## Disclaimer

This dashboard was developed for analytical and portfolio purposes. The findings reflect the dataset used and should not be interpreted as evidence of clinical outcomes or hospital performance without further investigation.
