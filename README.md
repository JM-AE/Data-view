# Data Handling Dashboard

## Overview

The Data Handling Dashboard is a first view Python application built with Tkinter that provides basic data analysis and visualization capabilities. 
This tool allows users to load, explore, manipulate, and visualize data from CSV and Excel files with an graphical interface.

## Features

### Data Loading
- Support for CSV and Excel file formats
- Easy file selection through a file dialog
- Automatic column detection and dropdown population

### Data Display
- Raw data view with scrollable treeview
- Comprehensive data description tab
  - DataFrame shape
  - Column data types
  - Missing value counts
  - Statistical summary

### Data Manipulation
- Missing value handling:
  - Drop missing values (entire DataFrame or specific columns)
  - Fill missing values (with custom values)

### Data Visualization
Supported visualizations:
- Histogram with density curve
- Pie Chart
- Correlation Matrix
- Cluster Map

## Prerequisites

Before running the application, ensure you have the following Python libraries installed:

- tkinter
- pandas
- numpy
- matplotlib
- seaborn
- scipy


You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/data-handling-dashboard.git
```

2. Navigate to the project directory:
```bash
cd data-handling-dashboard
```

3. Run the application:
```bash
python data_dashboard.py
```

## How to Use

### Loading Data
1. Click "Load Data" button
2. Select a CSV or Excel file
3. Data will automatically populate in the Raw Data and Description tabs

### Data Manipulation
1. Choose a manipulation type (dropna or fillna)
2. Optionally select a specific column
3. For fillna, enter a fill value
4. Click "Execute Manipulation"

### Data Visualization
1. Select a visualization type from the dropdown
2. Choose a column (if required)
3. Click "Generate Plot"

### Resetting
- Click the "Reset" button to clear all data and reset the interface

## Example Use Cases

- Financial data analysis
- Scientific research data exploration
- Business performance reporting
- Academic data visualization

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open-source. Please check the LICENSE file for details (tba).

## Contact

For questions or support, please open an issue in the GitHub repository.
