# hr-attrition-analysis-fabric-powerbi
End-to-end HR Attrition Analytics project using Microsoft Fabric, Dataflow Gen2, Lakehouse, Power Query, DAX, Semantic Model and Power BI.
# HR Attrition Analysis – Microsoft Fabric & Power BI

## 📊 Project Overview

This project demonstrates an end-to-end HR Attrition Analytics solution built using Microsoft Fabric and Power BI.

The objective is to analyze employee attrition patterns and identify trends across demographics, compensation, job satisfaction, overtime, business travel, education, marital status, and other HR-related dimensions.

## 🏗️ Architecture

Source Data
    ↓
Dataflow Gen2
    ↓
Power Query / M
    ↓
Microsoft Fabric Lakehouse
    ↓
Semantic Model
    ↓
Power BI Report

## 🛠️ Technologies & Skills

- Microsoft Fabric
- Power BI
- Power Query
- M Language
- Dataflow Gen2
- Fabric Lakehouse
- Semantic Model
- Direct Lake
- DAX
- Data Transformation
- Data Visualization
- HR Analytics

## 🔄 Data Transformation

Power Query was used to clean and transform the HR dataset.

Key transformations include:

- Data type standardization
- Data cleansing
- Conditional columns
- Derived attributes
- Age Group classification
- Data preparation for analytical reporting

### Example – Age Group

```powerquery
if [Age] <= 25 then "18 to 25"
else if [Age] <= 35 then "26 to 35"
else if [Age] <= 45 then "36 to 45"
else if [Age] <= 60 then "46 to 60"
else "Above 60"

📈 Power BI Dashboard
The dashboard provides analysis of:
- Overall Attrition Rate
- Employee Headcount
- Employees Left
- Average Tenure
- Attrition by Gender
- Attrition by Age Group
- Attrition by Education
- Attrition by Marital Status
- Attrition by Overtime
- Attrition by Business Travel
- Attrition by Salary Band
- Department-level analysis
🧮 DAX Measures
Examples of analytical measures include:
- Attrition Rate
- Employee Headcount
- Employees Left
- Average Tenure
- Average Tenure of Leavers
🎯 Key Learning Outcomes
- Building an end-to-end Microsoft Fabric analytics workflow
- Working with Dataflow Gen2 and Power Query
- Loading transformed data into a Fabric Lakehouse
- Creating and managing Semantic Models
- Developing DAX measures
- Designing interactive Power BI dashboards
- Applying data transformation and analytical techniques to HR data
📷 Dashboard
Add screenshots of the Power BI dashboard here.
### Overview

<img width="770" height="494" alt="HR Attrition 1 Overview" src="https://github.com/user-attachments/assets/da337654-4122-488d-9fc8-fbf2c70bf6c4" />


### Deep Dive

<img width="842" height="486" alt="HR attrition 2 Deep Dive" src="https://github.com/user-attachments/assets/4c36f901-f7e6-4e5a-85e0-452ac2185c16" />

