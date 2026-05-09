# Bank-Risk-Analysis (English version)
Statistical analysis and quadratic modeling of operational risks and fraud density in banking systems using Python. Proved the non-linear acceleration of risks during peak operational loads.
##  Project Overview
This project focuses on identifying the root causes of operational risks and analyzing fraud patterns within a banking environment. The primary goal was to determine how operational errors and transaction volumes impact the overall risk score using statistical modeling.

## Key Findings
* **Quadratic Risk Growth:** The analysis revealed a non-linear relationship between operational errors and risk. As errors exceed a specific threshold (approx. 30 errors/day), the risk score increases quadratically ($0.19x^2$), leading to a "snowball effect."
* **Fraud Density Impact:** Fraud density was identified as the most significant predictor of risk, with a high positive correlation.
* **Peak Load Vulnerability:** Using stress-test visualization, I identified that system risks accelerate significantly during high-transaction periods (f.ex. holidays), suggesting a need for dynamic resource allocation.

##  Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels
* **Methodology:** Weighted Least Squares (WLS) Regression, Quadratic Transformation, Root Cause Analysis (RCA).

##  Insights for Management
Based on the results, the model suggests that banks should focus on **process integrity** rather than just financial loss mitigation. Specifically, preventing the accumulation of small operational errors can prevent exponential systemic failures.


# Bank operatsion risklarini modellashtirish (Uzbek version)

Ushbu loyiha bank tranzaksiyalaridagi operatsion xatolarning umumiy risk darajasiga ta'sirini tahlil qiladi.

## Asosiy hulosalar:
- Operatsion xatolar va risk darajasi o'rtasida **kvadratik bog'liqlik** aniqlandi.
- Xatolar soni 30 tadan oshganda risk 'snowball' effekti bilan tezlashadi.

## Ishlatilgan metodlar:
- **Python** (Pandas, Matplotlib, Statsmodels)
- **Modellashtirish:** WLS (Weighted Least Squares) Regression
