## Overview

This project demonstrates how Logistic Regression can be applied to predict telecom customer churn.  
It highlights my machine learning skills in model building, evaluation, feature selection, and interpretation of results with actionable business insights.  

## Project Details  

The tasks in this project are as follows:  

- Build a **baseline Logistic Regression model** to predict churn  
- Evaluate performance using **log loss**  
- Conduct **feature fine-tuning experiments** (+callcard, +wireless, etc.)  
- Visualize feature coefficients to interpret model decisions  
- Draw **business insights** from the results  

## Results  

- **Baseline log loss:** ~0.543  
- **Best model (+callcard + wireless):** log loss ~0.539  
- **Key takeaway:** Customers with more equipment and wireless services are at **higher risk of churn**,  
  while older, long-tenured customers who use call cards are at **lower risk of churn**.  

From a business perspective, the model suggests focusing retention strategies on younger,  
wireless-heavy customers with multiple devices, while maintaining loyalty programs for  
older and long-tenured clients.

[Open the full notebook](https://github.com/yoiestelle/Data-Science-Portfolio/blob/main/machine-learning/customer-churn-logistic-regression/Customer%20Churn%20Prediction.ipynb)

