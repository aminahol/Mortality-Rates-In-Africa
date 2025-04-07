# Mortality-Rates-In-Africa
## Overview

This analysis leverages exploratory data analysis (EDA) and machine learning clustering techniques to explore the relationship between population, healthcare access, and mortality rates across African countries. The dataset used is sourced from the **UN Population Division Global Health Crises data**.

The goal is to identify patterns and underlying factors influencing mortality trends across the region.

By examining data on causes of death, population demographics, economic indicators, and healthcare access, the analysis uncovers key insights into mortality variations across Africa. Additionally, K-Means clustering was applied to group countries by their mortality profiles. This helped identify high-risk nations and outliers, providing valuable input for targeted health interventions and informed policy decisions to reduce preventable deaths and improve health outcomes across the continent.

![Mortality in Africa](https://github.com/aminahol/Mortality-Rates-In-Africa/blob/4c3ae3844cc164b0ff7440e0f25634cad1ba21b9/images/Mortality%20In%20Africa.png)

![Trend of Top Causes of Mortality](https://github.com/aminahol/Mortality-Rates-In-Africa/blob/4c3ae3844cc164b0ff7440e0f25634cad1ba21b9/images/Trend%20of%20Top%20Causes%20of%20Mortality.png)



## Key Insights & Recommended Actions

### 1. Notable Spike in Mortality in 1994
Data shows a significant increase in deaths in 1994, followed by a steady rise between 2003 and 2005, peaking at approximately 9.3 million deaths.  
Rwanda was identified as the primary outlier in 1994, which aligns with historical events, emphasizing how major crises can heavily impact health outcomes.

### 2. Population and Mortality Correlation: Predominantly Positive, with Some Variations
While there is generally a strong link between population size and mortality rates, this is not consistent across all countries.  
For example, Ethiopia, despite its large population, has a relatively low mortality rate. Similar trends were seen in Uganda, Tanzania, Rwanda, and Sudan.  
This indicates that factors like healthcare access, infrastructure, and living conditions play a significant role in mortality, independent of population size.

### 3. Cardiovascular Diseases as the Leading Cause of Death
Cardiovascular diseases account for over 37 million deaths, making them the leading cause across the dataset.  
Unlike other causes such as HIV or neonatal disorders, deaths from cardiovascular conditions have shown a consistent upward trend.  
This underscores the growing need for long-term investment in heart health awareness, prevention, and treatment.

### 4. High Mortality Among Children Under 5
Children under five represent about 41% of total deaths, totaling 116 million.  
This highlights the urgent need for targeted interventions in early childhood healthcare, nutrition, and maternal support.

### 5. Varying Access to Medical Professionals
Countries like Nigeria and Egypt have the highest number of doctors, likely due to their large populations.  
However, countries such as Tunisia and Algeria also have relatively high access to doctors despite smaller populations, reflecting proactive healthcare system investments.  
This suggests that healthcare capacity is not solely tied to population size and can be enhanced through effective policy and planning.

---

## Machine Learning Insights

I used K-Means clustering, a machine learning technique, to group countries based on similarities in the following variables:

- Population vs Mortality
- GDP vs Mortality
- Healthcare Access vs Mortality

Each model grouped countries into three distinct clusters, helping us identify specific characteristics and outliers for further analysis, such as:

- Countries with lower populations but relatively high mortality rates, like South Africa, Sudan, and Ghana.
- Countries that show significant mortality variations despite considerable healthcare investments, such as South Africa.  


---

## Recommendations

- Prioritize healthcare programs for children under five to reduce high mortality rates.
- Implement cardiovascular disease prevention and early detection initiatives.
- Strengthen the healthcare workforce in under-resourced countries.
- Study countries with large populations and improving health outcomes, such as South Africa, to identify effective practices for reducing mortality rates.
- Assess healthcare investment efficiency in countries with high mortality despite significant resources.
- Employ clustering insights to design region-specific healthcare interventions.




### References

[Datasets](https://github.com/aminahol/Mortality-Rates-In-Africa/tree/6f6ec781e8beee0dccc6d98180c99336d762312f/datasets)

[Jupyter Notebook](https://github.com/aminahol/Mortality-Rates-In-Africa/blob/6f6ec781e8beee0dccc6d98180c99336d762312f/Mortality%20Rates%20In%20Africa%20(4).ipynb)

[PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTIwYmZhNGUtMzFmNy00ZWVlLWJmOGItNGVlMDMxYzNlZDc2IiwidCI6IjEwMWQ0NjY0LTg3OGEtNGUzYi04N2Y3LTc4ZjA4Yjc2MjhiYSJ9)
