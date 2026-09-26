<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0F3460,1A3A6B,00B4D8&height=200&section=header&text=Ubaid%20ur%20Rehman&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Bachelor%20%C3%97%20Data%20Analysis%20%C3%97%20Google%20Certified&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

</div>

<p align="center">
  <a href="https://www.linkedin.com/in/ubaid-ur-rehman-chemist">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://wa.me/923228239798">
    <img src="https://img.shields.io/badge/WhatsApp-Chat-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
  </a>
  <a href="https://orcid.org/0009-0007-8152-5843">
    <img src="https://img.shields.io/badge/ORCID-Research-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/>
  </a>
  <a href="https://www.kaggle.com/ubaidurrehmanthaheem">
    <img src="https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  </a>
</p>

---

## About Me

I'm **Ubaid Ur Rahman**, a final-year BS Chemistry student (CGPA 3.84/4.0) and a **Google Certified Data Analyst**.

My background in analytical chemistry means I work with real, precise, and often messy data every day — spectroscopic readings, calibration curves, quality control measurements. I apply that same precision mindset to **SQL, Excel, Power BI, and Chemometrics** to clean data, find patterns, and turn numbers into clear answers.

> *"A spec sheet and a dataset aren't that different when you're looking for what's off."*

---

## Skills

| Category | Tools & Methods |
|---|---|
| 🗄️ Database & Query | SQL · SQLite |
| 📊 Spreadsheet Analysis | Excel, Google sheets |
| 📈 Visualisation | Power BI |
| 🔬 Chemometrics | PLS Regression · OLS Regression · Calibration Curves · LOD/LOQ · VIP Scores |
| 🐍 Programming | Python · pandas · scikit-learn *(beginner)* |
| 🧪 Domain Knowledge | Analytical Chemistry · UV-Vis Spectroscopy · Statistical QC |

---

## Projects
---
 
## 🚀 Featured Projects
 
---
 
### 1.📊 E-Commerce Profitability & Operational Efficiency Audit
 
> *Business Intelligence · Excel Dashboarding · Data Storytelling*
 
A structured BI audit of a 60-month, 138K-order e-commerce dataset answering **26 business questions** for CO & CFO level decision-making. Built a 10-sheet dark-theme Excel dashboard with 13 charts covering products, revenue, customers, acquisition channels, returns, and seasonal patterns.
 
**Key Findings Uncovered:**
- 🔴 Heavy discounts (>20%) destroy **21.5 percentage points** of profit margin — $15.8M lost per period
- 🔴 Late delivery triggers a **22.83% return rate** vs 0% for on-time delivery
- 💡 North region has the **highest CLV ($9,300+) and margin (48%)** but is severely underinvested
- 💡 All top-10 profit customers are **'Loyal' type** — loyalty programme = highest LTV multiplier
  
