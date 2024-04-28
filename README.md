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

Baseball Analysis: 

This analysis delves into the relationships between various baseball statistics, shedding light on factors influencing team performance. Key findings include the positive correlation between runs scored (R) and wins (W), indicating that teams scoring more runs tend to win more games. Additionally, a strong negative correlation exists between wins (W) and earned run average (ERA), emphasizing the significance of pitching performance in determining success. However, there's little to no relationship between runs scored (R) and earned run average (ERA), suggesting they may not directly influence each other significantly. Exploring data distributions reveals positive skewness in win counts, home runs, and runs scored, highlighting the tendency for most teams to have fewer wins or fewer runs than the average, with some exceptions. Outlier detection and replacement with the median ensure data integrity and robustness in subsequent analyses. Strong correlations between specific variables are observed, guiding feature engineering and model selection. Initial modeling results showcase the linear regression model's effectiveness in predicting team performance, with a high R-squared value indicating its ability to explain variance in the target variable. Overall, the analysis provides valuable insights for understanding and predicting baseball team performance.
