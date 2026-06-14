# Healthcare Patient Analytics
## Diabetes Readmission Analysis | Python · Tableau · Power BI

## Project Overview
A comprehensive analysis of diabetic patient readmission
patterns using real clinical data from 130 US hospitals
over 10 years. The project applies machine learning
(Random Forest classifier) to predict 30-day readmission
risk and identifies key clinical and demographic factors
driving hospital readmissions a $26 billion problem
in US healthcare.

---

##  Interactive Dashboards

### Tableau Dashboard
**[View Tableau Dashboard](https://public.tableau.com/app/profile/varshini.karuppusamy/viz/HealthcarePatientAnalyticsDashboard_17814679372600/Dashboard1?publish=yes)**

### Power BI Dashboard
**[View Power BI PDF](PowerBI/Healthcare_Patient_Analytics.pdf)**

---


## Dataset
| Detail | Value |
|--------|-------|
| Source | UCI ML Repository - Diabetes 130-US Hospitals |
| Records | 100,000+ patient encounters |
| After cleaning | ~70,000 unique patients |
| Columns | 50 clinical and demographic features |
| Period | 10 years of hospital records |
| Target | 30-day readmission (binary) |

**Download:**
kaggle.com/datasets/brandao/diabetes

---

## Business Questions Answered
- What factors predict 30-day hospital readmission?
- Which age groups have the highest readmission rates?
- How does length of stay affect readmission risk?
- Which medications are associated with better outcomes?
- How does number of diagnoses affect readmission risk?
- Are there demographic disparities in readmission rates?

---

## Tools & Technologies
| Category | Tools |
|----------|-------|
| Language | Python 3.10 |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Models | Logistic Regression, Random Forest |
| BI Tools | Tableau Public, Power BI Desktop |
| DAX | Custom measures for KPIs |

---


## Key Findings

1. **Overall readmission rate is ~11%** across all
   patients — consistent with national US averages

2. **Elderly patients (70-80 age group)** show the
   highest readmission rates — driven by multiple
   chronic conditions

3. **Number of inpatient visits** is the strongest
   predictor of readmission — more than length
   of stay or medication count

4. **Patients with 7+ diagnoses** have significantly
   higher readmission risk than those with fewer
   comorbidities

5. **Random Forest model achieved AUC > 0.65**
   identifying high-risk patients before discharge

6. **Demographic disparities exist** — certain
   racial groups show statistically higher
   readmission rates suggesting systemic gaps
   in care coordination

---

## Tableau Dashboard Features
- Readmission rate by age group (bar chart)
- Length of stay distribution (bar chart)
- Clinical factors heatmap (diagnoses vs stay)
- Medications vs readmission rate (line chart)
- Interactive filters by age, gender, race

## Power BI Dashboard Features
- 4 KPI cards (readmission rate, patients,
  avg stay, high risk count)
- Readmission by age (bar chart)
- Readmission by gender (donut chart)
- Readmission by race (bar chart)
- Length of stay line chart
- Medications vs readmission line chart
- Diagnoses vs readmission column chart
- Age, gender, race slicers

---

## Machine Learning Results

| Model | AUC Score |
|-------|-----------|
| Logistic Regression | ~0.62 |
| Random Forest | ~0.65+ |

**Top predictors of readmission:**
1. Number of inpatient visits
2. Number of diagnoses
3. Number of emergency visits
4. Time in hospital
5. Number of medications

---


## Skills Demonstrated
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn`
`Scikit-learn` `Random Forest` `Logistic Regression`
`Feature Importance` `ROC-AUC` `Tableau` `Power BI`
`DAX` `Healthcare Analytics` `Clinical Data`
`Machine Learning` `Data Storytelling`

---

## Author
**Varshini Karuppusamy**
MS Engineering Management - Northeastern University '26
karuppusamy.v@northeastern.edu
[LinkedIn](https://www.linkedin.com/in/kvarshini17/)


---


## Data Attribution
Strack, B., DeShazo, J.P., Gennings, C. et al.
Impact of HbA1c Measurement on Hospital Readmission
Rates: Analysis of 70,000 Clinical Database Patient
Records. BioMed Research International, 2014.
