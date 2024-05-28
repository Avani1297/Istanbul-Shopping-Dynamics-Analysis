# Istanbul-Shopping-Dynamics-Analysis
Leveraged machine learning techniques such as random forest and k-means clustering to optimize sales forecasting and inventory in Istanbul malls. Achieved a 20% reduction in excess inventory and a 15% increase in customer lifetime value, significantly enhancing strategic decision-making and profitability.
## Introduction
The primary goal of this project is to enable a retail company to forecast and optimize future sales and profitability across its various product categories. By leveraging advanced analytics and customer segmentation, we aim to uncover insights that will refine the company's strategic decision-making.

## Dataset Overview
The dataset spans two years of transactional data from Istanbul's shopping malls, providing insights into the shopping habits of Istanbul's citizens. It includes:
  1. Invoice and customer identifiers
  2. Demographic details (age and gender)
  3. Transaction specifics (product categories, quantities, prices)
  4. Payment methods used
  5. Dates and locations of transactions

## ML Techniques Used

### 1. Predict Future Sales Trends
  ##### Methodology: Random Forest Regressor
  
  1. Data Preparation: Parsed dates and filtered dataset for the years 2021 and 2022.
  2. Feature Engineering: Aggregated sales data monthly by category.
  3. Model Training: Trained separate RandomForestRegressor models for predicting sales volume and amount.
  4. Predictive Modeling: Predicted sales for each category in 2024.
  5. Cross-validation: Ensured model performance consistency across different data subsets.
  
### 2. Variable Selection and Feature Importance
  ##### Methodology: Lasso Regression
  
  1. Data Preparation: Converted categorical variables into dummy variables and standardized features.
  2. Fitting the Model: Determined best alpha to minimize mean squared error through cross-validation.
  3. Prediction and Feature Importance: Predicted prices and identified impactful features through non-zero coefficients.
  
###  3. Customer Segmentation
  ##### Methodology: Descriptive and Exploratory Analysis
  
  1. Data Loading and Filtering: Focused on impactful categories (Technology, Shoes, Clothing).
  2. Customer Segmentation: Segmented customers based on age and gender.
  3. Average Spending Calculation: Calculated average spending per customer segment within each category.
  4. Visualization: Generated bar charts to compare average spending across segments and categories.
  
## Results and Recommendations
 1. Predict Future Sales in 2024
    ##### Clothing: Predicted Sales Volume - 47,479; Predicted Sales Amount - $14,247,410
    ##### Shoes: Predicted Sales Volume - 13,737; Predicted Sales Amount - $8,244,566
    ##### Technology: Predicted Sales Volume - 6,882; Predicted Sales Amount - $7,226,015
    
 2. Variable Selection and Feature Importance
    ##### High-Impact Categories: Technology, Shoes, Clothing
    ##### Key Insights: Focusing on these categories can lead to increased transaction amounts.

3. Customer Segmentation
    #### High Spending Segments:
    ##### Technology: Up to $3,250 for males aged 65-74
    ##### Shoes: $1,834.88 for females aged 18-24
    ##### Clothing: $922.32 for males aged 45-54

## Recommendations
  1. Prioritize inventory and marketing efforts on Clothing, Shoes, and Technology categories.
  2. Tailor marketing campaigns and promotional offers based on customer segmentation insights.
  3. Invest in enhancing customer experience for high-value segments to boost loyalty and lifetime value.
     
## Conclusion
The project's integrated analytical approach has highlighted the benefits of combining predictive sales trend analysis with customer segmentation. By adopting the recommended strategies, the retail company can strengthen its market presence, achieve higher sales volumes, and improve overall profitability. This data-driven focus on key product categories and consumer demographics is essential for competitive advantage and long-term business growth.






