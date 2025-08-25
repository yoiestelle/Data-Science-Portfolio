## Overview
This project analyzes telecom customer data to predict churn using Logistic Regression.  
It includes model evaluation (log loss) and feature fine-tuning experiments.

## Key Features
- Baseline logistic regression model
- Fine-tuning with feature selection (+callcard, +wireless, etc.)
- Coefficient visualization
- Clear conclusion with actionable insights for business

## Results
- Baseline log loss: ~0.543  
- Best model (+callcard + wireless): log loss ~0.539  
- Key takeaway: tenure strongly reduces churn risk; removing `income` or `employ` worsens performance.

[Open the full notebook](machine-learning/custom$er-churn-logistic-regression/Customer%20Churn%20Prediction.ipynb)
