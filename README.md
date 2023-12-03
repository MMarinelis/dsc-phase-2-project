# Phase 2 Project

# Overview

The aim of this project was to analyse 'kc_house_data.csv' and align it with 'column_names.md' to predict some of the key features of what makes a house more valuable.
The main question explored in this project is:
What are the primary factors influencing housing prices in Kings County?

The focus was on providing actionable insights for a real estate agency to assist homeowners in buying or selling homes.

# Key Findings

Influential Features
Square Feet of Living Space (sqft_living): Larger living spaces significantly increase house prices.
Waterfront: Waterfront properties command higher prices.
Views: Better views are associated with higher prices.
Bathrooms : More bathrooms contribute to higher prices.
Bedrooms: A higher number of bedrooms slightly decreases the price.

# Model Performance and Validation

R-squared and Adjusted R-squared: The model achieved an adjusted R-squared of 0.523, indicating a moderate level of fit.
K-Fold Cross-Validation: To validate the model, K-fold cross-validation was employed, ensuring that the model's findings were consistent and not overly dependent on any particular subset of the data.
Mean Squared Error (MSE): The MSEs for both the training and testing datasets were very close, suggesting that the model generalizes well to new data.

# Limitations and Issues

Multicollinearity: Indicated by a high condition number, multicollinearity among predictors could be distorting coefficient interpretations.
Statistical Significance: Some features showed no significant impact on prices.
Residual Analysis: Suggested the need for checking assumptions like normality of residuals and homoscedasticity.
Methodology
The Ordinary Least Squares (OLS) regression was the primary analytical tool. Model validation included K-fold cross-validation and MSE comparison, which revealed consistent performance across training and testing phases.

Reflecting on the Project: With the benefit of hindsight, I recognize there were valuable lessons and areas of knowledge that I've only recently come to fully understand. I am eager to apply these insights in future endeavors to enhance both the process and the outcomes.

# Recommendations

Focus on Renovations with High ROI: Advise homeowners to invest in expanding living space and upgrading bathrooms.
Emphasise high-value areas: Emphasize properties' waterfront and view attributes in marketing campaigns.

# Conclusion

While the model identified key influencing features, addressing multicollinearity and other limitations is essential. Future iterations should include more nuanced modeling approaches and continuous validation to enhance prediction accuracy and reliability.

The files included in this repositry include:
data.ipynb - Jupyter Notebook
Predicting House Prices in King's County.mp4
Presentation.pdf
