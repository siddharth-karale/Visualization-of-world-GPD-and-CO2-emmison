# World GDP and CO2 Emission Visualization

This project explores the World Development Indicators dataset from the World Bank to visualize the relationship between CO2 Emissions and GDP (Gross Domestic Product) per capita in the United States.

## Data Source

The data source is the World Development Indicators dataset obtained from the World Bank, containing economic development indicators for various countries.

## Libraries Used

* pandas
* numpy
* matplotlib.pyplot

## Script Overview

1. **Loads the Dataset:** Reads the compressed data file (`data/Indicators.bz2`) using pandas.
2. **Initial Exploration:** Analyzes the dataset's shape, sample data, columns, unique entries for countries, country codes, indicators, and years.
3. **Data Visualization:** 
    * Focuses on CO2 emissions per capita for the USA.
    * Creates line plots to visualize CO2 emission changes over time.
    * Creates histograms to explore the distribution of CO2 emission values.
    * Analyzes the relationship between GDP per capita and CO2 emissions using scatter plots and correlation coefficients.

## Running the Script

1. Save the script as a Python file (e.g., `SATELLITE IMAGE DATA ANALYSIS.ipynb`).
2. Install the required libraries (`pandas`, `numpy`, `matplotlib`) using `pip install pandas numpy matplotlib`.
3. Run the script from the command line: `SATELLITE IMAGE DATA ANALYSIS.ipynb`.

This script provides a basic exploration of the World Development Indicators dataset, focusing on visualizing CO2 emissions and GDP per capita in the United States. Further analysis can involve comparing these indicators across different countries or exploring additional indicators from the dataset.
