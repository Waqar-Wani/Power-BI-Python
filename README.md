# Power-BI-Python
I developed this project entirely myself

# HR Attrition Analysis Dashboard

## Overview

This project is an HR Attrition Analysis Dashboard created using Power BI and Python. The dashboard provides insights into employee attrition over the years at a company, segmented by different departments. The visualizations include line charts with data annotations, filtered data views, and more.

## Features

- **Interactive Line Chart**: Visualizes attrition counts over the years with an orange line and data annotations.
- **Dynamic Filtering**: Utilizes Power BI slicers to filter data by department and other criteria.
- **Data Cleaning and Transformation**: Data preparation using Power BI's data cleaning tools and DAX queries.
- **Python Integration**: Enhanced visualization using Python scripts for custom charting.

## Tools and Technologies

- **Power BI**: For data visualization, cleaning, and transformation.
- **Python**: For custom visualizations using Matplotlib and Pandas.
- **DAX (Data Analysis Expressions)**: For creating calculated columns and measures in Power BI.
- **Power BI Slicers**: For dynamic data filtering and interaction.

## Data Cleaning and Transformation

1. **Data Import**: Imported the HR dataset into Power BI.
2. **Data Cleaning**: Used Power BI's data cleaning tools to handle missing values, remove duplicates, and normalize data.
3. **DAX Queries**: Created calculated columns and measures to aggregate data and calculate metrics such as AttritionCount.

## Slicers

I created four slicers to allow dynamic filtering of the data:

1. **Select All at Once**: A general slicer for overall data.
2. **Human Resources**: Filters data for the HR department.
3. **Research and Development**: Filters data for the R&D department.
4. **Sales**: Filters data for the Sales department.

## Python Visualization

The line chart visualization was created using Python to provide more customization options than Power BI's built-in charts. The Python script accesses the dataset, applies necessary filters, and generates a line chart with data annotations, removing grid lines and adding color to specific areas for better visual effect.

### Notes on Python Visualization

- The Python script runs every time you need to update the visualization, unlike native Power BI visuals that update automatically.
- Adjusting the script or dataset requires rerunning the Python script in Power BI.

## Conclusion

This project showcases the integration of Power BI's robust data processing and visualization capabilities with Python's advanced charting options. The dashboard provides a comprehensive view of HR attrition data, enabling better decision-making through interactive and dynamic visualizations.

## How to Run

1. **Load Dataset**: Ensure the dataset is loaded into Power BI.
2. **Apply DAX Queries**: Use the provided DAX queries to prepare the data.
3. **Configure Slicers**: Set up slicers for dynamic data filtering.
4. **Run Python Script**: Use the Python script in the Python visual in Power BI to generate the custom line chart.