| Deliverable | Description |
|---|---|
| [📊 `olivedd_dashboard.xlsx`](https://github.com/ur-chemist/E-Commerce-Profitability-Operational-Efficiency-Audit/blob/main/analysed_results.xlsx) | 10-sheet dark-theme BI dashboard · 13 charts · AutoFilter |
| [📄 `olivedd_bi_report.docx`](https://github.com/ur-chemist/E-Commerce-Profitability-Operational-Efficiency-Audit/blob/main/insights/olivedd_bi_report.docx) | 26 Q&A answers · executive findings · strategic recommendations |
 ---
### Dashboard 

> 📸 *First-Page*
> ![](https://github.com/ur-chemist/E-Commerce-Profitability-Operational-Efficiency-Audit/blob/main/insights/Dashboard.png)
 ---
[![Repo](https://img.shields.io/badge/View_Repo-0F3460?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ur-chemist/E-Commerce-Profitability-Operational-Efficiency-Audit)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle_Dataset-20BEFF?style=flat-square&logo=kaggle&logoColor=white)
 ----
## 2. 🌿 UV-Vis Pesticide Detection — Chemometric Data Analysis

**Repository:** [uv-vis-pesticide-chemometrics](https://github.com/ur-chemist/uv-vis-pesticide-chemometrics)
**Dataset DOI:** [10.5281/zenodo.21911163](https://doi.org/10.5281/zenodo.21911163)

### Project Summary

Analysed 846 UV-Vis spectra (200–737.5 nm) collected from complex environmental
water samples to detect and quantify four pesticide analytes. The project compared
univariate (Beer-Lambert) and multivariate (PLS, PLS+SNV) methods to understand
which approach handles real-world matrix interference better.

This is a negative-result study — one analyte was confirmed undetectable due to
dissolved organic matter (DOM) interference. That finding is the result, and it
matters as much as a positive one.

### The Problem

Standard univariate calibration fails when multiple compounds overlap in the same
spectral region. The question was: can PLS regression recover individual analyte
signals from a complex, overlapping mixture?

### What I Did

- Loaded and cleaned 846 spectra — removed NaN columns, sorted by analyte concentration
- Built calibration curves for all 4 analytes using LINEST (Excel) and Beer-Lambert law
- Calculated LOD and LOQ for each analyte
- Built a selectivity table using CORREL across 5 key wavelengths
- Ran PLS and PLS+SNV models with 5-fold cross-validation, 10 components
- Analysed VIP scores to identify which wavelength regions actually contribute

### Results

| Analyte | Univariate R²cv | PLS R²cv | PLS+SNV R²cv |
|---|---|---|---|
| Fluopyram | −0.004 | 0.41 | **0.597** |
| Bromide | 0.31 | 0.58 | **0.627** |
| Diflufenican | ~0.00 | ~0.00 | ~0.002 |


**Key Finding:** Diflufenican is undetectable across all models — DOM matrix
interference confirmed. VIP scores show only 202–300 nm contributes meaningfully
to the Fluopyram model.

### Skills Demonstrated

- Multivariate Data Analysis (PLS · PLS+SNV)
- Spectral Data Cleaning & Preprocessing
- Calibration Curve Construction (LINEST)
- LOD / LOQ Calculation
- Cross-Validation & Model Evaluation
- Scientific Data Reporting (honest negative results)
- Excel Advanced Functions
- Python (pandas · scikit-learn)

### Tools

`Excel` `Python` `pandas` `scikit-learn` `Zenodo` `UV-Vis Spectral Data`

### Screenshots

> 📸 *Calibration curves*
> ![Calibration Curves](https://github.com/ur-chemist/uv-vis-pesticide-chemometrics/blob/main/images/Calibaration_Curve.png)

> 📸 *PCA SCORE*
> ![PCA-score](https://github.com/ur-chemist/uv-vis-pesticide-chemometrics/blob/main/images/FINAL_fig7_PCA.png)

> 📸 *VIP scores plot*
> ![VIP Scores](https://github.com/ur-chemist/uv-vis-pesticide-chemometrics/blob/main/images/FINAL_fig3_VIP.png)

---

## 3. 🍷 Wine Quality — Data Analysis & Classification

**Repository:** [wine-quality-chemometrics](https://github.com/ur-chemist/wine-quality-chemometrics)

### Project Summary

Analysed 1,599 red wine samples from the UCI Wine Quality dataset to identify
which chemical properties drive quality scores. Built a regression model, a
classification pipeline, and a SQL database to store and query predictions.

### The Problem

Can measurable physicochemical properties — acidity, alcohol, sulphates — predict
wine quality reliably? And which features matter most?

### What I Did

- Loaded and explored 1,599 rows × 11 chemical features
- Analysed distributions, outliers, and feature correlations
- Built an OLS regression model to quantify each feature's impact on quality
- Classified wines as good (quality ≥ 7) vs average using Random Forest
- Stored all predictions in a SQLite database
- Wrote SQL queries to filter, sort, and summarise results by quality tier

### Results

| Method | Result |
|---|---|
| OLS Regression R² | 0.32 |
| Random Forest Accuracy | ~78% on test set |
| Strongest positive driver | Alcohol content |
| Strongest negative driver | Volatile acidity |

**Honest note:** R² of 0.32 reflects that wine quality ratings are partly
subjective human scores — not a flaw in the analysis. The value here is in
the data pipeline, SQL workflow, and feature interpretation.

### Skills Demonstrated

- Exploratory Data Analysis (EDA)
- OLS Regression & Feature Significance (p-values)
- Random Forest Classification
- SQL Database Design & Querying (SQLite)
- Data Cleaning with pandas
- Jupyter Notebook Documentation

### Tools

`Python` `pandas` `scikit-learn` `statsmodels` `SQLite` `SQL` `Jupyter` `Excel`

### Screenshots

> 📸 *Feature correlation heatmap*
> ![Correlation Heatmap](https://github.com/ur-chemist/wine-quality-chemometrics/blob/main/Regression%20summary%20output%20(1).png)

> 📸 *Regression results summary*
> ![Regression Results](https://github.com/ur-chemist/wine-quality-chemometrics/blob/main/Regression%20summary%20output%20(2).png)

> 📸 *Random Forest feature importance — add your screenshot here*
> ![Feature Importance](screenshots/wine_feature_importance.png)


## Certifications

| Certificate | Issuer | Completed | Verify |
|---|---|---|---|
| Google Data Analytics Professional | Google / Coursera | Dec 1, 2025 | [Verify](https://coursera.org/verify/professional-cert/98TNBN2M2XU6) |
| Google IT Support | Google / Coursera | 2025 | [verify](https://coursera.org/share/623d73057fa984be82c963f0b936020e) |

---

## Contact

I am open to **remote Data Analyst roles and freelance projects**.

| Platform | Link |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/ubaid-ur-rehman-chemist](https://www.linkedin.com/in/ubaid-ur-rehman-chemist) |
| 💬 WhatsApp | [+92 322 823 9798](https://wa.me/923228239798) |
| 🔬 ORCID | [0009-0007-8152-5843](https://orcid.org/0009-0007-8152-5843) |
| 🎯 Kaggle | [ubaidurrehmanthaheem](https://www.kaggle.com/ubaidurrehmanthaheem) |

<p align="center">Made from Bahawalnagar, Pakistan 🇵🇰</p>
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00B4D8&center=true&vCenter=true&width=650&lines=Final-Year+BS+Chemistry+%E2%80%94+CGPA+3.84%2F4.0;Data+Analysis+%7C+Chemometrics+%7C+BI+Dashboards;Python+%7C+SQL+%7C+Excel+%7C+Power+BI;CM+Honhaar+Scholar)](https://git.io/typing-svg)

</div>
