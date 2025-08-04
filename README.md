# Covid-project
# Socioeconomic Factors that Affected COVID-19 Mortality in England

This repository contains the data analysis project, investigating the **socioeconomic and demographic variables that influenced COVID-19-related deaths in England** during the 2020 pandemic. The study employs statistical modeling and data visualization to uncover how factors such as **age, gender, education level, health status, deprivation levels, and housing conditions** contributed to mortality patterns across English local authority districts.

## 📄 Project Overview

**Author:** Iyeose Simon Uhumuvabi  
**Module:** DS7006  
**Institution:** [University of East London]

### 🧠 Objective
To identify the most significant socioeconomic and demographic determinants of COVID-19 mortality in England by analyzing data from multiple sources and applying statistical methods such as regression modeling, correlation testing, PCA, and data normalization.

---

## 📊 Key Research Questions

- How do age, gender, and education levels impact COVID-19 outcomes?
- What role do pre-existing health conditions play in mortality?
- How are housing and deprivation levels correlated with death rates?
- What public health insights can be drawn from these findings?

---

## 🧪 Methodology

### Data Sources:
- **COVID-19 Deaths:** Provided by the course module (based on 2018 LA codes).
- **Socioeconomic Data:** Extracted from the [Nomis](https://www.nomisweb.co.uk/) website, based on the 2011 UK census.
- **Local Authority Code Mapping:** Handled changes in LA boundaries from 2018 to 2023 using official records from GOV.UK.

### Tools Used:
- **R (via RStudio)** for data modeling and visualization
- **SQLite** for preprocessing and merging datasets
- **Excel** for initial data cleaning
- **ggplot2**, `psych`, and `car` packages for EDA and modeling

### Statistical Techniques:
- Normalization per 1000 residents
- Shapiro-Wilk and Kolmogorov–Smirnov tests
- Spearman’s rank correlation
- Principal Component Analysis (PCA)
- Multiple Linear Regression
- Variance Inflation Factor (VIF) for multicollinearity

---

## 🔍 Key Findings

- Areas with **no deprivation** experienced significantly fewer deaths.
- High deprivation levels and **poor living conditions** were strongly associated with increased mortality.
- **Educational attainment** and **health status** also contributed meaningfully, although not all variables remained significant in the final regression model.

---

## 📁 Repository Structure
 covid19-socioeconomic-analysis/
│
├── 📁 data/
│ ├── COVID_19_deaths.csv
│ ├── Age_band.csv
│ ├── Gender.csv
│ ├── Deprivation.csv
│ ├── Qualification_level.csv
│ └── Accommodation_type.csv
│
├── 📁 scripts/
│ ├── data_cleaning.sql
│ ├── data_merge.sql
│ └── analysis_final.R
│
├── 📁 outputs/
│ ├── final_dataset.csv
│ ├── pca_results.png
│ └── regression_output.txt
│
├── README.md
└── LICENSE


---

## 📝 Conclusion

The analysis provides strong evidence that COVID-19 mortality in England was heavily influenced by structural inequalities. Policymakers and health officials should prioritize interventions in deprived areas, especially where housing conditions and educational opportunities are limited.

This project showcases how integrated data science techniques can provide meaningful insights into public health crises and support more inclusive and effective responses in the future.

---

## 📚 References

Key references include studies from **WHO**, **ONS**, **Public Health England**, and peer-reviewed research on the impact of **socioeconomic disparities** during COVID-19. Full citations are available in the [report](https://github.com/Iyeose/Covid-project/blob/main/COVID-19%20Death%20analysis.pdf).

---

## 🤝 Acknowledgments

Thanks to the DS7006 module instructors and [Nomis](https://www.nomisweb.co.uk/) for the data resources.

---

## 📬 Contact

For any questions or feedback, feel free to open an issue or reach out via GitHub.

