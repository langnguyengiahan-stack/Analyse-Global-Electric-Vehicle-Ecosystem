# Analyse-Global-Electric-Vehicle-Ecosystem

## Overview
This project performs an initial exploratory data analysis (EDA) and summary of multiple datasets related to the Electric Vehicle (EV) ecosystem. The accompanying Jupyter Notebook loads several data files, calculates their dimensions, verifies data quality, and generates a visual size comparison [cite: 1].

## Datasets
The analysis processes the following six CSV files:
* `EV_Vehicles.csv`: Details on individual EV vehicles (5,000 records). [cite: 1]
* `Consumer_Reviews.csv`: Consumer feedback and reviews (5,000 records). [cite: 1]
* `Charging_Stations.csv`: Location and specifications of EV charging stations (1,000 records). [cite: 1]
* `vehicle_models.csv`: Specific EV model information (30 records). [cite: 1]
* `manufacturers.csv`: Data on EV manufacturers (25 records). [cite: 1]
* `countries.csv`: Country-level geographic or market data (15 records). [cite: 1]

## Data Quality Summary
A programmatic data quality check was executed across all tables to identify structural metrics, missing values, and duplicate entries. The datasets are remarkably clean, containing exactly zero missing values and zero duplicate rows across all files [cite: 1].

| Dataset | Rows | Columns | Duplicate Rows | Missing Values |
| :--- | :--- | :--- | :--- | :--- |
| **vehicles** | 5,000 | 20 | 0 | 0 |
| **consumer** | 5,000 | 20 | 0 | 0 |
| **stations** | 1,000 | 16 | 0 | 0 |
| **models** | 30 | 9 | 0 | 0 |
| **manufacturers** | 25 | 5 | 0 | 0 |
| **countries** | 15 | 12 | 0 | 0 |

## Visualizations
The notebook generates a styled summary table (utilizing a blue gradient color map for dataset dimensions) and a horizontal bar chart visualizing the volume of records for each dataset, sorted in descending order [cite: 1].

## Dependencies
To execute the notebook, ensure you have the following Python libraries installed [cite: 1]:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `statistics`

## Usage
1. Ensure all six CSV files are placed in the same directory as the `.ipynb` file.
2. Run the Jupyter Notebook cells sequentially to load the datasets into a dictionary, generate the summary statistics, and render the size comparison bar chart.
README.md
Displaying README.md.
