# Healthcare Claims Denial Analysis – SQL Project

## Overview
This project focuses on analyzing healthcare claims data to uncover **denial patterns, reasons, financial impact, and trends**. It demonstrates SQL skills in **database creation, query design, and healthcare analytics**, with practical applications in **Revenue Cycle Management (RCM)**.

## Features
- **Database Setup**: `healthcare` database with `claims` table  
- **Denial Insights**:
  - Total claims vs. denied claims
  - Denial reasons and their frequency
  - Department-wise and procedure-wise denial counts  
- **Trend Analysis**:
  - Monthly denial counts and denial rate percentages
  - Diagnosis and procedure code denial trends over time
  - Denial reason trends by month  
- **Financial Metrics**:
  - Highest and lowest denied claim amounts
  - Average denied claim amount per department  
- **Clinical Insights**:
  - Most common diagnosis codes in denied claims  

## Skills Demonstrated
- SQL database design (`CREATE DATABASE`, `CREATE TABLE`)
- Aggregation and grouping (`COUNT`, `SUM`, `AVG`, `GROUP BY`)
- Conditional logic (`CASE WHEN`)
- Time-based analysis (`MONTH(Date_of_Service)`)
- Healthcare domain knowledge in denial management

## Repository Structure
- `queries.sql` → All SQL queries used for analysis
- `README.md` → Documentation and usage guide

## Use Cases
- Identify high-risk departments and procedures with frequent denials  
- Understand denial reasons to improve claim acceptance rates  
- Support healthcare RCM teams with actionable insights  

## Future Enhancements
- Add sample dataset for reproducibility  
- Visualize denial trends using Python/Power BI  
- Extend analysis to include payer-level insights  
