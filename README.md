 HEALTH AND LIFESTYLE FACTORS INFLUENCING INSURANCE CLAIM AMOUNT
 
 Project Overview

This project explores how demographic, health, and lifestyle factors affect insurance claim amounts.
By analyzing data on age, gender, BMI, smoking status, hereditary diseases, diabetes, and exercise habits, the project uncovers key patterns that influence health risks and medical costs.

The insights derived can help insurers improve risk assessment, premium pricing, and policy design.

🎯 Objective

To analyze and understand how lifestyle and health-related factors impact health insurance claims, and to identify which variables have the most significant effect on claim amounts.

🧩 Dataset Information

File: healthinsurance.csv

Records: ~15000

Columns Include:

age – Age of the policyholder

sex – Gender

bmi – Body Mass Index (health indicator)

smoker – Whether the person smokes or not

diabetes, hereditary_diseases, exercise – Health & lifestyle variables

claim – Insurance claim amount

⚙️ Project Workflow

Data Understanding & Import

Loaded dataset using pandas.

Data Cleaning

Handled missing values (median/mode imputation).

Removed duplicates.

Created new variables like Age_Group and BMI_Category.

Exploratory Data Analysis (EDA)

Univariate, bivariate, and multivariate analysis.

Visualized relationships using:

Bar plots

Pie charts

Histograms

Box plots

Violin plots

Scatter plots

Heatmaps

Pivot tables

Insights & Interpretation

Examined how each factor (e.g., smoking, BMI, age) affects claim amount.

Conclusion

Derived key insights for insurers and policyholders.

Limitations & Future Scope

Suggested adding more behavioral and regional factors.

Final Takeaway

Promoting healthy living helps reduce medical and insurance costs.

📊 Key Insights

Smokers have significantly higher claim amounts than non-smokers.

Claim amount increases with age, especially above 45.

Obese individuals show higher claims, confirming BMI as a strong risk factor.

Diabetes and hereditary diseases lead to moderately higher claims.

Combined factors (older + smoker + obese) result in the highest claim levels.

📈 Visualizations Used
Visualization	Purpose
Histogram	Distribution of numerical data
Bar Plot	Compare averages or counts
Pie Chart	Proportion of categories
Box / Violin Plot	Identify outliers and spread
Scatter Plot	Show relationships between variables
Heatmap	Display correlations
Pivot Table	Summarize averages by groups
🧠 Tools and Libraries

Python

pandas

numpy

matplotlib

seaborn

Jupyter Notebook for analysis and documentation

💡 Conclusion

Healthy lifestyle choices — such as avoiding smoking, maintaining normal BMI, and managing chronic diseases — lead to significantly lower health insurance claims.
Insurers can use these insights to design data-driven premium models, encourage preventive care, and promote wellness programs for customers.
