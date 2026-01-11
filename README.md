# Census Data Analysis & Policy Recommendation

This project was completed as part of the **MSc Artificial Intelligence and Data Science** programme.  
It analyses a mock UK census dataset to identify demographic trends and support **data-driven infrastructure and public investment decisions**.

---

## Project Overview

Local governments rely on census data to plan infrastructure, allocate funding, and anticipate future needs.  
In this project, a simulated 2025 census dataset for an imaginary UK town is analysed to:

- Clean and preprocess real-world style census data  
- Explore demographic, employment, and household patterns  
- Support evidence-based policy recommendations  

The dataset contains missing values, inconsistent entries, and free-text fields, reflecting real census challenges.

---

## Objectives

- Clean and standardise demographic and household data  
- Engineer household-level and employment-status features  
- Perform exploratory data analysis (EDA) using visualisations  
- Identify trends relevant to housing, transport, and public services  
- Provide data-driven recommendations for local government planning  

---

## Data Preparation & Feature Engineering

Key preprocessing steps included:

- Standardising **age**, **gender**, **marital status**, and **religion** fields  
- Creating a **household identifier** to analyse occupancy and household size  
- Handling missing and invalid values using rule-based logic  
- Engineering an **employment status** variable from occupation and age  
- Separating school students and university students for commuting analysis  

---

## Exploratory Data Analysis

The analysis focused on:

- **Age structure** and population pyramid  
- **Employment status** across age groups  
- **Household occupancy categories**  
- **Marital status composition**  
- **Religion distribution**  
- **Infirmity reporting**

Visualisations were created to clearly communicate demographic trends and support interpretation.

---

## Key Insights

- The town has a **predominantly working-age population**, concentrated between ages 20–49  
- A **large student population**, including university students, indicates high commuting demand  
- Household structures are mainly **single-person, two-person, and small families**  
- No strong evidence suggests urgent demand for new religious or emergency medical facilities  
- Transport connectivity and education capacity emerge as key priorities  

---

## Recommendations

Based on the analysis, the data supports:

- **Investment in transport infrastructure** (e.g. a train station) to support commuters  
- **Increased spending on education**, driven by a large and growing population of children and students  

These recommendations align with both current demographic needs and future population trends.

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

---

## Repository Contents
- `Census_report.ipynb` – Data cleaning, analysis, and visualisation notebook

## Notes
This project demonstrates end-to-end data analysis and data-driven decision making.

