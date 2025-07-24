# Diabetes Hospital Encounter Analysis: Medication Usage Trends, Readmission Patterns, and Demographic Insights

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Insights](#insights)

---

## Project Overview
This Excel-based data analysis project explores inpatient encounters involving diabetic patients to uncover patterns across three key areas: medication usage trends, readmission rates by age group, and demographic distributions. The objective was to analyze how frequently specific medications were prescribed and whether their dosages were increased, decreased, or maintained; to examine how readmission rates vary across age groups; and to understand the gender distribution within different age categories.  
In analyzing medication usage, the focus was on the frequency of each drug being marked as "steady," "up," or "down" across all hospital encounters, rather than by patient. Since multiple medications may be administered during a single encounter, the resulting chart reflects medication usage trends across all encounters, offering a broad view of prescribing behaviors over the 10-year period. These insights aim to support clinical decision-making, reveal demographic disparities, and enhance understanding of treatment patterns within diabetic care.

---

## Data Source
**Source**: 10 Years Diabetes Dataset from Kaggle  
**Filename**: diabetes.csv  
**Description**: Contains inpatient data of diabetic patients over a 10-year period (1999–2008) of clinical care at 130 US hospitals.

---

## Tools
Microsoft Excel was the only tool used in this project for:
1. Data cleaning  
2. Data transformation  
3. Pivot table creation  
4. Slicer setup for interactive filtering  
5. Data visualization (bar charts, pivot charts)  
6. Report formatting  

---

## Data Cleaning
I performed the following data preparation steps:
1. Data inspection  
2. Data cleaning and formatting  
3. Converting the data to an Excel Table for dynamic referencing  
4. Creating a new summary table that aggregates usage trends for each drug  

**Note on Rare Medications**:  
The dataset contains two medications: *Examide* and *Citoglipton*, which appear to be placeholders. These drugs were retained in the raw and edited datasets for completeness but were excluded from charts and visual analysis due to their negligible or zero usage. This helps ensure that the visualizations reflect more meaningful and clinically relevant trends.

---

## Exploratory Data Analysis
Some guiding questions for Exploratory Data Analysis included:
1. What is the gender distribution of the patients across age groups?  
2. What are the readmission rates by age group?  
3. What is the overall distribution of medication usage trends (steady, up, down) for each prescribed medication?  
4. Which medications were most frequently administered or had changes in dosage across hospital encounters?

---

## Visualizations

**1. Gender Distribution by Age Group**  
![Gender Distribution by Age Group](./Gender%20by%20Age%20Group.png)

**2. Readmission Rates by Age Group**  
![Readmission by Age Group](./Readmission%20by%20Age%20Group.png)

**3. Medication Usage Trends Across Hospital Encounters**  
![Medication Usage Trends](./Medication%20Usage%20Trends.png)


## Data Analysis

The dataset was analyzed using Excel through pivot tables, formulas, and interactive slicers. Three key visualizations were created to answer core questions. Bar charts were plotted:
1. Showing gender distribution across age groups.  
2. Displaying readmission rates segmented by age group.  
3. Visualizing how often medications were prescribed with dosages increased, decreased, or maintained across hospital encounters.  

Interactive elements like slicers were incorporated to allow dynamic filtering of the medication usage data, enhancing interpretability.

---

## Insights
**Key Insights Drawn from the Analysis**:
1. **Gender Distribution by Age Group**  
   Female patients mostly outnumbered male patients across all age groups, with the 70–80 age range showing the highest female representation. Conversely, younger age groups (e.g 0–10, 10–20) had lower representation overall, which may reflect fewer hospital admissions for diabetes among younger population.

2. **Readmission Rates by Age Group**  
   The 70–80 age group had the highest number of both readmitted and non-readmitted patients, likely due to having the largest total number of encounters.  
   Meanwhile, younger age groups (e.g 0–10, 10–20) showed lower readmission rates, which may reflect both better health outcomes and a smaller number of total patients in those categories — meaning the lower readmission might not solely indicate better care or outcomes.

3. **Medication Usage Trends Across Hospital Encounters**  
   Among the tracked prescribed medications, most drugs were maintained ("steady") during hospital encounters. Only a minority showed dosage increases or decreases.  
   Medications such as *Metformin* and *Insulin* were among the most commonly used, while medications such as *Acetohexamide*, *Glimepiride + Pioglitazone*, etc., were rarely prescribed. *Examide* and *Citoglipton*, which appear to be placeholders, were excluded from visual charts to avoid distorting trends.

---
