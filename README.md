# Customer Churn Analysis with Power BI

![Screenshot (115)](https://github.com/user-attachments/assets/bc2f3ede-c5b6-44ed-a4ba-66761f1ea2b4)


This project involves analyzing customer churn for a telecom company, Databel, using Power BI. The goal is to understand churn rates, identify reasons behind customer churn, and develop strategies to reduce churn. The analysis includes data import, cleaning, preprocessing, creating measures and calculated columns, and designing visualizations.

## Project Overview

### Objective
- Analyze customer churn rates.
- Identify key drivers of churn.
- Provide actionable insights and recommendations to reduce churn.

### Tools and Technologies
- Power BI
- DAX (Data Analysis Expressions)
- Data Visualization

## Steps Taken

### 1. Data Import and Cleaning
- Imported the telecom company dataset into Power BI.
- Cleaned and preprocessed the data to ensure accuracy and consistency.

### 2. Created Measures and Calculated Columns
- Developed dynamic calculations using DAX:
  - **Churn Rate**: `Churn Rate = DIVIDE(COUNTROWS(FILTER(Customers, Customers[Churn] = "Yes")), COUNTROWS(Customers))`
  - **Customer Lifetime**: `Customer Lifetime = DATEDIFF(Customers[StartDate], Customers[EndDate], MONTH)`

### 3. Visualizations
- Created a variety of visualizations to represent data insights:
  - **Line Charts**: Show trends in churn rate over time.
  - **Bar Charts**: Compare churn rates across different segments (e.g., regions, customer types).
  - **Pie Charts**: Display the proportion of churned vs. active customers.
  - **Heatmaps**: Identify areas with high churn rates.
  - **Tables**: Present detailed data for analysis.
  - **Slicers**: Allow interactive filtering of data by different dimensions (e.g., time period, customer demographics).

### 4. Analyzing Churn Causes
- Analyzed data to identify key factors contributing to churn:
  - **Customer Demographics**: Age, gender, income level.
  - **Service Usage Patterns**: Data usage, call patterns.
  - **Customer Feedback**: Satisfaction scores, complaints.

### 5. Actionable Insights and Recommendations
- Based on the analysis, provided recommendations to reduce churn:
  - Improve customer support for high-churn segments.
  - Offer targeted promotions and discounts.
  - Enhance service quality and reliability.

### 6. Report Design
- Designed eye-catching and informative report pages.
- Ensured the reports were easy to navigate with a logical flow of information.

## Key Takeaways
- Understanding and reducing customer churn involves not only tracking metrics but also uncovering the stories within the data.
- Effective data visualization can drive strategic business decisions and improve customer retention.

## Project Files
- [Power BI Report File (.pbix)](https://github.com/Aakaaaassh/Case-Study-Analyzing-Customer-Churn-in-PowerBI/blob/main/Final%20Customer%20Churn%20Report.pbix)

## Contact
For any questions or feedback, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/Aakaaaassh).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

