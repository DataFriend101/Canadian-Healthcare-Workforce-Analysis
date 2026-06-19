# Canadian Healthcare Workforce Analysis
A Power BI analysis of healthcare workforce supply, demographics, and growth trends across Canadian provinces and territories, 2020–2024.

# Project Overview
This project examines how Canada's healthcare workforce* has changed over a four-year period, with a focus on geographic distribution, demographic composition, and growth patterns.

*This analysis covers four professions: Physicians, Physiotherapists, Psychologists, and Registered Nurses — selected for complete data availability across all provinces and years.

# Tools Used
- Microsoft Excel (data structuring)
- Power BI (analysis and visualization)

# Explanation of the Analysis and Visualization in Power BI
**Canadian Healthcare Workforce Overview (Page 1):**
Maps and ranks healthcare worker rates per 100,000 population across all provinces and territories, filterable by profession

*Key finding:* Nunavut and Northwest Territories show the highest rates per capita of healthcare workers*, driven by small population denominators rather than abundant healthcare access

**Healthcare Workforce Demographics (Page 2):**
Explores age distribution and gender composition across the four professions

*Key finding:* 350k workers are aged 60+, with Physicians and Psychologists showing the highest concentration of near-retirement professionals. Registered Nursing remains ~90% female and has stayed flat since 2020, while Physicians show a slow shift toward gender balance (43% → 47% female, 2020–2024).

**Healthcare Workforce Trends (2020–2024) (Page 3):**
Tracks total workforce size, growth rate by profession, and year-over-year change.

*Key finding:* The workforce grew 10.92% from 2020 to 2024 (444K → 492K workers), with growth accelerating sharply in 2024. Physiotherapists showed the highest percentage growth (18.3%), though Registered Nurses added the most workers in absolute terms.

# Data sources
- Canadian Institute for Health Information (CIHI) — Health Workforce in Canada, 2020–2024
(https://www.cihi.ca/en/health-workforce-in-canada-overview)

# Files 
- Canadian Healthcare Workforce Analysis.pbix — Power BI file
- Canadian Health Workforce (2020-2024) Clean  — Cleaned source data (Profession, Training, Population tables)
- Health Workforce Canada (2020-2024) Raw - CIHI dataset

# Data Notes
- All figures represent 4 professions only: Physicians, Physiotherapists, Psychologists, and Registered Nurses.
Selected for complete data availability across all provinces and years. 
- Northwest Territories and Nunavut report combined Registered Nurse counts under CIHI methodology; this affects per-capita rate comparisons for these two territories specifically, which was mentioned in the excel and the Power BI file.
- Some demographic breakdowns (age, gender) contain suppressed or missing values for smaller provinces/territories, consistent with CIHI's privacy thresholds for small sample sizes.
