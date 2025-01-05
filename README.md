# Sales_Analysis_by_Stores_Dashboard
### Store Sales Performance and New Store Analysis

## Table of Contents:
- [Project Objectives](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#project-objectives)
- [Data Preparation](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#data-preparation)
- [Data Modeling](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#data-modeling)
- [Data Analysis (DAX)](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#data-analysis-dax)
- [Data Visualization (Dashboard)](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#data-visualization-dashboard)
- [Insights](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#insights)
- [Recommendations](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI?tab=readme-ov-file#recommendations)


## Project Objectives
The primary goal of this project is to analyze store sales performance and evaluate the impact of new stores on overall sales. Key objectives include:
- Identifying trends in sales variance and performance across districts.
- Assessing the contribution of new stores to total sales.
- Providing actionable recommendations to improve sales and operational efficiency.

---

## Data Preparation:
- Data transformation was done in Power Query and the dataset was loaded into Microsoft Power BI Desktop for modeling.
- Removed Unnecessary columns
- Removed Unnecessary rows
- Each of the columns in the table were validated to have the correct data type

## Data Modeling:
After the dataset was cleaned and transformed, it was ready to be modeled.
A star schema data model with the following relationships is shown below:

<p align="center" style="margin-top: 20px; margin-bottom: 20px;">
<img width="90%" src="https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI/blob/main/images/modeling.png" alt="Outcome"></img>
</p>

## Data Analysis (DAX):
Measures used in all visualization are:
<p align="center" style="margin-top: 20px; margin-bottom: 20px;">
<img width="20%" src="https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI/blob/main/images/key_measures.png" alt="Outcome"></img>
</p>

## Data Visualization (Dashboard):
Data visualization for the data analysis (DAX) was done in Microsoft Power BI Desktop:

| Dashboard 1 |
| ----------- |
|![dashboard1](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI/blob/main/images/3a_Store%20Sales%20Performance%20and%20New%20Store%20Analysis%20(Power%20BI).png)|


| Dashboard 2 |
| ----------- |
|![dashboard1](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI/blob/main/images/3b_Store%20Sales%20Performance%20and%20New%20Store%20Analysis%20(Power%20BI).png)|


| Dashboard 3 |
| ----------- |
|![dashboard1](https://github.com/ThuyTran102/Sales_Analysis_by_Stores_Dashboard_PowerBI/blob/main/images/3c_Store%20Sales%20Performance%20and%20New%20Store%20Analysis%20(Power%20BI).png)|


## Insights
#### **Store Sales Overview**
- **Sales Distribution**: Fashions Direct contributes 71% of total sales, while Lindseys accounts for 29%.
- **New Stores**: A total of 10 new stores opened, with noticeable contributions in specific regions.
- **Sales Variance by District Managers**:
  - Sales performance varies significantly across months and managers, with March showing the highest positive variance and July/August experiencing declines.

#### **District Monthly Sales**
- **Performance Trends**:
  - Monthly sales peaked in March, with a significant dip in April and stable performance thereafter.
  - New stores underperform slightly in terms of sales per square foot compared to established stores.
- **Category-Level Insights**:
  - "Women's" and "Men's" categories drive the majority of sales, with "Shoes" showing higher performance consistency.
- **Sales Variance**:
  - Positive variance in Q1 suggests successful promotions or seasonality, while later months show challenges in maintaining growth.

#### **New Stores Analysis**
- **Geographical Contribution**:
  - New stores are clustered in specific states like Ohio and Virginia, with a focus on urban and suburban areas.
- **Sales Efficiency**:
  - Winchester (Fashions Direct) leads in sales per square foot ($21.22), while Pasadena (Lindseys) underperforms ($10.92).
- **Opening Trends**:
  - Most new stores opened in May, with Lindseys contributing to the majority of openings.



## Recommendations
1. **Boost Underperforming Districts**:
   - Focus on training and targeted marketing for managers with consistent negative variances.
   - Review product assortments and customer preferences in these districts.
   
2. **Optimize New Store Openings**:
   - Leverage insights from high-performing stores (e.g., Winchester) to guide site selection and store operations.
   - Delay openings in Q3 based on historical underperformance during these months.

3. **Improve Sales Per Square Foot**:
   - Conduct store audits for lower-performing locations like Pasadena.
   - Introduce localized campaigns and product bundles to enhance in-store sales.

4. **Category-Specific Strategies**:
   - Expand inventory for high-performing categories such as "Women's" and "Shoes."
   - Address gaps in underperforming categories like "Home" and "Groceries."

5. **Monitor and Adjust Seasonal Strategies**:
   - Capitalize on seasonal sales trends by replicating successful Q1 strategies in subsequent quarters.
   - Analyze competition and macroeconomic factors impacting performance in Q2 and Q3.

---

## Conclusion
By addressing the key insights and implementing the above recommendations, the company can improve overall sales performance, enhance efficiency in new store openings, and achieve sustained growth across all districts.
