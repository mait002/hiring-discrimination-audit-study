# Hiring Discrimination Audit Study

This project analyzes name-based discrimination in hiring using resume audit data from the famous Bertrand & Mullainathan (2004) study. It explores whether applicants with Non-Anglophone (minority-sounding) names are less likely to receive callbacks, even when qualifications are equal.

## 🧠 Research Question
Are immigrants with Non-Anglophone names less likely to receive callbacks compared to those with Anglophone names?

## 📊 Dataset
- **Source**: Bertrand & Mullainathan Resume Audit Study (OpenICPSR)
- 4,870 resumes sent to job ads in Boston and Chicago
- Key variables: `firstname`, `race`, `call`, `education`, `experience`, resume features

## 🔍 Methodology
- Logistic regression using Python (`statsmodels`)
- Visualization in Tableau
- Callback rates analyzed by race, name type, and resume strength

## 🧪 Key Finding
Applicants with Anglophone names were **~55% more likely** to receive callbacks compared to Non-Anglophone names, controlling for resume quality and experience.

## 📁 Files
- `cleaned_resume_audit_data.csv` — cleaned dataset used in analysis
- `hiring_bias_analysis.ipynb` — full Python notebook
- `dashboard/` — Tableau dashboard screenshots

## 📈 Tableau Dashboard
📎 [Link to interactive dashboard](#) *(optional if published on Tableau Public)*

## 🔧 Requirements
```bash
pandas
statsmodels
matplotlib
scipy

