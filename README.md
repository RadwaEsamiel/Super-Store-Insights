# Super-Store-Insights
Super Store Insights
Tableau Super Store Project


Project Overview
This project is a Tableau-based data visualization suite designed to analyze the performance of the Super Store dataset. It includes multiple dashboards for analyzing key performance indicators, performance trends, and top sales metrics.

General Requirements
- All dashboards are sized to "Automatic" to ensure flexibility across different devices.
- Preferred usage of containers to organize dashboard components.
- A designated filter pane for user interaction.
- Proper formatting with a focus on clarity and readability.
- Borders are added for all charts and panes to maintain consistency.

Overview Dashboard
Requirements
- Filters: The dashboard must have three filters: `KPI`, `Year`, and `State`.
- Design:
  - Each tile has a grey border.
  - Each tile contains:
    - A dynamic title.
    - A dynamic measure (Sales, Profit, Quantity).
    - A separator line.
    - Change percentage for the selected year compared to the previous year.
    - A dynamic sentence indicating "Growth" or "Decline" compared to the previous year.
- Filters: Only data from the United States is used.
- Segment-based Tiles: The three lower tiles are filtered by segments: Consumer, Corporate, Home Office.

Performance Dashboard
Requirements
- Filters: The dashboard must have six filters: `KPI`, `Year`, `State`, `Segment`, `Category`, and `Sub-Category`.
- Design:
  - Grey borders are added to each chart.
  - **Chart #1**: A dynamic monthly trend for several measures.
  - **Chart #2**: Order priority distribution by several measures.
  - **Chart #3**: Ship mode distribution by several measures.
  - Each chart has:
    - A dynamic title (bold) based on the selected measure and year.
    - Removal of grid lines for a cleaner look.
    - An average line with value labels.

 Top 10 Dashboard
Requirements
- Filters: The dashboard has four filters: `Year`, `Segment`, `Category`, and `Sub-Category`.
- Design:
  - Grey borders for all charts.
  - Chart #1: Top 10 countries by sales.
  - Chart #2: Top 10 states by sales based on the selection in Chart #1.
  - Removal of grid lines for a cleaner design.


Through Tableau Desktop or Tableau Public Connect the workbook to the appropriate dataset.

Usage and Interaction
To use the dashboards:
1. Select the desired filters to customize the visualizations.
2. Interact with the charts to explore data trends and insights.
3. Observe the dynamic changes based on your selections.

Contributing
Contributions to this project are welcome. If you have suggestions or improvements, please submit a pull request with a detailed description of your changes.


