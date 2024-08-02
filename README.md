# census_income
Introduction
This project focuses on analyzing the 'Census Income' dataset from the UCI Machine Learning Repository. The dataset contains income information for over 48,000 individuals from the 1994 US Census. The analysis involves data preprocessing, exploratory analysis, visualization, and building machine learning models to predict whether an individual earns more than $50,000 a year.

Table of Contents
Introduction About the Dataset Data Preprocessing Data Manipulation Data Visualization Statistical Analysis Machine Learning Models Linear Regression Logistic Regression Decision Tree Classifier Random Forest Classifier Evaluation Conclusion

About the Dataset
The dataset contains demographic and income information for individuals from the 1994 US Census. The key features include:

age: Age of the individual workclass: Type of work class education: Level of education marital-status: Marital status occupation: Type of occupation relationship: Relationship status race: Race of the individual sex: Gender of the individual capital-gain: Capital gain capital-loss: Capital loss hours-per-week: Hours worked per week native-country: Country of origin income: Income category (<=50K or >50K)

Data Preprocessing
Handling Missing Values:
Replaced missing values with 'NA'. Removed rows containing 'NA' values.

Label Encoding:
Converted categorical variables into numerical format using label encoding.

Data Manipulation
Extracting Specific Columns and Rows:

Extracted the 'education' column. Extracted all male employees working in state-gov. Extracted columns number 5, 8, and 11. Extracted 39-year-olds with a bachelor's degree or native of the United States. Extracted 200 random rows from the dataset.

Calculating Statistics:
Counted different levels of the 'workclass' column. Calculated the mean of the 'capital gain' column grouped by 'workclass'. Created a dataframe with males and females earning more than $50,000. Calculated the percentage of private employees from the US earning less than $50,000. Calculated the percentage of married people. Calculated the percentage of high school graduates earning more than $50,000.

Data Visualization
Visualizing Distributions and Relationships: Created various plots to visualize the distribution of income categories, workclass, education levels, and more.

Statistical Analysis
One Sample Test for Mean:
Tested if the average purchase made by men aged 18-25 is equal to 10000. Result: The mean purchase for this group is not 10000 (p-value < 0.05).

One Sample Test for Proportion:
Tested if the proportion of women spending more than 10000 is 35%. Result: The proportion is not 35% (p-value < 0.05).

Two Sample Test for Means:
Compared the average purchases between men and women aged 18-25. Result: The average purchases are not the same (p-value < 0.05).

Two Sample Test for Proportions:
Compared the percentage of men spending more than 10000 between age groups 18-25 and 26-35. Result: The percentages are the same (p-value > 0.05). Machine Learning Models

Linear Regression:
Built a linear regression model to predict income. Evaluated the model using RMSE (Root Mean Squared Error).

Logistic Regression:
Built a logistic regression model to classify income categories. Evaluated the model using accuracy score and confusion matrix.

Decision Tree Classifier:
Built a decision tree classifier to predict income categories. Evaluated the model using accuracy score and confusion matrix.

Random Forest Classifier:
Built a random forest classifier with 300 estimators. Evaluated the model using accuracy score and confusion matrix.

Evaluation
The machine learning models were evaluated based on their accuracy and confusion matrix. Visualization techniques helped in understanding the distribution and relationships between various features. Data cleaning and preparation ensured that the analysis was based on a high-quality dataset.

Conclusion
The analysis revealed significant patterns in income distribution based on demographic and occupational features. Key findings include:

Certain demographic features such as age, education, and occupation significantly influence income levels. Machine learning models like Logistic Regression, Decision Tree, and Random Forest provide reasonable accuracy in predicting income categories. The insights gained from this analysis can help in developing targeted policies and programs to address income inequality. These insights can help policymakers and organizations in understanding income distribution patterns and designing interventions to promote economic equality. The statistical tests validate the hypotheses, providing a solid foundation for making data-driven decisions.
