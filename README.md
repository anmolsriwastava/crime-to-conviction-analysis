# Crime to Conviction Analysis

**Data Analysis & Research Project**

## Overview

This project analyzes the journey from crime reporting to final conviction using real-world criminal justice data. The focus is on understanding patterns, bottlenecks, and factors that influence conviction rates, case durations, and justice delivery efficiency.

## Questions We Will Explore

## Questions We Will Explore

### 1. Which categories of crime contribute the largest share of convicted prisoners in India?

1.1 How has the relative contribution of violent offences against the human body versus property offences to total state‑level convictions changed from 2019 to 2023? Are we imprisoning more people for violent acts or for property disputes over time?

1.2 Is there a correlation between a state's conviction rate for Murder and its conviction rate for Theft? (Do states with high rates of violent death also experience high rates of petty property crime, or are they inversely related?)

1.3 While murder gets headlines, which state shows the highest Compound Annual Growth Rate (CAGR) in Criminal Breach of Trust (Col. 17) and Cheating (Col. 18) convictions combined from 2019 to 2023?

1.4 Has the ratio of Burglary (Col. 20) to Theft (Col. 12) convictions inverted in any state between 2019 and 2023? (i.e., Did Burglary drop significantly while Theft rose, or vice versa?)

1.5 Within a state, how does the proportion of Life Imprisonment Eligible Crimes (Murder + Rape + Dacoity) to Total Convicts differ from the national average?

### 2. Do states exhibit distinct “crime profiles” based on the composition of convictions?

2.1 Using a simple ratio metric, can we classify states on a spectrum from "Violence-Dominant" to "Property-Dominant" prisons? How has Uttar Pradesh's position on this spectrum shifted from 2019 to 2023 compared to Tamil Nadu?

2.2 How many states changed their rank position in the Murder Conviction Count (Col. 3) by more than 3 places between 2019 and 2023? Is the "Murder Capital" list rigid or fluid?

2.3 Which states have an unusually low ratio of Attempt to Murder (Col. 6) to Murder (Col. 3) compared to their regional neighbors?

2.4 Group states into Low, Medium, and High tertiles based on their 5‑year average Kidnapping & Abduction (Col. 7) convictions. Now, within the Medium tertile, calculate the Coefficient of Variation (CV) of the annual totals. Which states in the Medium tertile show High Volatility (CV > 0.5)?

2.5 For each state, calculate the 5-year correlation (Pearson's r) between Robbery (Col. 14) and Burglary (Col. 20). Which states exhibit a strong negative correlation (r < -0.7)?

### 3. How significant are crimes against women within the overall prison population?

3.1 How has the composition of "Crimes Against Women" convictions changed between 2019 and 2023? Specifically, has the proportion of Rape (Col. 8) convictions increased relative to Cruelty by Husband (Col. 23)?

3.2 Using a Simple Linear Regression, can we predict the number of Dowry Death (Col. 5) convictions in a state based on the number of Cruelty by Husband (Col. 23) convictions?

3.3 In which states does the number of Dowry Death (Col. 5) convictions exceed or equal the number of Cruelty by Husband (Col. 23) convictions? (i.e., Ratio >= 1.0)

3.4 Has the geographic concentration of Cruelty by Husband (Col. 23) convictions changed between 2019 and 2023? Specifically, calculate the share of the Top 3 states in total national convictions for this crime in 2019 and again in 2023.

3.5 Within each state, calculate the Pearson correlation coefficient across the 5 years (2019‑2023) between Rape (Col. 8) convictions and Assault on Women (Col. 9) convictions. Which states show a strong positive correlation (r > 0.7), and which show no correlation (r between -0.2 and +0.2)?

### 4. Are crime conviction patterns stable over time?

4.1 Did the national rank order of states in terms of Total Convicts (Col. 28) remain stable from 2019 to 2023? Measure the rank mobility of the top 10 and bottom 10 states.

4.2 Which specific crime category showed the most consistent year-over-year trend (steady increase or decrease) at the All-India level from 2019 to 2023?

4.3 Did the ratio of Attempt to Murder (Col. 6) to Actual Murder (Col. 3) change significantly in any state between 2019-2020 and 2021-2023?

4.4 Did the All-India proportion of Rape (Col. 8) within the Total Crimes Against Women (Col. 26) change monotonically (steadily in one direction) between 2019 and 2023?

4.5 Track the 5-year trend in Arson (Col. 19) convictions. Has this crime vanished from the conviction records of certain states?

### 5. Are there “outlier states” that show unusually high conviction numbers for specific crimes?

5.1 Which state has the most imbalanced ratio of Rape Convictions (Col. 8) to Assault on Women (Col. 9)?

5.2 Examine the Preparatory Offences: Prep. and Assembly for Dacoity (Col. 16). Which states have a zero count for this charge despite having high Actual Dacoity (Col. 15) counts?

5.3 Which state shows a consistent, sharp decline (>50% drop) in Riots (Col. 11) convictions from 2019 to 2023? Is this Peace or Impunity?

5.4 For each state, calculate two metrics: (1) Average Annual Growth Rate (CAGR) of Total Convicts (Col. 28) from 2019‑2023 and (2) Coefficient of Variation (CV) of the annual Total Convicts. Which states fall into the "High Growth, High Volatility" quadrant?

5.5 Consider the crime Counterfeiting (Col. 22). Identify all states that reported at least one conviction for counterfeiting in all five years (2019‑2023). Among these states, which has the lowest total convictions over the 5‑year period?




## Folder Structure
- `data/raw/` → Original CSV files (never edit)
- `data/processed/` → Cleaned and merged datasets
- `notebooks/` → All analysis notebooks (one folder per question)
- `reports/` → Final figures and tables

## How to Run
1. Clone the repo
2. `pip install -r requirements.txt`
3. Then open your respective question notebook

## Data Source

