# Hong Kong Corruption & Security Analysis

## Introduction

This project analyses the relationship between perceived corruption, public security behaviour, and trust in institutions using survey data from Hong Kong.

The analysis focuses on identifying how corruption perception influences precautionary behaviour and how demographic characteristics affect perceptions of corruption, security, and confidence in the police.

The project applies statistical modelling techniques to support data-driven understanding of public attitudes, perceived risk, and behavioural responses associated with corruption and security concerns. :contentReference[oaicite:0]{index=0}

---

# Dataset

The project uses survey data from the World Values Survey (Hong Kong).

- Dataset source:  
https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp

- Dataset coverage:
  - Hong Kong
  - ~2000 observations
  - Data collected between July 2018 and November 2018

---

# Project Objectives

The analysis investigates:

1. Whether perceived corruption influences security-related behaviour  
2. Whether demographic characteristics influence corruption perception and perceived security  
3. Whether confidence in the police moderates the relationship between corruption perception and security behaviour  
4. Whether there is an association between age and confidence in the police  

---

# Analytical Approach

The project applies several statistical modelling techniques:

- Binary Logistic Regression
- Multiple Linear Regression
- Moderation Analysis

The analysis was conducted using R and regression-based statistical modelling techniques. :contentReference[oaicite:1]{index=1}

---

# Variables Used

Key variables included:

- Perception of corruption
- Security-related behaviour
- Confidence in the police
- Age
- Sex
- Immigration status

The target behavioural indicator focused on whether respondents avoided carrying large amounts of money due to security concerns.

---

# Project Structure

```text
hk-corruption-security-analysis/
│
├── data/
│   └── world_values_survey_hk.csv
│
├── notebooks/
│   └── corruption_security_analysis.Rmd
│
├── report/
│   └── corruption-security-analysis_regression.pdf
│
├── images/
│   ├── regression_results.png
│   └── model_summary.png
│
└── README.md
```

---

# Key Findings

## Corruption Perception & Security Behaviour

Higher perceived corruption was associated with increased likelihood of precautionary security behaviour.

A one-unit increase in perceived corruption increased the odds of avoiding carrying large amounts of money due to security concerns by approximately 10%. :contentReference[oaicite:2]{index=2}

---

## Demographic Factors

The analysis identified several demographic patterns:

- Younger individuals tended to perceive corruption as higher
- Non-immigrants perceived corruption as higher than immigrants
- Female respondents were more likely to engage in precautionary security behaviour

---

## Confidence in the Police

The moderation analysis found no statistically significant interaction effect between corruption perception and confidence in the police.

This suggests that confidence in law enforcement did not significantly alter the relationship between perceived corruption and security behaviour. :contentReference[oaicite:3]{index=3}

---

# Regression Results

## Model Summary

<p align="center">
  <img src="./images/model_summary.png" width="700">
</p>

---

# Business & Policy Relevance

The findings demonstrate how perceived corruption can influence public behaviour and perceived security, even in relatively low-corruption environments.

The analysis highlights how statistical modelling can support:
- risk perception analysis
- public policy evaluation
- behavioural analytics
- crime and security research
- evidence-based decision making

The results also suggest potential value in public communication and anti-corruption awareness campaigns aimed at improving perceived institutional trust and public security confidence.

---

# Tools & Libraries

- R
- Regression Analysis
- Statistical Modelling
- World Values Survey Data

---

# Key Outcomes

- Applied regression modelling to behavioural and perception-based survey data
- Conducted binary logistic regression, multiple linear regression, and moderation analysis
- Identified significant associations between corruption perception and security behaviour
- Evaluated demographic influences on corruption perception and institutional trust
- Produced data-driven policy and behavioural insights

---

# Future Improvements

Potential future extensions include:
- additional demographic segmentation
- longitudinal analysis across countries
- advanced causal modelling
- interaction effects with additional institutional trust variables
- visual analytics dashboards
