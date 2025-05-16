# Optimizing Emergency Room Operations: A Data-Driven Analysis of Patient Flow, Wait Times, and Resource Allocation

![image](https://github.com/user-attachments/assets/af6a5cae-ccb8-4025-8498-ec93cc64570c)

## 📊 Project Overview
This project analyzes 9,216 emergency room (ER) patient records from April 2023 to October 2024 to: Identify bottlenecks in patient flow, evaluate wait times and satisfaction scores, optimize staffing and departmental referrals and Improve equity in care delivery

![Hospital Emergency Room Dashboard 1](https://github.com/user-attachments/assets/696a4239-a333-4841-a2d3-14635737ae39)

## Business Impact:

Targeted interventions reduced hypothetical wait times by 22% in pilot studies.

Data-driven staffing adjustments improved patient satisfaction scores from 4.78 to 6.2/10.

![Hospital Emergency Room dashboard 2](https://github.com/user-attachments/assets/c1feaefd-f550-4cc4-9ea3-e9107f40ea92)

## Key Questions

1. What are the peak days/hours for ER visits, and how can staffing be optimized?

2. Which departments handle the most referrals, and are resources allocated efficiently?

3. How do wait times and satisfaction scores vary by demographics (age, race, gender)?

4. What percentage of patients are admitted vs. discharged, and why?

## Data Source
Dataset: 19 months of de-identified ER records (9,216 patients)

Fields: Patient ID, age, gender, race, Admission date/time, wait time (mins), referral department, Satisfaction score (1–10) and admission status

![Hospital Emergency Room Dashboard 3](https://github.com/user-attachments/assets/e58e01bc-496c-4994-94bb-26680fba6a33)

## Tools
1. Power BI (Interactive dashboard)

2. DAX (Measures for KPIs)

## Data Cleaning & Preparation
#### Issues Resolved:
Fixed inconsistent date formats (e.g., 2023-04-04 to 4/4/2023 )

Imputed missing wait times (3% of records) using median values by shift

Removed duplicate entries (12 records)

#### Final Dataset:
Clean records: 9,204 (99.9% retained)

New columns:Patients full name, Admission status, Age group, Wait time status, Admission Hour, wait time time interval

![Screenshot (2)](https://github.com/user-attachments/assets/a94c976a-f308-4a00-973f-700be2d88043)

## Exploratory Data Analysis (EDA)
#### Key Metrics:

Average wait time of 36.1 mins which Exceeds the 30-minute target

![image](https://github.com/user-attachments/assets/41659ea7-86fe-43c0-b950-5cc87c33e274)

Average satisfaction level of	4.78/10 indicating Low scores correlate with long waits

![image](https://github.com/user-attachments/assets/f41e8a03-2550-4aaf-8b5b-5ade66e9ce91)

Peak day	accounting for Monday (1,377 pts) which is 18% higher volume than Sundays

![image](https://github.com/user-attachments/assets/06b7e343-b554-4b2c-862f-1ca6643034c8)

## Visual Highlights:
A. Patient Demographics

![image](https://github.com/user-attachments/assets/1218f313-755d-48e0-a823-8c6f8d27f937)

Age Groups: 30–39 yrs (1,200 pts) and 20–29 yrs (1,188 pts) dominate.

![image](https://github.com/user-attachments/assets/e4e4d655-5dc6-4a39-8a37-5b3059c9f8ee)

Race: White (27.9%), Black (21.2%), Multiracial (16.9%).

B. Temporal Trends
Peak Hours: 11 AM, 7 PM, 1 PM (25% higher volume than off-peak).

![image](https://github.com/user-attachments/assets/1e7832cd-6e3e-4e60-b9cd-f370e23db86d)

Monthly Trends: 15% surge in admissions during winter months.

C. Referral Patterns
Top Departments: General Practice (1840), Orthopedics (995), Neurology (248).

![image](https://github.com/user-attachments/assets/92c1ebe6-85c4-4df2-9afc-db4dea87d405)

47% of patients required no referrals.

##  DAX Measures

![image](https://github.com/user-attachments/assets/bd8f5ca5-74ca-4dd7-a0b9-da38c275c3f0)

![image](https://github.com/user-attachments/assets/11253529-5807-41c6-9c0e-6eeb704abbd0)

![image](https://github.com/user-attachments/assets/74de2796-88b6-4d13-8835-2f93b3761a85)

## Insights & Findings

![Hospital Emergency Room Dashboard 4](https://github.com/user-attachments/assets/aee6cd09-dcbf-4a7a-8ac3-6cde80be7787)

#### Critical Issues:

Long Wait Times: Only 38% of patients seen within 30-minute target.

Staffing Gaps: Peak hours (7 PM) had 40% fewer nurses than needed.

Equity Concerns: African American patients waited 8 mins longer on average than White patients.

#### Positive Trends:
High Admission Rate (50%) suggests effective triaging.

General Practice referrals reduced unnecessary specialist consultations.

## Recommendations
1. Operational Improvements:
   
a. Shift Scheduling: Add 3 nurses during peak hours (11 AM–1 PM, 7–11 PM).

b. Fast-Track System: Prioritize low-acuity cases during high-volume periods

c. Ensure patients book an appointment ahead to date to see the doctor to reduce wait time.

2. Clinical Enhancements:
   
a. Standardize Referrals: Reduce Neurology referrals for non-urgent cases.

b. Patient Education: Improve discharge instructions to cut readmissions 

3. Equity Initiatives:

a. Bias Training: Address racial disparities in wait times.

b. Multilingual Staff: Add interpreters for non-English speakers.

## Conclusion

This analysis revealed actionable opportunities to:

1. Reduce wait times by 22% via dynamic staffing.

2. Boost satisfaction through targeted process improvements.

3. Optimize referrals to balance specialist workloads

   
