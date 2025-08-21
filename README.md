🏥 Hospital Emergency Room Dashboard

This project presents an interactive dashboard for analyzing Hospital Emergency Room (ER) performance using patient-level data. The dashboards were created in Power BI (or similar BI tool) to provide hospital administrators with real-time insights into ER efficiency, patient demographics, and overall satisfaction.

📊 Dataset

The dataset used for this dashboard is provided in Hospital ER_Data.csv.
It contains details about ER visits, including:

Patient Id – Unique identifier for each patient

Full Name – Patient name

Age – Patient age (summed in dashboard visuals)

Department Referral – Department to which the patient was referred (e.g., General Practice, Orthopedics, Cardiology, Physiotherapy, Gastroenterology, etc.)

Patient Gender – Male / Female / Not Confirmed

Patient Race – Ethnic/racial category of the patient

Wait Time (min) – Time each patient spent waiting for care

📈 Dashboards Overview
1. Monthly View Dashboard

(Refer to dashboard_monthly.png)

Key KPIs:

No. of Patients: 431 (for selected month)

Average Wait Time: 36.67 minutes

Patient Satisfaction Score: 4.72 / 5

No. of Patients Referred: 179

Visuals included:

Patient Admission Status (Admitted vs. Not admitted)

Patients Seen within 30 Minutes (Target vs. Missed)

No. of Patients by Age Group

No. of Patients by Department Referral

No. of Patients by Race

Patient Visits by Day & Hour (heatmap)

2. Patient Details Dashboard

(Refer to dashboard_details.png)

This dashboard provides a tabular patient-level view, showing:

Patient Id & Name

Age

Department Referral

Gender

Race

Wait Time

This view helps drill down from aggregated KPIs into specific patient records for auditing and detailed analysis.

🔍 Key Insights

Majority of patients fall in the 30–49 age group.

Roughly 52% patients were admitted, while 48% were not admitted.

Average wait time was ~37 minutes, with 66% patients seen within 30 minutes.

Wednesday had the highest number of ER patients.

General Practice referrals dominate, followed by Orthopedics.

By race, White and African American patients form the largest groups.


🛠 Tools Used

Power BI / Tableau (for visualization)

CSV Dataset (patient-level data)
