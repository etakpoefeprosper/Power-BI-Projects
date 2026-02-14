
# Health Analytics Dashboard Report  
**Comprehensive Analysis of Nigerian Health Data**  

---
<img width="952" height="678" alt="image" src="https://github.com/user-attachments/assets/6af6176a-45f6-4af8-9904-780ec2fd9592" />

<img width="947" height="675" alt="image" src="https://github.com/user-attachments/assets/ccf13789-04ce-47ff-a936-9640896abe30" />

---

**Tools Used:** Microsoft Excel (Data Cleaning & Preparation) • Power BI (Interactive Dashboard & Visualizations)  

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Data Overview & Methodology](#data-overview--methodology)
- [Key Insights](#key-insights)
  - [1. Demographic Patterns](#1-demographic-patterns)
  - [2. Lifestyle & Behavioral Risk Factors](#2-lifestyle--behavioral-risk-factors)
  - [3. Hidden Patterns Discovered](#3-hidden-patterns-discovered)
- [Recommendations](#recommendations)
- [Dashboard Screenshots](#dashboard-screenshots)
- [Final Thoughts](#final-thoughts)

---

## Executive Summary

This report analyzes a comprehensive health dataset of **312,000 patients** across Nigeria. Using Excel for data wrangling and Power BI for advanced visualizations, critical patterns were uncovered in disease prevalence, demographic risk factors, and lifestyle contributors.

### Key Highlights
- **Total Patients**: 312K  
- **Gender Split**: Male 52.14% (163K) | Female 47.86% (149K)  
- **Overall Health Status**:  
  - Healthy: **63%** (196K)  
  - One Ailment: 82K  
  - Multiple Ailments: 33K  
- **Average BMI**: **27.94** (Overweight category)  
- **Top Diseases by Prevalence**:

| Disease          | Count   | Prevalence Rate |
|------------------|---------|-----------------|
| Diabetes         | 41K     | **13.00%**      |
| Asthma           | 41K     | **13.12%**      |
| Skin Cancer      | 29K     | **9.00%**       |
| Heart Disease    | 27K     | **8.51%**       |
| Stroke           | 12K     | **3.75%**       |
| Kidney Disease   | 11K     | **4.00%**       |

**Major Insight**: Metabolic and respiratory conditions dominate, while cardiovascular risks escalate sharply with age and vary significantly by ethnicity.

---

## Data Overview & Methodology

### Data Source
- **312,000 records** of Nigerian patients  
- Variables: Age, Gender, Tribe, BMI, Smoking status, Obesity, Physical activity, Sleep, Mental health, Disease indicators (Heart Disease, Diabetes, etc.)

### Methodology
1. **Excel Phase**  
   - Data cleaning (removed duplicates, handled missing values, standardized tribe names)  
   - Created calculated columns (Age Groups, BMI Categories, Risk Scores)  
   - Pivot tables for initial exploration  

2. **Power BI Phase**  
   - Imported cleaned Excel file  
   - Built DAX measures for prevalence rates, risk ratios, and percentages  
   - Designed interactive dashboard with slicers (Gender, Tribe, Age Group)  
   - Used custom themes and icons for professional medical look  

---

## Key Insights

### 1. Demographic Patterns

#### Gender Distribution

- Males slightly outnumber females (52.14% vs 47.86%)  
- **Heart Disease Prevalence by Gender**: Females account for **61.53%** of all heart disease cases (despite being 47.86% of population) → **Higher burden on women**

#### Age & Heart Disease

**Clear exponential trend**:
- 18–24 years: **0.60%**  
- 50–54 years: **5.28%**  
- 70–74 years: **15.52%**  
- **80+ years: 22.55%** (37× higher than youngest group)

**Interpretation**: Age is the strongest predictor of heart disease in this population.

#### Ethnic (Tribe) Variations

| Tribe         | Heart Disease Prevalence |
|---------------|--------------------------|
| Tiv           | **10.40%**               |
| Yoruba        | 9.13%                    |
| Other         | 8.09%                    |
| Hausa-Fulani  | 7.37%                    |
| Igbo          | 5.22%                    |
| Ibibio        | 3.25%                    |

**Insight**: Tiv and Yoruba populations show significantly elevated risk — potential genetic, dietary, or environmental factors warrant further study.

### 2. Lifestyle & Behavioral Risk Factors

#### Smoking & Obesity
- **Smokers**: 128K (**41%** of total population)  
- **Obese**: 96K (**31%**)  

**Smoking peaks in 60–69 age group** (15.1K–15.2K smokers) — exactly where heart disease risk also spikes.

#### Other Prevalence Metrics

| Metric                     | Value      | % of Population |
|----------------------------|------------|-----------------|
| Difficulty Walking         | 41K        | **13%**         |
| Sleep Deprivation          | 29K        | **9%**          |
| Poor Mental Health         | —          | **8%**          |
| Alcohol Consumption        | —          | **7%**          |
| Average Physical Activity  | **3.27**   | 78% active      |

**Heart Disease Risk Among High-Risk Groups**:
- Among **Smokers**: Only **5.98%** have heart disease  
- Among **Obese Patients**: Nearly **48.4%** affected  
- Among **Diabetics**: **13%** have heart disease (same rate for both genders)

### 3. Hidden Patterns Discovered

1. **Female Vulnerability**  
   Despite lower smoking rates, women bear a disproportionate heart disease burden — possibly linked to higher obesity or post-menopausal risks.

2. **Urban-Rural Divide?**  
   Tribes with higher prevalence (Tiv, Yoruba) may correlate with dietary shifts in certain regions.

3. **Preventable Burden**  
   41% smoking rate + 31% obesity = massive opportunity for public health intervention.

---

## Recommendations

### Immediate Actions (0–6 months)
- Targeted Screening: Mobile clinics for 65+ age group in Tiv and Yoruba communities  
- Smoking Cessation: National campaign focused on 55–74 age bracket  
- Women’s Heart Health: Integrate heart disease screening into routine maternal and reproductive health visits

### Medium-Term (6–18 months)
- Community Programs: Partner with tribal leaders for culturally tailored nutrition and exercise initiatives  
- Digital Tracking: Develop simple Excel/Power BI templates for local clinics  
- Policy: Advocate for sugar/salt taxes and workplace wellness mandates

### Long-Term (18+ months)
- Longitudinal Study: Track the same cohort over 5 years  
- AI Predictive Model: Build risk scoring model (age + tribe + BMI + smoking)

---

## Dashboard Screenshots

**Dashboard 1**: Overview & Demographic Insights  
![Overview Dashboard](<img width="64" height="46" alt="image" src="https://github.com/user-attachments/assets/051b1fd1-ec53-418a-8341-34b46e855619" />)

**Dashboard 2**: Prevalence Metrics & Risk Factors  
![Prevalence Dashboard](<img width="947" height="675" alt="image" src="https://github.com/user-attachments/assets/ccf13789-04ce-47ff-a936-9640896abe30" />)

---

## Final Thoughts

This dataset paints a concerning but actionable picture of Nigeria’s health landscape. **63% of the population is still healthy** — we have a window of opportunity to prevent the next wave of chronic disease.

The combination of **Excel’s precision** and **Power BI’s storytelling** made complex insights accessible to non-technical stakeholders.

**Let’s turn data into healthier lives.**

---
