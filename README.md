### TASK-5 – Exploratory Data Analysis (EDA) Report
Author: Anvesh kumar
Dataset Used: train.csv (Titanic Dataset – Kaggle Version)

1. Objective
The objective of this analysis is to explore the Titanic dataset to identify key factors affecting passenger survival during the Titanic disaster. Through summary statistics and visual analysis, meaningful patterns, trends, and correlations are discovered.

2. Dataset Overview
Attribute	Description
Total Rows	891
Total Columns	12
Target Variable	Survived (0 = No, 1 = Yes)
Types of Data	Numerical & Categorical

3. Handling Missing Values
Column	Missing	Action
Age	177	Filled using Median
Embarked	2	Filled using Mode
Cabin	687	Dropped due to high missing ratio
Handling missing values ensures more reliable statistical and visual analysis and prevents bias in model predictions.

4. Key Findings & Insights
4.1 Survival by Gender
•	Female passengers were significantly more likely to survive than males.
•	Indicates the “Women and Children First” rescue protocol.
4.2 Survival by Passenger Class
•	Passengers in 1st class had a much higher survival probability compared to 2nd and 3rd class.
•	Wealth and access to better rescue positions influenced survival.
4.3 Fare Impact
•	Higher fare (indicator of socio-economic status) correlates positively with survival.
4.4 Age Factor
•	Children and younger passengers survived at higher rates.
•	Average survivor age was lower than non-survivors.

5. Correlation Summary
Feature	Influence on Survival
Sex	Strongest influence
Pclass	Higher class = higher survival
Fare	Positive correlation
Age	Younger passengers survived more

6. Conclusion
Survival during the Titanic disaster was not random. It was strongly influenced by demographic and socio-economic factors. Women, children, and wealthier passengers had significantly higher survival chances. Therefore, the key determinants of survival were Gender, Passenger Class, and Fare.

7. Future Work
•	Build prediction models using Logistic Regression, Random Forest, etc.
•	Feature engineering: family size, title extraction, deck from cabin.
•	Compare model accuracy after feature transformation.


End of Report
Thank you.

