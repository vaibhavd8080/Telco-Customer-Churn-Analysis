# Telecom Customer Churn Analysis — Power BI

A Power BI dashboard exploring customer churn patterns in a telecom customer dataset. The report compares churn across customer groups and service characteristics to help identify segments that may need further investigation.

## Dashboard preview

![Telecom Customer Churn dashboard](images/dashboard_preview.png)

## Business questions

- What proportion of customers have churned?
- How does churn vary by contract type?
- How does churn differ across customer tenure groups?
- How does churn compare across internet service types?
- How does churn vary by payment method?
- Which customer segments may warrant further retention analysis?

## Dashboard features

- KPI cards for total customers, churned customers, churn rate and retained customers.
- Churn comparisons by contract type, internet service, payment method and tenure.
- Interactive slicers for exploring customer segments.
- Customer-level detail for further investigation.

## Key observations

The existing dashboard analysis highlights these descriptive patterns in the dataset:

- Month-to-month contract customers show the highest churn.
- Customers with shorter tenure are more likely to churn.
- Fiber optic customers show higher churn than DSL customers.
- Electronic check users show a higher churn frequency.

These are associations in the analysed data. They do not prove that contract type, tenure, internet service or payment method causes churn.

## Data preparation

The repository contains both the original CSV and a cleaned CSV. The project documentation describes category standardisation, missing-value handling, data-type checks and Power BI calculated measures.

There is currently no separate Python or SQL cleaning notebook in this repository. As a result, the README summarises the preparation work, but does not claim that every cleaning step can be reproduced from a script here.

## Tools and skills

- Microsoft Power BI
- DAX measures
- Power Query and data preparation
- Data modelling
- Interactive dashboard design
- Exploratory business analysis

## Repository structure

- \`Data/Telco-Customer-Churn.csv\` — original CSV
- \`Data/telco_churn_cleaned.csv\` — prepared CSV
- \`PowerBI/TELCO CUSTOMER CHURN ANALYSIS.pbix\` — Power BI report
- \`images/dashboard_preview.png\` — dashboard screenshot

## Limitations

- The repository does not currently document a source URL or licence for the dataset. Add the original source citation and licence before presenting this project as fully sourced.
- The cleaning workflow is described at a high level; no step-by-step transformation script is included.
- The observations are descriptive and should not be interpreted as causal explanations.
- The dashboard preview is static. Open the PBIX file in Power BI Desktop to explore its interactive controls.

## Author

**Vaibhav Deshmukh**  
[Aspiring Data Analyst — GitHub profile](https://github.com/vaibhavd8080)
