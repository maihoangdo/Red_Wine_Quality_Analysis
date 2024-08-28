# Red Wine Quality Analysis
## Project Overview
This project aims to predict the quality of red wine based on its physicochemical properties using machine learning algorithms. By utilizing the Red Wine Quality Dataset from the UCI Machine Learning Repository, we perform data visualization, regression analysis, and predictive modeling to understand the factors that influence wine quality and to identify how changes in key variables could improve it.

## Dataset Description
- Source: UCI Machine Learning Repository
- Number of Observations: 1599
- Number of Variables: 12 (11 input features, 1 output feature)
- Missing Values: None
- Input Variables:
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol
- Output Variable: Quality (rated on a scale of 0 to 10)
## Methodology
- Data Preprocessing:
The dataset was cleaned and normalized, with particular attention paid to scaling the numeric variables for better model performance. No missing values were present in the dataset, making it ideal for machine learning algorithms.
- Exploratory Data Analysis (EDA):
Data visualizations were generated to explore the relationships between the wine's chemical properties and its quality score. Correlations were assessed to identify the most impactful features. For instance, alcohol content and volatile acidity were found to have notable correlations with the wine’s quality.
- Modeling:
Four machine learning models were trained and evaluated for their predictive power:
  - Random Forest Classifier
  - Decision Tree
  - Support Vector Machines (SVM)
  - Linear Regression
After tuning hyperparameters and cross-validating the models, the Random Forest Classifier emerged as the most accurate model in predicting wine quality, marginally outperforming the other models.
## Model Performance:
- The Random Forest Classifier achieved the highest accuracy due to its ability to handle large datasets and model complex interactions between the input features. The model's ability to aggregate predictions from multiple decision trees made it well-suited for this multivariate dataset.
## Key Findings
Alcohol: One of the strongest indicators of wine quality, with higher alcohol content often corresponding to higher quality.
Volatile Acidity: Found to negatively impact wine quality; wines with higher volatile acidity tended to score lower.
Sulphates and pH: Both play crucial roles in determining the quality of wine. Wines with balanced sulphates and pH levels scored higher in quality.
## Conclusion
Through data analysis and predictive modeling, we identified key chemical properties that influence the quality of red wine. By adjusting these variables, winemakers may be able to improve wine quality, and consequently, profitability. The Random Forest Classifier performed the best among the models tested, highlighting its robustness in dealing with complex, multivariate datasets. The insights gained from this analysis could help winemakers refine their production process to consistently produce higher-quality wines.

## Future Work
- Feature Engineering: Further analysis could explore the impact of combining multiple variables, such as acidity and sulphates, to see how they interact to influence quality.
- Predictive Improvements: Expanding the dataset to include external factors such as grape variety, vineyard location, and aging time could help improve the accuracy of the predictions.
- Real-World Application: Winemakers could implement the findings by adjusting chemical properties during production, using the model as a guide to predict and optimize wine quality.
## References
- Dataset: UCI Machine Learning Repository - Red Wine Quality ((https://archive.ics.uci.edu/ml/datasets/wine+quality))
- Relevant Publication: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis, "Modeling wine preferences by data mining from physicochemical properties," in Decision Support Systems, Elsevier, 47(4):547-553, 2009.


