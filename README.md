
 # Primary-Health-Center-Analytics-Nigeria
---
## Table of Contents
- [Project Scope](#project-scope)
- [Data Sources](#data-sources)
- [Tool Used](#tool-used)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis Performed](#exploratory-data-analysis-performed)
- [EDA Visual Insights](#eda-visual-insights)
- [Data Analysis](#data-analysis)
- [Results / Findings](#results--findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project Scope
This project analyzes **Primary Health Center (PHC) performance across Nigeria** using simulated healthcare data.  
The objective is to evaluate **patient outcomes, disease burden, facility distribution, and workforce capacity** to understand how well PHCs are positioned to meet public health demands.

The dashboard is structured into four analytical views:
- Executive Overview
- Disease Analysis
- Patient Analysis
- Facility Analysis

The analysis focuses on identifying **healthcare access gaps, workload imbalances, and disease pressure points** across states.

 ![_6750_PHC_page-0001__153_PHC_page-0002](https://github.com/user-attachments/assets/5c5a6356-259d-4199-aa08-2ae1412cd3a1)


---

### Data Sources
The dataset used for this project is **simulated PHC data** designed to reflect healthcare delivery patterns across Nigeria.

Key data domains include:
- Patient records
- Disease reports
- Facility operational status
- Health workforce distribution
- State-level healthcare summaries
- Time-based reporting (Year, Month)

The simulation mirrors real-world public health reporting structures commonly used in PHC systems.

---

### Tool Used
- Microsoft Power BI – Data modeling, DAX calculations, and dashboard design  
- Power Query – Data transformation, data quality checks, and normalization  
- DAX – KPI creation, ratios, and performance indicators  

---

### Data Cleaning & Preparation
1. Standardized numerical fields for patient counts, disease cases, and workforce figures.
2. Ensured consistent state and facility naming conventions.
3. Created calculated measures for recovery rate, mortality burden ratio, and patient load.
4. Validated time-based fields (Year, Month Name) for trend analysis.
5. Grouped age bands and disease categories for meaningful aggregation.
6. Verified operational status classification for PHCs (Functional, Partially Functional, Non-Functional).

---

### Exploratory Data Analysis Performed
The EDA focused on **population health outcomes and system capacity**. Key KPIs analyzed include:
- Total Patients
- Recovered Patients
- Recovery Rate (%)
- Total Disease Cases Reported
- Total Death Cases
- Mortality Burden Ratio
- Number of PHCs
- Functional vs Non-Functional PHCs
- Health Workers Count
- Average Years of Experience (YOE)

---

### EDA Visual Insights
- Recovery rates are high overall, but vary across time and patient volume.
- Disease burden is heavily concentrated in a small number of illnesses.
- Patient volume fluctuates monthly, indicating seasonal health pressure.
- A significant portion of PHCs are non-functional or partially functional.
- Certain states carry a higher patient load per facility due to lower facility counts.
- Workforce distribution does not scale evenly with patient demand across states.

---

### Data Analysis
Using DAX:
- SUM and COUNT measures were applied to patient, disease, and workforce volumes.
- Ratio metrics were created for recovery rate and mortality burden analysis.
- Patient load per facility was calculated to assess operational stress.
- Comparative analysis across states highlighted disparities in access and capacity.
- Trend analysis was used to evaluate monthly disease and patient reporting patterns.

---

### Results / Findings
From the dashboard analysis:
- Malaria remains the most reported disease across PHCs.
- Recovery rate exceeds 98%, but absolute death cases remain significant due to high volume.
- States with fewer functional PHCs experience higher patient load per facility.
- Workforce availability does not consistently align with patient demand.
- Children and young adults represent the largest share of reported cases.
- Monthly disease reporting shows recurring seasonal peaks.

---

### Recommendations
Based on the insights:
1. Prioritize reopening and upgrading non-functional PHCs in high-burden states.
2. Redistribute health workers to facilities with extreme patient load.
3. Strengthen malaria prevention and early intervention programs.
4. Use patient load metrics to guide future PHC expansion planning.
5. Monitor seasonal disease trends to improve preparedness and resource allocation.

 
