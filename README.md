# Ecoworld Real Estate 

## Ecoworld Real Estate Report

### Introduction / Background / Preamble

The real estate sector is a critical component of the economy, reflecting both individual investment behavior and broader market trends. Understanding property sales patterns, pricing structures, and geographic distribution is essential for stakeholders such as investors, developers, and policymakers.
This project explores property sales data from 2013 to 2016 across different cities, property types, and grades. The study leverages data analysis and visualization techniques to uncover trends, insights, and actionable recommendations.

###  Data Source

The dataset was provided in an Excel file (Project 1 Real Estate.xlsx) containing four sheets: 2013, 2014, 2015, and 2016. Each sheet included property-level transaction details such as:
Sale price
Property value
Bedrooms, bathrooms, and square footage
Year built
Property grade and type
Location (city)

[Project 1 Real Estate 1.xlsx](https://github.com/user-attachments/files/22084307/Project.1.Real.Estate.1.xlsx)


### Objectives

The project was guided by the following objectives:
1. Assess the total property sales and value over the years.
2. Identify trends in sales by year and month.
3. Compare average sales price by city.
4. Analyze property type distribution by grade.
5. Provide insights and recommendations for stakeholders in the real estate sector.

### Technical Skills Used in the Project

- Data Cleaning & Transformation: Excel, Power Query (Power BI)
- Data Modelling: Power BI DAX (calculated columns, measures, aggregations)
- Data Visualization: Power BI (cards, line charts, donut charts, bar charts, filters/slicers)
- Analytical Skills: Exploratory data analysis, trend analysis, comparative analysis

### Data Cleaning / Transformation / Modelling
Steps taken:
- Null Values Handling: Removed or replaced missing values in price, property value, and city columns.
- Data Type Corrections: Ensured numeric fields (price, value) were stored as numbers.
Derived Columns:
- Average Sale Price = Total Sales ÷ Total Properties
- Year Column for combining all years in a single table
- Data Modelling: Consolidated the four yearly datasets (2013–2016) into one unified model.

![Table View](https://github.com/user-attachments/assets/dccc7ab0-e14e-41c5-9df3-4eea70bc0559)

![Model View](https://github.com/user-attachments/assets/cd41375e-2095-431c-ad12-4525950636eb)


###  Data Analysis / Visualization
The Power BI dashboard was designed with an executive summary style, highlighting key metrics and insights:
KPI Cards:
- Total Property Value: ₦6B
- Total Sales Price: ₦7B
- Total Properties: 21K
- Average Sales Price: ₦274K
- Line Chart: Monthly Sales Price trend (2013–2016) → Peak in June–July.
- Donut Chart: Sales Price contribution by year → 2015 led with ~2B in sales.
- Bar Chart: Average Sales Price by City → Brentwood (₦305K).
- Bar Chart: Top 5 Property Grades → Grade C dominates (~17K units).

  ![Real Estate 2](https://github.com/user-attachments/assets/150b31d1-691a-4ff6-85f2-409c60dfb971)


### Interpretation / Insight
1. Market Growth: Sales rose consistently from 2013 to 2015, showing market expansion.
2. Seasonality: Sales peaked mid-year (summer), likely due to higher buyer activity.
3. City Distribution: Brentwood dominates premium sales; Nashville and Mount Juliet represent strong mid-market sales.
4. Property Grade: Grade C properties form the bulk of the market, indicating strong demand for mid-range housing.
5. Investment Outlook: Premium markets remain attractive but are limited in volume compared to mid-range.

### Conclusion / Recommendation
- Investors: Focus on Grade C properties for volume-driven returns, while selectively targeting Grade A/B for premium margins.
- Developers: Prioritize cities like Brentwood and Nashville where demand and pricing are higher.
- Policy Makers: Recognize mid-range housing as a driver of stability in the real estate sector.
- Future Work: Extend the analysis to newer years (2017–2023) to capture recent market dynamics.

#### Closing
This project demonstrates the application of data analytics and visualization in uncovering valuable insights from real estate data. Power BI proved to be a powerful tool for transforming raw property data into actionable intelligence, empowering better decision-making for stakeholders.
