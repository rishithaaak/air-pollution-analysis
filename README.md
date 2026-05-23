# Global Air Pollution Exposure Trends Among High-Income Countries

This project presents a longitudinal statistical analysis tracking ambient PM2.5 air pollution exposure levels across 36 high-income countries from 1990 to 2023. By evaluating historical environmental tracking metrics, the study measures global percentage changes, isolates regional variances, and examines how stable air quality improvements are across different macroeconomic cohorts.

* **Full Research Paper:** [Air Pollution Levels Among High-Income Countries (PDF)](reports/Air_Pollution_Levels_Among_High-Income_Countries.pdf)
* **Data Sources:** Core metrics derived from the State of Global Air Database (covering 1990–2023 tracking intervals).


## Technical Stack
* **Analysis & Report Suite:** Microsoft Excel, RealStats Data Analysis Toolpack
* **Methodologies:** Descriptive Statistics, Two-Sample Paired t-Tests, Single-Factor ANOVA, F-Tests for Variance


## Key Statistical Findings

### 1. Global Decoupling and Downward Trends
The dataset tracks a widespread reduction in ambient particulate matter concentrations over the 33-year period:
* **The Drop:** Out of the 36 high-income nations evaluated, 35 successfully lowered their average PM2.5 exposure levels. 
* **The Metrics:** The sample population exhibited a mean reduction of -38.36% and a median drop of -42.86%.
* **The Outlier:** The Republic of Korea was the only nation in the cohort that experienced a net increase in mean exposure over the timeline (+0.43%).

### 2. Regional Variance and Macro Cohorts (ANOVA)
Using a Single-Factor ANOVA test, we evaluated whether regional grouping influenced total PM2.5 exposure levels:
* **The Result:** The test yielded a statistically significant result ($p \approx 0.0039$), confirming that geographic and structural differences override high-income economic commonalities.
* **Middle East vs. North America:** The Middle East cohort exhibited the highest overall PM2.5 exposure alongside the highest year-to-year variability. Conversely, North America recorded the lowest and most statistically stable exposure baselines.

### 3. Pre- vs. Post-2000 Structural Shifts (Paired t-Tests)
We executed a two-sample paired t-test comparing the 1990–2000 decade against the 2000–2023 timeline to measure policy effectiveness:
* The analysis proved a statistically significant drop in mean pollution levels during the latter half of the study period, demonstrating the measurable impact of compounding international emissions standards and cleaner energy transitions.
