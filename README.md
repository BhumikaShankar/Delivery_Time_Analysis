#  Food Delivery Time Analysis — Power BI

##  Project Overview

An end-to-end data analytics project analyzing **45,584 food delivery records** to identify factors associated with longer delivery times.

The project combines **Python/Pandas for data cleaning and statistical analysis** with **Power BI for interactive business reporting and visualization**.

##  Business Problem

> What operational factors are associated with longer food delivery times, and where can delivery operations focus to improve performance?

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Statistical Analysis (Hypothesis Testing)
- Power BI
- DAX
- Power Query

##  Analysis Performed

- Data cleaning and missing-value analysis
- Distance calculation between restaurant and delivery location
- Outlier analysis
- Descriptive statistics
- Correlation analysis
- ANOVA
- Regression analysis
- Interactive Power BI dashboard

##  Key Findings

- Average delivery time was approximately **26.6 minutes**.
- Delivery time showed a positive association with delivery distance.
- **Traffic density** was associated with substantial differences in average delivery time.
- **Weather conditions** showed significant differences in delivery times.
- Multiple deliveries were associated with higher average delivery times.
- Distance alone did not explain all variation in delivery time, indicating the importance of other operational factors.

## Power BI Dashboard

The dashboard includes:

- Total Deliveries
- Average Delivery Time
- Maximum Delivery Time
- Late Delivery % (with 20 mins taken as threshold)
- Delivery time by traffic density
- Delivery time by weather conditions
- Delivery time by vehicle type
- Multiple deliveries analysis
- Distance-band drill-down

##  Business Recommendation

Delivery operations should pay particular attention to **high-traffic conditions, adverse weather, longer delivery distances, and multiple-delivery assignments** when investigating potential delivery delays.

> **Note:** The analysis identifies associations rather than proving causal relationships.

