# Black Bear Body_weight Analysis Repository
This GitHub repository provides an extensive analysis of the dataset "Estimating the Live Body_weight of American Black Bears in Florida." The analysis primarily focuses on the relationship between chest girth, age, and body length concerning the body weight of black bears. The purpose of this repository is to document the data analysis process comprehensively, including data collection, exploratory data analysis, multiple linear regression models, hypothesis testing, confidence intervals, and more.

## Data Source
The data for this analysis is sourced from the article "Estimating the Live Body_weight of American Black Bears in Florida." We will specifically be using the variables "chest_girth," "age," "body_length," and "body_weight" from the dataset "bear_statistics_cleaned.csv."

## Analysis Process
The analysis in this repository will follow several key steps:

### Simple Linear Regression (SLR) for Body Weight vs. Chest Girth
1. We will create a simple linear regression (SLR) model to explore the relationship between body weight and chest girth. The regression equation will be developed, and the significance of the model will be tested using T-tests and the Coefficient of Determination.

2. The B0 and B1 terms in the equation will be explained in their statistical context, with B0 representing the intercept, and B1 representing the coefficient of the chest girth.

### Multiple Linear Regression for Body Weight
3. We will take the analysis a step further by creating a multiple linear regression model for body weight that includes chest girth and age as independent variables. This model will be tested with an F-Test and T-tests, where appropriate.

4. The meanings of B0, B1, and B2 in this multiple regression equation will be discussed in terms of their statistical significance, with B0 as the intercept, B1 as the coefficient for chest girth, and B2 as the coefficient for age.

### Further Extension: Multiple Linear Regression with Body Length
5. In an extended analysis, we will create a multiple linear regression model for body weight that includes chest girth, age, and body length as independent variables. This model's equation will be provided and explained, with B3 representing the coefficient for body length.

6. The Coefficient of Determination for this multiple regression equation will be calculated, and its implications for the equation's strength will be discussed.

### Confidence Intervals and Predictions
7. Confidence intervals for the mean (expected) weight of bears and the projected weight of bears, given the regression equations, will be presented.

Please note that this README.md file serves as an overview of the analysis process. The comprehensive analysis, along with detailed code and findings, can be found in the associated code files within this repository. The final results, including findings and conclusions, will be compiled into a comprehensive report.
