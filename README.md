# Luxury Loan Dashboard
## Overview
This dashboard provides an analysis of bank loans in New York, specifically focusing on a luxury loan portfolio. It displays key metrics, line plots, and visualizations related to loan data. The data is sourced from a CSV file and includes information such as loan ID, funded amount, funded date, purpose, and duration months.

## Getting Started
### Prerequisites
- Python 3.x
- Dash library
- Pandas library
- Plotly Express library

## Installation
1. Install dependencies:
```
pip install dash pandas plotly
```
2. Run the application:
```
python app.py
```

## Dashboard Layout
### Metrics Scorecards
Total User
- Displays the total number of unique users with loans.
Total Approved Amount
- Displays the total funded amount of approved loans.

### Date Range Selection
Use the Date Picker Range to select a specific time period for analysis.

### Line Plot
Displays a line plot showing the total sum of payments (in months) over the selected date range.

### Graphs
Distribution of Individual Loan Purpose
- Bar chart showing the distribution of individual loan purposes.
Loan Duration Proportion (Pie Chart)
- Pie chart displaying the proportion of loan durations in months.
