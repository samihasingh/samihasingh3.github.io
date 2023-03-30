---
title: "Analyzing Racism in Housing Price Taxation in Cook County: A Data Science Exploration"
date: 2023-03-30
---

Housing discrimination and systemic racism have long plagued the United States. The Cook County Housing project aimed to analyze the extent of racism in housing price taxation in Cook County, Illinois, using computer science techniques. This project utilized a dataset from the Cook County Assessor's office, which contained information on over 500,000 properties and 61 features (excluding Sale Price of properties).

One of the primary goals of this project was to compare my custom model to the official model used by Cook County to understand the regressive taxation scheme implemented. The results showed that the custom model outperformed the official model, indicating that the county's taxation scheme may indeed be regressive.

To begin, I conducted exploratory data analysis using Seaborn, a Python library for data visualization. Nineteen visualizations were created to explore relationships between various features and housing prices. Additionally, data was extracted for four model features using Regex, a pattern-matching technique.

Then, a high-performing model was developed to predict housing prices using nine features and one-hot encoding. Cross-validation was used to evaluate the model's performance, ensuring that it would generalize well to new data. The model was then applied to the Cook County dataset, and the results were analyzed using linear regression and various visualizations.

In addition to the model comparison, feature selection analysis was conducted to reduce model complexity and improve accuracy. The custom model high in accuracy, as measured by mean square error in the test set.


The findings of this project shed light on the prevalence of racism in housing price taxation in Cook County. By using computer science techniques, this project was able to analyze a vast dataset and provide valuable insights into the issue. The high-performing custom model developed in this project could potentially be used to inform policy decisions regarding housing taxation in Cook County and beyond.

In conclusion, the Cook County Housing project was a valuable application of computer science techniques to analyze and understand issues related to systemic racism and housing discrimination. Through the use of advanced modeling and data visualization techniques, this project was able to uncover important insights and contribute to ongoing efforts to address these critical issues.
