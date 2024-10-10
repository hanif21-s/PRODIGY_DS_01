# Power BI Project - Population Visualization

## Description

This project visualizes **population data** from various countries over several decades using Power BI. The data comes from the **World Bank** and contains information on population from 1960 to 2023. The goal is to provide insights into demographic growth trends across different countries, with interactive filtering options based on countries and years.

The dataset has been **prepared** to facilitate visualization by reorganizing the columns to better leverage the data for various interactive visualizations.

## Dataset

The dataset used in this project is sourced from [World Bank Population Data](https://data.worldbank.org/indicator/SP.POP.TOTL) and contains the following columns:
- `Country Name`: The name of each country.
- `Country Code`: The unique code for each country.
- `Indicator Name`: Name of the indicator (here, total population).
- `Indicator Code`: The unique code for the indicator.
- Annual columns (1960 - 2023): Each column represents the population for a specific year.

## Data Preparation

Before proceeding with the visualizations, the data was transformed and reorganized. I modified the structure to obtain more suitable columns for analysis, such as **country names**, **years**, and **populations**. This allowed me to use the data effectively in interactive charts and apply relevant filter segments.

## Visualizations Created

1. **Stacked Bar Chart**:
   - Represents populations based on countries.
   - **X-Axis**: Population.
   - **Y-Axis**: Countries.
   - **Year Filtering**: I added a **segment** that allows filtering the visualization by a specific year or range of years.

2. **ArcGIS Map**:
   - A map displaying the population of countries with bubbles proportional to the population size.
   - **Location**: Countries.
   - **Bubble Size**: Sum of the population.
   - Year filtering using a **segment** that allows selecting year ranges.

3. **Line Chart**:
   - Represents the evolution of the population over the years for each country.
   - **X-Axis**: Years.
   - **Y-Axis**: Population.
   - **Filtering**: I added a **segment** to filter the data by country and year range.

4. **Table**:
   - Displays the following columns:
     - `Country`: The name of the country.
     - `Average Population`: The average population over the years.
     - `Most Recent Year`: The most recent year in the data.
     - `Most Recent Population`: The population corresponding to the most recent year.
     - **Sparkline**: A line chart showing the population evolution for each country over all available years.
