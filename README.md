# Healthcare Risk Modeling Case Study: A $23.8k Insight Analysis

## Project Goal: 
- Accurate cost prediction is critical for insurance underwriting profitability. I analyzed 1,338 records to identify which demographic and lifestyle factors drive medical cost differences to inform risk-based pricing decisions.

## Methodology: 
- **Data Integrity & Prep:** Conducted data validation and outlier analysis in Python (Pandas), ensuring statistical assumptions were met prior to modeling. Encoded categorical variables to enable regression-based modeling.
- **Statistical Modeling:** Built a Multiple Linear Regression (OLS) model to isolate and quantify each variable’s independent contribution to annual healthcare charges. Achieved an Adjusted R² of 0.75, indicating strong explanatory power.
- **Visual Storytelling:** Developed an interactive Tableau dashboard using parameterized filters and custom calculations to translate abstract statistical coefficients into actionable financial insights.

## Key Finding: 
- **The $23.8k Smoking Impact:** Smoker status is the dominant cost driver, driving an average increase of $23,848 in annual charges, holding age, BMI, and region constant.
- **BMI/Age Scale:** Each additional BMI unit and year of age increases annual charges by approximately $339 and $256, respectively, indicating a steady, linear growth in risk.
- **Conclusion:** Results indicate that lifestyle-based underwriting adjustments would yield significantly greater margin protection than region-based pricing strategies.

## Strategic Business Application:
- **Premium Optimization:** Recommend reallocating underwriting weight toward lifestyle indicators, as smoking and BMI materially outperform geographic variables in explaining cost variance.
- **Targeted Wellness Programs:** Data identifies specific High-Risk clusters where preventative wellness initiatives could yield the highest ROI for the provider.

## Links
- Tableau Dashboard https://drive.google.com/file/d/1s527oyVR_nnCizXhkYwKM997kcTdOcqH/view?usp=share_link
- Python Code https://drive.google.com/file/d/1-PQQUgVOZrWsDapzQuLaMi-blloKJg1U/view?usp=sharing
