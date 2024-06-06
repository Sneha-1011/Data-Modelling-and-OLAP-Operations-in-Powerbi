# Data Modelling and OLAP Operations Project

## Overview

This project showcases data modeling and OLAP (Online Analytical Processing) operations using Power BI and Python. Power BI is employed for data modeling, and Python scripts are integrated within Power BI to perform various OLAP operations such as slicing, dicing, drilling down, rolling up, and creating pivot tables.

## Project Structure

- **Data Modeling**: Implemented in Power BI.
- **OLAP Operations**: Implemented in Python and integrated with Power BI.

## Features

### Data Modeling in Power BI:

- Importing and transforming data from multiple sources.
- Establishing relationships between tables.
- Creating measures and calculated columns for analysis.

### OLAP Operations with Python:

- **Drill Down and Roll Up**: View transaction dates by specific times for a particular city.
- **Slicing**: Display transaction amounts by transaction type when the amount exceeds 100.
- **Dicing**: Display transaction amounts with transaction type if the type is 1 and Location is 007, and show a frequency table of transactions.
- **Pivot Table**: Columns are Gender and Account Type, rows are Quarter, and values are Transaction Amount.

## Getting Started

### Prerequisites

- Power BI Desktop
- Python 3.x
- Pandas, Matplotlib, Seaborn libraries for Python

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. **Install Python Libraries**:
    ```bash
    pip install pandas matplotlib seaborn
    ```

3. **Open the Power BI file**:
    - Open the Power BI Desktop.
    - Load the provided Power BI (.pbix) file.

4. **Configure Python Scripting in Power BI**:
    - Go to **File > Options and settings > Options**.
    - Under **Global**, select **Python scripting**.
    - Set the path to your Python executable.

5. **Run Python Scripts in Power BI**:
    - Use the Python visual in Power BI to run the provided Python scripts for OLAP operations.

## Usage

- **Data Modeling**:
    - Use Power BI to explore data relationships, create measures, and visualize data.
- **OLAP Operations**:
    - Use the integrated Python scripts within Power BI to perform slicing, dicing, drilling down, rolling up, and generating pivot tables.


## Acknowledgements

- Thanks to the Power BI and Python communities for their amazing tools and support.
