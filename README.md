# US Health Insurance Data Analysis

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [References](#references)

### Project Objective: 

To study the risk of underwriting in health insurance, examining the interplay of various attributes of the insured and their impact on the insurance premium.

### Data Sources:

The dataset used was "health_insurance.csv", which contains 1338 rows of insured data, where the Insurance charges are given against the following attributes of the insured: Age, Sex, BMI, Number of Children, Smoker, and Region. There are no missing or undefined values in the dataset.

### Tools Used:

- Jupyter Notebook-Python 

### Exploratory Data Analysis: 

The dataset was checked for duplicates and null values and then underwent exploratory data analysis in Python to uncover initial patterns and insights on charges for the attributes- Age, Sex, BMI, Number of Children, Smoker, and Region.
   
### Findings:

The analysis findings can be summarised as follows:
-  Region: The southeast has the highest average charges among all regions. While the Northeast and Northwest have similar counts of insured individuals, the charges in the Northeast are higher.
-  Smoking Status: Smokers have significantly higher premium charges compared to non-smokers.
-  BMI and Age: Both BMI and age show a positive correlation with premium charges; as either BMI or age increases, so do the premium charges.
-  Gender: Males pay higher premiums than females, possibly due to a higher prevalence of smoking among males.
-  Number of Children: Individuals with 2 or 3 children pay a higher average premium than those with fewer or more children.

This analysis provides a comprehensive overview of how different attributes influence health insurance premiums, which can inform risk assessment and underwriting decisions in the health insurance industry.

### References:

1. Kaggle-[US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset/data)
2.  Analyst builder
