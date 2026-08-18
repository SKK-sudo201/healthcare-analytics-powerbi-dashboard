# 🏥 Apollo Hospital Performance Tracker | Power BI Data Analytics Project
An end-to-end healthcare analytics project built in Power BI to track hospital performance across patient admissions, bed occupancy, physician workload, revenue, and treatment outcomes.

## Business Problem
Hospitals generate large volumes of operational and patient data. Without proper analysis, it becomes difficult to monitor performance, identify bottlenecks, and improve patient care.
This project addresses these challenges by creating an interactive dashboard that tracks key healthcare metrics.

## Key KPIs
•	Total Patients
•	Patient Admissions
•	Occupancy Rate
•	Revenue Analysis
•	Treatment Outcomes
•	Average Length of Stay

## Project Overview
This project analyzes 7,157 patient records from a hospital operations dataset spanning December 2022 to March 2024, transforming raw admissions, billing, and feedback data into an interactive Power BI dashboard for operational decision-making.

## Key Results
| Metric | Result |
|---|---|
| Patient records analyzed | 7,157 |
| Total billing tracked | $190.4M |
| Insurance coverage ratio | 90% of billing covered by insurance |
| Average length of stay | 8.2 days (median: 5 days) |
| Bed occupancy mix | 50% Private / 33% General / 17% ICU |
| Peak admission month | March 2023 —> 609 admissions |
| Patient satisfaction | 82.5% of patients rated care 4.5★ or higher |
| Most common diagnosis | Viral Infection —> 28% of all cases |
| Most common test ordered | Blood Test —> 31% of all tests ordered |
| Physician workload | Evenly distributed, ~1,020 patients per physician (7 physicians) |

## What Was Done
## 1. Data Cleaning & Modeling
Cleaned and structured raw patient-level records (admissions, discharge, diagnosis, billing, insurance, feedback) for analysis
## 2. KPI Dashboard Design
Built interactive Power BI dashboards tracking admissions trends, occupancy rates, physician performance, and revenue
## 3. Trend Analysis
Identified peak admission periods and seasonal patterns in patient volume
## 4. Financial Analysis
Analyzed billing vs. insurance coverage, average cost per diagnosis, and revenue distribution
## 5. Outcome Tracking
  Summarized patient feedback and satisfaction scores across diagnoses and    physicians

## Dataset
The `dataset` (hospital_performance_data.csv) contains the following fields:
•	`Patient_ID`- unique patient identifier
•	`Admit_Date` / `Discharge_Date`- admission and discharge dates
•	`Diagnosis`- one of 6 categories (Viral Infection, Flu, Malaria, Typhoid, Pneumonia, Fracture)
•	`Bed_Occupancy` - Private / General / ICU
•	`Test` -diagnostic test ordered (Blood Test, MRI, CT Scan, X-Ray, Ultrasound)
•	`Doctor` - attending physician
•	`Followup Date` - scheduled follow-up date
•	`Feedback` - patient satisfaction score (out of 5)
•	`Billing Amount` - total billed amount (USD)
•	`Health Insurance Amount` -portion covered by insurance (USD)

## Tools & Skills Utilized
Power BI · Microsoft Excel · Data Cleaning · Data Modeling · DAX · KPI Dashboard Design · Healthcare Analytics · Business Intelligence

## Skills Demonstrated
•	Data Analysis
•	Data Cleaning
•	Data Modeling
•	Power BI Dashboard Development
•	KPI Reporting
•	Business Intelligence
•	Data Visualization
•	Healthcare Analytics

## Dashboard Features
•	Executive Overview
•	Hospital Performance Summary
•	Revenue Trends
•	Occupancy Monitoring
•	Patient Analytics
•	Admission Trends
•	Discharge Analysis
•	Treatment Success Rate
•	Revenue Analysis
•	Monthly Revenue
•	Revenue by Department
•	Revenue Trends

##  Key Insights
•	Identified peak patient admission periods for proactive staffing planning
•	Tracked occupancy utilization trends across bed categories
•	Evaluated physician workload and revenue contribution
•	Monitored insurance coverage ratio and billing trends by diagnosis
•	Summarized treatment outcomes via patient satisfaction feedback

## Dashboard Screenshots
<img width="1306" height="732" alt="Single-Patient Drill-Down Patient-Level Drill-Down for Granular Insight" src="https://github.com/user-attachments/assets/0f653eba-a296-4b2c-bfc4-451114169e17" />
<img width="1308" height="731" alt="Full Dashboard Overview End-to-End Hospital Performance Dashboard" src="https://github.com/user-attachments/assets/52468866-4014-4fb3-baeb-722d60da3774" />
<img width="1305" height="730" alt="Filtered Time-Range View Dynamic Date-Range Filtering in Action" src="https://github.com/user-attachments/assets/abd8df0e-076a-4f5b-aad4-5faec079393c" />
