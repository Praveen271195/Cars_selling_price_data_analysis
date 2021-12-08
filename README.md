<h1 align="center">Analytics on Car Selling Price 🚗 🛒 💲</h1>

## Purpose of Repository:
The used cars market has grown rapidly in recent years and demand for passenger vehicles has encouraged the industry to collect enormous amounts of data. This document proposes an idea to use such a dataset for building a tool that can predict the selling price of a vehicle by using statistical techniques. This readme includes information and plan of actions to achieve the main goal of this project.

## About Dataset:
The dataset is sourced from a website called github. The original dataset includes 6 variables and 4,006 observations, but this is planned to be reduced to 5 variables, where 4 are predictors and 1 is the response variable. Total number of observations will be a random sample of 22.5% taken from the original dataset which will result in 901 observations in total. The 5 features are tabulated below:


<h4>Features in Dataset</h4>

<table>
  <tr>
    <th>Variables</th>
    <th>Continuous/Discrete/Categorical </th>
    <th>Predictor/Response</th>
  </tr>
  <tr>
    <td>vehicle_brand</td>
    <td>Categorical nominal (7 brands)</td>
    <td>Predictor</td>
  </tr>
  <tr>
    <td>year (model)</td>
    <td>Quantitative discrete</td>
    <td>Predictor</td>
  </tr>
  <tr>
    <td>engine_capacity</td>
    <td>Quantitative continuous</td>
    <td>Predictor</td>
  </tr>
  <tr>
    <td>mile_driven</td>
    <td>Quantitative continuous</td>
    <td>Predictor</td>
  </tr>
  <tr>
    <td>selling_price</td>
    <td>Quantitative continuous</td>
    <td>Response</td>
  </tr>
</table>

</body>
</html>


## Questions To Be Answered :
1. Whether a luxury car manufactured by a brand like Mercedes, has a higher selling price than a usual brand?
2. Does an old car have a low value in the resale market?
3. How does an engine specification/capacity of a car affect its selling price?
4. Does the resale price of the car drop as its distance covered increases?

Finding answers for the above questions will help me perform Exploratory Data Analysis to identify the causal relationship between the variables. Having this clarity would help me develop a multiple linear regression model that fits the data and will allow me to check if the fitted model has a higher explanatory power which could be interpreted by
computing R 2 value.

## Objective :
The main goal of this project is to predict the selling price of a used car (selling_price) based on 4 regressors mentioned: vehicle_brand, year, engine_capacity, miles_driven.

## Statistical Analysis :
Firstly, the original dataset's missing values are planned to be deleted and the scaling of the selling price variable would be performed based on my interpretations from data visualizations. Multiple Linear Regression is planned to be used to develop a model to fit the data so that the selling price of a car can be predicted based on the mentioned regressors. Summary of fit table will be used to interpret the R 2 value, sample size and Root Mean Squared Error. ANOVA table will be generated to interpret the measure of significance and Parameters estimates/coefficients table will be used to interpret the P-value.
