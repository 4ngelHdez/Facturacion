# Beverage Company Billing Analysis

### Project Description

In this project, I focused on analyzing the billing behavior and payment methods of an international soft drinks company operating across several Latin American countries. The main goal was to understand billing trends and customer payment preferences in the different regions where the company distributes its products.


### Objectives:

   * Validate and analyze billing data.
   * Group billing events to identify patterns.
   * Visualize the results to better understand billing behavior.

### Methodology:

The project was based on the analysis of a billing dataset loaded from an Excel file. An exploratory data analysis (EDA) was performed. Column names were normalized (converted to lowercase and renamed for clarity — e.g., “país” to “pais” and “tamaño” to “tamano”).<br>
A new column was added to extract the billing year.<br>
Invoices were counted by city and by payment method to gain an overall view.<br>
Data was aggregated to compute the total sales by store, by payment method, and by store–payment method combination.<br>
Finally, the aggregated data was exported to an Excel file, and graphical visualizations were created to support the analysis.<br>

### Key Findings:

  * Guadalajara was the city with the highest number of invoices (13,483), followed by Santiago de Chile (13,075) and Buenos Aires (12,344). Mexico City, Bogotá, and Medellín ranked fourth, fifth, and sixth respectively.<br>
  * Four main payment methods were identified: Credit, Debit, Cash, and Nequi.<br>
  * Across all visualizations, a consistent trend emerged showing user preference for card payments. Credit cards were the most used method, closely followed by debit cards. Cash ranked third, and Nequi, a newer payment technology, was the least used.<br>

### Tools & Technologies

  * Python
  * Pandas (data manipulation)
  * Plotly Express (visualization)
  * Openpyxl (Excel file handling)

This analysis provided a clear understanding of billing behavior and customer payment preferences across the company’s locations, serving as a basis for strategic decision-making in sales and marketing.
