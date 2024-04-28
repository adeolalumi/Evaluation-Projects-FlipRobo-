Avocado Analysis:
The analysis reveals significant insights into avocado pricing and market dynamics. Organic avocados command higher prices, indicating consumer
preferences and pricing strategies. Regional price variations, notably in areas like Hartford-Springfield, New York, and San Francisco, reflect 
differences in income levels and demand for organic produce. Data distribution analysis highlights right-skewed distributions in avocado volume and 
bag-related metrics, indicating occasional outliers. Avocado prices exhibit a moderately right-skewed distribution, with both lower-priced and 
higher-priced avocados present. Negative correlations between avocado prices and volume suggest price decreases with higher supply, while a weak 
positive correlation with time hints at a slight price increase over the years. 

Model evaluation favours RandomForestRegressor and XGBRegressor, with XGBoost selected for its robust performance. K-fold cross-validation ensures 
the reliability of the chosen model for future predictions and study. Overall, the analysis provides comprehensive insights into avocado pricing, 
regional variations, and predictive modelling, contributing to a deeper understanding of the avocado market.


HR Analysis: 
The HR analysis focuses on understanding attrition patterns within the company. Initial exploration reveals a lower attrition rate, indicating the
company's success in retaining employees. Age appears to have a potential association with attrition, but further statistical analysis is needed for
confirmation. Departmental analysis shows that Research and Development has lower attrition rates compared to Sales and HR. 

Additionally, there's a negative correlation between job satisfaction and environmental satisfaction, while age strongly correlates with job level. 
Outliers are addressed through logarithmic transformation, and high multicollinearity among variables prompts consideration for dropping some. 
Various classifiers are tested, with the Support Vector Classifier achieving perfect accuracy, suggesting optimal performance in predicting attrition.
However, caution is advised regarding potential overfitting, necessitating further validation of diverse datasets for robust conclusions.
