
📊 Analyzing Healthcare Data in Power BI
🩺 Case Study: Hospital Discharges Analysis - New York State
📁 Project Description
This Power BI dashboard project presents an in-depth analysis of hospital discharge data from healthcare facilities across New York State. It utilizes a rich dataset containing detailed information about patient demographics, clinical procedures, diagnoses, hospital performance, and resource utilization metrics. The purpose of this case study is to uncover patterns and key influencers that affect hospital length of stay (LOS) and cost per discharge, helping healthcare administrators, analysts, and policymakers make informed decisions.

📄 Dataset Overview
The dataset includes over 26,000 discharge records from 151 hospitals and covers multiple dimensions:


Field Name	Description
facility_name, facility_id	Identifiers for healthcare facilities
age_group, gender, race, ethnicity	Demographic information of patients
length_of_stay (LOS)	Duration of hospital stay in days
type_of_admission	Admission type (e.g., Emergency, Elective, Trauma)
patient_disposition	Discharge status (e.g., Home, Rehabilitation, Skilled Nursing Facility)
ccs_diagnosis_description	Clinical classification of diagnoses
ccs_procedure_description	Clinical classification of procedures
apr_severity_of_illness_description	Severity level from Minor to Extreme
apr_risk_of_mortality	Mortality risk level (1 to 4)
total_charges, total_costs	Financial metrics of care
The classification systems used include:

AHRQ CCS: Clinical Classification Software for diagnosis and procedure grouping

APR-DRG: All Patient Refined Diagnosis Related Groups for severity and resource tracking

📝 More on these systems:

HCUP CCS

NY State DOH APR-DRG

📊 Key Insights & Visualizations
1. Average Length of Stay (LOS) by Hospital
Average LOS across hospitals is 2.65 days.

Kings County Hospital Center, Interfaith Medical Center, and Memorial Hospital for Cancer and Allied Diseases have the highest LOS, reaching up to 12 days.

The lowest LOS (<2 days) was observed in Northern Dutchess Hospital, St. Elizabeth Medical Center, and Alice Hyde Medical Center.

2. Average Cost per Discharge
The overall average cost per discharge is $20,910.

Highest-cost hospitals include NYU Lutheran Medical Center ($85K) and Olean General Hospital.

Lowest-cost facilities are located in Southern Tier and Capital/Adirondack regions, such as Newark-Wayne Community Hospital.

3. Top Influencers on LOS
LOS significantly increases when:

apr_severity_of_illness_description is Extreme

apr_risk_of_mortality is Major or Extreme

health_service_area is New York City

patient_disposition is Skilled Nursing Facility

4. Most Common Diagnoses
Osteoarthritis and Complication of orthopedic device account for over 89% of discharges in orthopedic-focused hospitals.

5. Disposition Patterns
Majority of patients are discharged to:

Home/self-care (73%)

Home with home health services (10%)

Skilled Nursing Facilities (4.3%)

🧠 Business Applications
Hospital Benchmarking: Identify outliers with higher-than-average LOS or cost.

Resource Optimization: Target hospitals and patient profiles where extended stays can be mitigated.

Policy Support: Guide healthcare planning for post-discharge care services.

🛠️ Tools & Technologies
Power BI Desktop for dashboard creation and data modeling

DAX & Power Query for data transformation

Custom visuals for key influencers, LOS-cost correlation, and segmentation analysis

📌 How to Use This Project
Open the .pbix file in Power BI Desktop.

Explore the dashboard pages:

LOS Comparison

Cost Comparison

Hospital Profile

Filter by hospital name, diagnosis, or geographic region to analyze targeted insights.
