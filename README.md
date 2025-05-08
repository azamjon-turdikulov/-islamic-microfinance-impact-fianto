# Islamic Microfinance Impact – Policy Evaluation in Indonesia

This project evaluates the role of Islamic Microfinance Institutions (MFIs) in improving household welfare, based on Fianto (2017). Using a simulated dataset in STATA, I replicate key methods from the paper, including Propensity Score Matching (PSM), Difference-in-Differences (DiD), and Logit analysis.

## 📌 Project Overview
- **Country focus:** Indonesia  
- **Policy area:** Financial inclusion, Islamic finance  
- **Key paper:** Fianto, B. A. (2017)  
- **Tools used:** STATA, R (for graphs)

## 📈 Methods Applied
- Simulated 200-household dataset (age, income, education, treatment status)
- Estimated treatment effects using:
  - Propensity Score Matching (`psmatch2`)
  - Difference-in-Differences regression
  - Logit model for participation determinants
- Visuals and tables created in R Studio

## 📂 Files Included
- `stata_commands.txt` — STATA commands used to simulate data and run analysis  
- `dataset_simulated.dta` — Simulated dataset (200 observations)  
- `simulated_data_description.txt` — Brief explanation of how data was generated  

## 📚 Context
This is part of my MSc Development Economics coursework at the University of Birmingham. The analysis critically reflects on real-world challenges of causal inference, external validity, and policy trade-offs in Islamic financial inclusion.

*Note: The dataset used is simulated and does not reflect real household data.*
