## HEALTHCARE DATASET 
Filtered and structure the raw healthcare dataset by removing inconsistence, unnecessary fields, and organizing columns for analysis.

Due to large file, size dataset is hosted on google drive:
[download dataset] 
[https://docs.google.com/spreadsheets/d/1D3IY7gv7bcXT3r38vfhQ7zE1iFlEJLc_/edit?usp=drive_link&ouid=102171691396979325428&rtpof=true&sd=true]

Created Pivot Table to summarize key metrics such as total patients, revenue, admission type, medical condition, year, Insurance provider and result.

[https://drive.google.com/file/d/15bU_isRGVF9-3tKpPOjbaQ7f4wNQbexK/view?usp=drive_link]

Built an interactive healthcare performance dashboard in excel using pivot charts, slicers, and KPI cards.

[https://drive.google.com/file/d/1wK99HLp030DznmpLjrqvANuzfUhLfuQM/view?usp=drive_link]

POWER BI DASHBOARD

Desighned an advanced power bi dashboard with data modeling, DAX measure, and interactive visualization.

[https://drive.google.com/file/d/148WCEGxhnTnqLH_8uZvycydjTCkYKDyE/view?usp=drive_link]


Project Title
Healthcare Data Analysis – Excel & Power BI

📌 Project Objective

To analyze hospital data and identify trends in patient admissions, revenue, average stay duration, and medical conditions.

📌 Tools Used

Microsoft Excel (Data Cleaning + Pivot + Dashboard)

Power BI (Data Modeling + DAX + Dashboard)

📌 Key KPIs

Total Patients

Total Revenue

Average Stay Duration

Abnormal Test Result %

📌 Analysis Performed

Admission Type Analysis

Gender-wise Distribution

Medical Condition Analysis

Monthly Admission Trend

Top Revenue Generating Hospitals

📌 DAX Measures Used (Example)
Total Patients = COUNT(healthcare_dataset[Patient ID])

Total Revenue = SUM(healthcare_dataset[Billing Amount])

Average Stay = AVERAGE(healthcare_dataset[Stay Duration])

Abnormal % = DIVIDE(CALCULATE(COUNT('healthcare_dataset6'[Test Results]),'healthcare_dataset6'[Test Results]="Abnormal"),count('healthcare_dataset6'[Test Results]))

📌 Business Insights

Most patients were admitted through Emergency.

Revenue peak observed in specific months.

Certain medical conditions generated higher billing revenue.

Average stay duration varies by admission type

Revenue by insurance provider.
