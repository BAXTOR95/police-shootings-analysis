# Police Shootings and Socioeconomic Analysis

## Overview

Today we will do some deep analysis around an incredibly sensitive and politically charged topic. Since Jan. 1, 2015, The Washington Post has been compiling a database of every fatal shooting in the US by a police officer in the line of duty. This repository contains an analysis of this dataset together with US census data on poverty rate, high school graduation rate, median household income, and racial demographics. Our goal is to better understand social trends and what is going on with the fatal use of force by the police in the United States.

## Datasets

1. **Fatal Police Shootings**: A comprehensive database of every fatal shooting in the US by a police officer in the line of duty, compiled by The Washington Post.
2. **US Census Data**:
   - Median Household Income (2015)
   - Percentage of People Below Poverty Level
   - Percentage of People Over 25 Completed High School
   - Racial Demographics by City

## Objectives

- **Data Cleaning**: Handle missing values and duplicates in the datasets to ensure data integrity.
- **Data Integration**: Merge datasets based on common columns to facilitate comprehensive analysis.
- **Exploratory Data Analysis (EDA)**: Visualize relationships between fatal police shootings and socioeconomic factors, identify trends, and understand patterns in the data.

## Analysis

1. **Poverty Rate and Police Killings**:

   - Visualization of poverty rates across US states.
   - Correlation analysis between poverty rates and high school graduation rates.

2. **Racial Demographics and Police Killings**:

   - Visualization of the racial makeup of each US state.
   - Analysis of the distribution of people killed by police by race.

3. **Age and Manner of Death**:

   - Visualization of the age distribution of people killed by police.
   - Analysis of the manner of death, broken down by gender.

4. **Mental Illness and Police Killings**:

   - Analysis of the percentage of people killed by police who have been diagnosed with a mental illness.

5. **Geographic Analysis**:
   - Identification of cities with the highest number of police killings.
   - Analysis of the racial demographics in these cities to calculate the rate of death by race.

## Tools

- **Python**: The primary programming language used for data analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For data visualization.
- **NumPy**: For numerical operations.

## Getting Started

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/BAXTOR95/police-shootings-analysis.git
   cd police-shootings-analysis
   ```

2. **Install Dependencies**:

   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Analysis**:
   Execute the Jupyter notebooks provided in the repository to reproduce the analysis and visualizations.

## Conclusion

This analysis aims to shed light on the intricate relationships between socioeconomic factors and the fatal use of force by police in the United States. By examining these datasets, we hope to provide insights that can inform public policy and contribute to a deeper understanding of this critical issue.
