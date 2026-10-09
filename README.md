# Healthcare Analytics for Doctor Visits

> **DIY Project — Data Analytics Internship**  
> Under **Edunet Foundation** in collaboration with **Vodafone Idea Foundation (Vi)** as part of the **TIRTC (Telecom Innovation Research Training Centre)** Program

---

## 📁 Repository Structure

```
├── Healthcare_Analytics_for_Doctor_Visits.csv
├── Healthcare_Analytics_for_Doctor_Visits.ipynb
└── Healthcare_Analytics_for_Doctor_Visits_DIY_Project.pptx
```

---

## 📌 Problem Statements

This project addresses three connected problem statements that together answer one larger question —
**"What factors drive a patient to visit the doctor more frequently?"**

### PS1 — Illness and Chronic Conditions
> How does a patient's illness count and chronic condition affect the number of doctor visits?

### PS2 — Income and Insurance
> How does income level and insurance type influence a patient's access to healthcare?

### PS3 — Gender and Reduced Activity
> How do gender and reduced activity days relate to the frequency of doctor visits?

---

## 🎯 Objectives

- Analyze the distribution of patients based on illness count and identify which group visits doctors most
- Understand the relationship between chronic conditions and frequency of hospital visits
- Explore how income level and government/private insurance affects healthcare access
- Compare doctor visit frequency between male and female patients
- Find out how reduced activity days correlate with number of doctor visits
- Visualize key patterns using charts, heatmaps, scatter plots and pie charts

---

## 📊 Dataset — Healthcare Analytics for Doctor Visits

| Property | Details |
|---|---|
| File Name | Healthcare_Analytics_for_Doctor_Visits.csv |
| Total Records | 5190 rows |
| Total Columns | 13 columns |

### Columns Description

| Column | Description |
|---|---|
| visits | Number of doctor visits |
| gender | Gender of the patient (male/female) |
| age | Age of the patient |
| income | Income level of the patient |
| illness | Number of illnesses the patient has |
| reduced | Number of days of reduced activity due to illness |
| health | General health score |
| private | Whether the patient has private health insurance (yes/no) |
| freepoor | Govt insurance due to low income (yes/no) |
| freerepat | Govt insurance due to old age or disability (yes/no) |
| nchronic | Whether patient has a non-chronic condition (yes/no) |
| lchronic | Whether patient has a long-term chronic condition (yes/no) |

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** — Data loading, filtering, groupby operations
- **Matplotlib** — Bar charts, scatter plots, pie charts, boxplots
- **Seaborn** — Heatmaps, histplots, lineplot, correlation matrix
- **Jupyter Notebook** — Development environment

---

## 📈 Key Findings

**PS1:** Patients with 1 illness are the highest in count (1638). Chronic patients visit the doctor significantly more than non-chronic patients.

**PS2:** Low income patients with government insurance visit the doctor more frequently. Private insurance holders also show higher visit rates due to better healthcare access.

**PS3:** Females visit the doctor slightly more than males. Patients with more reduced activity days tend to visit the doctor more frequently.

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
1. Upload the `.ipynb` file to [Google Colab](https://colab.research.google.com)
2. Upload the `.csv` file when prompted
3. Run all cells — `Runtime → Run All`

### Option 2 — Jupyter Notebook (Local)
1. Clone this repository
2. Place the `.csv` file in the same folder as the `.ipynb` file
3. Open Jupyter Notebook and run all cells

---

## 🏢 About the Program

This project was completed as part of the **DIY Project** under the **TICT (Technology Internship and Career Training)** program.

| Organization | Role |
|---|---|
| **Edunet Foundation** | Program Coordinator |
| **Vodafone Idea Foundation (Vi)** | Industry Partner |
| **VOIS for Tech** | Internship Platform |

---

## 👤 Author

**Chirag Chavda**  
Data Analytics Intern — VOIS for Tech  
Edunet Foundation × Vodafone Idea Foundation
