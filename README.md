# SWYNEX-Final-Data-Analytics-Project
End-to-end Data Analytics Project | Python · Pandas · Power BI · DAX

# 🏋️‍♂️ Gym Membership Analysis

## 📌 Project Overview
This end-to-end data analytics project explores a synthetic gym membership dataset to understand member demographics, membership distribution, gym attendance, workout duration, and additional service usage.

The project covers data cleaning, exploratory data analysis (EDA), data visualization, and interactive dashboard development using Python and Power BI.

## ❔Problem Statement
Gym management needs a clearer understanding of member demographics, attendance patterns, membership preferences, and participation in additional services. This analysis explores these areas to identify useful patterns and potential opportunities for improving member engagement and service planning.

## 📖 Dataset Information
- Dataset: Gym Membership Dataset – Exploring Membership Trends: A Synthetic Dataset for EDA and Machine Learning
- Records: 1,000
- Original columns: 17
- Data type: Synthetic gym membership data

## 🧰 Tools and Technologies
- Python
- Pandas
- Matplotlib
- Google Colab
- Microsoft Power BI
- DAX
- Excel

## 📽️ Project Workflow

### Task 1: Data Cleaning
- Inspected dataset structure and data types.
- Identified and handled missing values using the relevant service participation fields.
- Checked for duplicate records and duplicate IDs.
- Standardized multi-value categorical entries.
- Renamed inconsistent column names.
- Exported the cleaned dataset to Excel.

### Task 2: Exploratory Data Analysis
- Calculated descriptive statistics for age, weekly visits, and gym duration.
- Analyzed membership type and age-group distributions.
- Compared weekly visits and gym duration across membership types.
- Examined participation in personal training, group lessons, and sauna usage.
- Explored the relationship between age and gym duration.
- Used the IQR method to identify statistical outliers.

### Task 3: Interactive Power BI Dashboard
The dashboard includes:
- KPI cards for total members, average age, average weekly visits, average gym time, premium membership percentage, and personal training usage percentage.
- Membership type distribution.
- Age-group distribution.
- Average weekly visits by membership type.
- Average gym time by membership type.
- Additional service usage.
- Age versus gym duration scatter plot.
- Interactive slicers for membership type, age group, gender, and personal training.

## ✔️ Key Findings
1. Standard membership has 507 members (50.7%), while Premium membership has 493 members (49.3%).
2. Members aged 26–45 represent 53.8% of the dataset.
3. Average weekly visits are almost identical for Premium and Standard members.
4. Average gym duration is approximately 105 minutes for both membership types.
5. Personal training participation is 51.8%, group lesson participation is 50.3%, and sauna usage is 49.3%.
6. The correlation between age and gym duration is -0.041, indicating virtually no linear relationship.
7. The IQR method identified 124 statistical outliers in weekly visits. These correspond to members visiting five times per week and were retained because this frequency is plausible.

## 🛡️ Business Recommendations
- Review the preferences and needs of members aged 26–45 when planning services and engagement activities.
- Investigate opportunities to increase participation in additional services through member feedback and targeted promotions.
- Compare engagement and retention measures across membership types before making membership strategy decisions.
- Monitor attendance patterns to support class scheduling and gym resource planning.
- Collect additional data over time to assess trends and evaluate the effectiveness of future initiatives.

These are potential recommendations based on observed patterns; their business impact would need further validation.

## Conclusion
This project demonstrates an end-to-end analytics workflow, from cleaning and exploring data to presenting findings in an interactive Power BI dashboard. It highlights membership patterns, service participation, and attendance behavior while distinguishing statistical outliers from likely data errors.

## 📁 Project Files
- Cleaned dataset: `data/gym_membership_cleaned.xlsx`
- Python notebooks: `notebooks/`
- Power BI dashboard and screenshot: `dashboard/`
- Final report: `report/`

## Skills Demonstrated
Data Cleaning | Exploratory Data Analysis | Python | Pandas | Matplotlib | Power BI | DAX | Data Visualization | Business Insights
