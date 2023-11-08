# Ecommerce Linear Regression Analysis README

## Overview

This README provides an overview of a linear regression analysis performed on an Ecommerce dataset from a clothing store company. The goal of the analysis is to help the company decide whether to concentrate on their mobile app service or website, based on the yearly amount spent by the customers to grow the business.

https://www.kaggle.com/datasets/leilaaliha/ecommerce-customers/data

## Data Description

The dataset includes the following columns:

- Email: Customer's email address.
- Address: Customer's address.
- Avatar: Customer's avatar color.
- Avg. Session Length: Average session length in minutes.
- Time on App: Time spent on the mobile app in minutes.
- Time on Website: Time spent on the website in minutes.
- Length of Membership: How long the customer has been a member in years.
- Yearly Amount Spent: The annual amount spent by the customer.

## Analysis Steps

1. **Data Loading:** The dataset was loaded and explored to understand its structure and content.

2. **Data Preparation:** The data was split into independent variables (X) and the dependent variable (y).

3. **Data Splitting:** The data was divided into training and testing sets with a 70-30 split ratio.

4. **Linear Regression:** A linear regression model was created using scikit-learn's LinearRegression class.

5. **Model Training:** The model was trained using the training data.

6. **Model Evaluation:** The model's performance was evaluated using the testing data. Mean Squared Error (MSE) and R-squared (R2) were calculated to assess prediction accuracy and goodness of fit.

7. **Model Coefficients:** The coefficients and intercept of the model were extracted to interpret the impact of each independent variable on yearly spending.

## Results

The analysis yielded the following results:

- Mean Squared Error (MSE): Approximately 80.90
- R-squared (R2): Approximately 0.9885
- Coefficients:
  - Avg. Session Length: ~25.83
  - Time on App: ~38.81
  - Time on Website: ~0.28
  - Length of Membership: ~61.30
- Intercept: ~-1048.82

## Interpretation

- The analysis suggests that customer engagement with the mobile app has a significantly greater positive impact on yearly spending compared to the website.
- Customer loyalty and the "Length of Membership" have a substantial positive influence on increasing yearly spending.
- Improving the website's user experience and engagement could still have a positive impact on yearly spending.

## Recommendations

- Consider concentrating resources and efforts on further enhancing the mobile app's user experience and features.
- Continue to invest in customer loyalty and retention strategies, as indicated by the "Length of Membership" variable.
- Improve the website to make it more competitive with the mobile app.

## Conclusion

This linear regression analysis provides valuable insights into factors that influence yearly spending by customers. It guides the company's decision-making process in focusing on the mobile app and improving customer engagement on the website. It also highlights the importance of customer loyalty in growing the business.

## Author

Carolina Jiménez M

https://carolinajimenez.github.io
