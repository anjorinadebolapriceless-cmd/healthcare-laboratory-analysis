# Healthcare Laboratory Operational Performance Analysis

## Project Overview

This project examines the operational performance of a fictional diagnostic laboratory, ClearPath Diagnostic Laboratory, using Microsoft Excel.

The analysis focuses on laboratory turnaround time (TAT), operational efficiency, data quality, and compliance with established testing targets.

Using a synthetic dataset of 1,000 laboratory test-request records, the project demonstrates how data analytics can support operational monitoring, identify performance gaps, and generate actionable business recommendations.

## Business Problem

Laboratories must process and release diagnostic test results within established turnaround time targets to support efficient service delivery.

Delays in sample processing, result preparation, and result release can affect operational efficiency and service quality.

ClearPath Diagnostic Laboratory requires an analytical approach to evaluate its turnaround time performance, identify operational bottlenecks, and assess compliance with established testing targets.

## Project Objectives

- Evaluate laboratory turnaround time performance.
- Assess compliance with established turnaround time targets.
- Identify operational bottlenecks across pre-analytical, analytical, and post-analytical stages.
- Investigate data quality issues and inconsistencies.
- Examine performance across laboratory sections, test categories, and priority levels.
- Develop evidence-based recommendations for operational improvement.

## Dataset Description

The project uses a synthetic dataset containing 1,000 laboratory test-request records.

Key dataset attributes include:

- Record and request identifiers.
- Request dates.
- Laboratory sections.
- Test categories and test names.
- Priority levels.
- Sample receipt timestamps.
- Processing start timestamps.
- Result-ready timestamps.
- Result-release timestamps.
- Target turnaround time.
- Sample status.

**Data privacy and integrity:** All records are synthetically generated for educational and portfolio purposes. No real patient information or confidential laboratory records were used.

## Tools and Technologies

- Microsoft Excel
- Power Query
- Excel formulas and functions
- Pivot Tables
- Data visualisation and dashboard reporting

## Data Preparation and Cleaning

Data preparation involved several data quality procedures:

- Identification and removal of duplicate records.
- Standardisation of inconsistent laboratory section names.
- Correction of spelling inconsistencies.
- Date and time format standardisation.
- Identification of missing and incomplete records.
- Validation of chronological relationships between laboratory timestamps.
- Application of data validation rules.

The cleaning process identified 10 duplicate records for removal and 12 incomplete records.

Additional chronological inconsistencies were flagged for investigation rather than automatically treated as valid observations.

## Analytical Methodology

The analysis examined the following operational indicators:

1. Pre-Analytical Time
2. Processing Time
3. Total Turnaround Time
4. Release Delay
5. Turnaround Time Compliance

Excel formulas, statistical analysis, Pivot Tables, and visualisations were used to investigate operational performance and identify trends.

## Key Findings

**1. Turnaround Time Compliance**

The analysis recorded 593 tests within their established turnaround time targets and 380 tests exceeding their targets.

This indicates a substantial opportunity to improve turnaround time performance.

**2. Priority-Level Performance**

STAT tests recorded 76.83% compliance, Urgent tests recorded 73.44%, while Routine tests recorded 55.65%.

Routine testing showed the lowest compliance rate among the three priority categories, highlighting an area requiring further operational investigation.

**3. Test Volume Distribution**

Full Blood Count accounted for the largest proportion of test requests at 8.53%, followed by Reticulocyte Count at 8.32% and ESR at 7.81%.

These results highlight the importance of monitoring resource allocation across frequently requested tests.

## Business Recommendations

- Investigate the causes of turnaround time delays, particularly within Routine testing.
- Review staffing, workload distribution, and resource allocation across laboratory sections.
- Monitor turnaround time compliance regularly using operational dashboards.
- Strengthen timestamp documentation and data validation procedures.
- Prioritise process improvement initiatives in areas with recurring delays.

## Project Deliverables

- Synthetic raw dataset.
- Data dictionary.
- Cleaned dataset.
- Data cleaning and validation documentation.
- Excel analytical calculations.
- Pivot Tables.
- Data visualisations.
- Operational performance dashboard.
- Analytical findings and business recommendations.

## Project Outcome

This project demonstrates the application of Excel-based data analytics to a healthcare operations problem.

It highlights how structured data preparation, analytical calculations, and visual reporting can provide insights into operational performance and support evidence-based decision-making.

## Skills Demonstrated

Microsoft Excel | Power Query | Data Cleaning | Data Validation | Statistical Analysis | Pivot Tables | Data Visualisation | Business Analysis | Operational Performance Analysis

---

**Project Category:** Healthcare Analytics

**Organisation:** ClearPath Diagnostic Laboratory (Fictional)

**Dataset:** 1,000 Synthetic Records

**Primary Tool:** Microsoft Excel
