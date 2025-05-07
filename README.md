# Fuel Economy Analysis (2008 vs. 2018)

## Overview

This project analyzes trends in vehicle fuel economy and related factors between 2008 and 2018.  The analysis uses a dataset of vehicle information to understand how fuel efficiency has changed over this period, the factors influencing those changes, and the implications for emissions and the automotive industry.

## Project Goals

* Determine the overall change in fuel economy between 2008 and 2018.
* Analyze shifts in the distribution of fuel economy values.
* Examine changes in fuel type proportions over time.
* Investigate how vehicle class distributions have evolved.
* Assess fuel economy and emission trends within specific vehicle classes.
* Evaluate the impact of "SmartWay" certification on fuel economy and emissions.
* Explore how the relationships between engine size, MPG, and emissions have changed.

## Data Source

The data for this project comes from a dataset containing vehicle information for the years 2008 and 2018.  ( *Add specific source and details here* )

## Methods

The analysis involves the following steps:

1.  **Data Loading and Inspection:**
    * Loading the 2008 and 2018 datasets using pandas.
    * Inspecting the data structure and key variables.
    * Cleaning the data as necessary (e.g., handling missing values).

2.  **Exploratory Data Analysis (EDA):**
    * Calculating descriptive statistics for MPG in 2008 and 2018.
    * Visualizing the distribution of MPG for each year using histograms.
    * Analyzing the distribution of vehicle classes in 2008 and 2018.
    * Examining the proportions of different fuel types in each year.

3.  **Comparative Analysis:**
    * Calculating the overall MPG improvement from 2008 to 2018.
    * Comparing MPG distributions between the two years.
    * Analyzing changes in fuel type proportions.
    * Comparing vehicle class distributions.
    * Analyzing MPG and emission trends within specific vehicle classes.
    * Evaluating the impact of SmartWay certification.
    * Analyzing correlation between variables

4.  **Visualization:**
    * Creating bar charts to compare MPG, fuel type proportions, and vehicle class distributions.
    * Generating histograms to visualize MPG distributions.
    * Producing correlation matrix heatmaps to show relationships between variables.

## Key Findings

* Overall MPG improved from 2008 to 2018.
* The distribution of MPG shifted towards higher values in 2018.
* Alternative fuels gained market share, while gasoline's share decreased.
* Vehicle class preferences shifted, with increased popularity of small and midsize cars.
* Most vehicle classes showed improved fuel economy and reduced emissions.
* The relationship between engine size and MPG weakened slightly.
* The correlation between MPG and low greenhouse gas emissions strengthened.

## Report Structure

The analysis is presented in a report with the following structure:

1.  Introduction
2.  Key Findings
3.  Detailed Analysis
    * Analysis of 2008 and 2018 Datasets Separately
    * Analysis of Combined Dataset
4.  Conclusion
5.  Limitations
6.  Further Research
7.  Appendix: Visualizations

## Code

The analysis is conducted using Python with the following libraries:

* pandas
* matplotlib
* seaborn

The code files for this project are located in fuel_eco_analysis.ipynb.

## Visualizations

The report includes the following visualizations:

* Overall MPG Improvement (2008 vs. 2018) - Bar Chart
* Distribution of MPG in 2008 and 2018 - Histograms
* Fuel Type Proportions (2008 and 2018) - Bar Chart
* Vehicle Class Distribution (2008 and 2018) - Bar Chart
* Average MPG by Vehicle Class (2008 vs. 2018) - Bar Chart
* SmartWay Vehicle Proportions (2008 and 2018)
* Correlation Matrix (2008) - Heatmap
* Correlation Matrix (2018) - Heatmap

## Results

The results of this analysis provide insights into the trends in vehicle fuel economy between 2008 and 2018.  The findings suggest that fuel efficiency has improved, driven by technological advancements, the adoption of alternative fuels, and shifts in vehicle preferences.  These changes have implications for reducing emissions and potentially lowering fuel costs.

## Future Work

Further research could explore the impact of specific technologies, analyze economic factors influencing vehicle choices, and investigate the effectiveness of government regulations.
