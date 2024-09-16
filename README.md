# Analyzing the Impact of Recession on Automobile Sales
### Dataset
The dataset used in this project is artificially created and includes the following variables:

* Date: The date of the observation.
* Recession: A binary variable indicating recession period (1 means recession, 0 means normal).
* Automobile_Sales: The number of vehicles sold.
* GDP: The per capita GDP value in USD.
* Unemployment_Rate: The monthly unemployment rate.
* Consumer_Confidence: A synthetic index representing consumer confidence.
* Seasonality_Weight: The weight representing the seasonality effect on automobile sales.
* Price: The average vehicle price during the period.
* Advertising_Expenditure: The advertising expenditure of the company.
* Vehicle_Type: The type of vehicles sold (Supperminicar, Smallfamilycar, Mediumfamilycar, Executivecar, Sports).
* Competition: A measure of competition in the market.
* Month: Month of the observation, extracted from Date.
* Year: Year of the observation, extracted from Date.
  
### Project Overview
This project is divided into two main parts:

#### Part 1: Visualizations using Matplotlib, Seaborn, and Folium
The goal of this part is to analyze historical trends in automobile sales during recession periods using Matplotlib, Seaborn, and Folium.

Tasks:
* Line Chart: Show how automobile sales fluctuate year by year.
* Vehicle Type Analysis: Plot different lines for vehicle categories and analyze trends during recession periods.
* Comparison of Recession and Non-Recession Periods: Using Seaborn to visualize.
* GDP Subplots: Compare GDP variations during recession and non-recession periods.
* Bubble Chart: Display the impact of seasonality on automobile sales.
* Scatter Plot: Identify the correlation between vehicle price and sales volume during recessions.
* Pie Chart: Display the portion of advertising expenditure during recession and non-recession periods.
* Pie Chart by Vehicle Type: Show advertising expenditure per vehicle type during the recession period.
* Line Plot on Unemployment Rate: Analyze the effect of the unemployment rate on vehicle sales by type during recessions.

#### Part 2: Creating an Interactive Dashboard with Plotly and Dash
In this part, an interactive dashboard was developed using Plotly and Dash to allow directors to select specific years or categories for detailed analysis.

Tasks:
* Creating the Dashboard: Give the Dash application a meaningful title.
* Dropdown Menus: Add dropdown menus for user interaction.
* Output Division: Create a division for output display.
* Callbacks: Define the callback function to update the graphs based on user selection.
* Recession Report Graphs: Display key statistics for the recession report.
* Yearly Report Graphs: Display key statistics for the yearly report.

#### Dashboard Results
Yearly Report Graph
![YearlyReportgraphs](https://github.com/user-attachments/assets/00fb8c6f-98d4-413e-910f-a5bfbf80cf7e)

Recession Report Graph
![RecessionReportgraphs](https://github.com/user-attachments/assets/90101f86-4cdb-4da9-adf9-bb55b2d2d060)


