# 🥇 Olympics Data Analysis

## Overview
This project analyzes Olympic Games data to uncover trends, statistics, and insights about athlete performances, medal distributions, and more. The analysis utilizes various Python libraries for data manipulation, visualization, and statistical analysis.

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Commit History](#commit-history)

## Introduction
The Olympics are a global phenomenon, showcasing athletic prowess from countries worldwide. This analysis aims to explore the data behind the Games, including the performance of countries, athletes, and sports over the years.

## Data Source
The data for this analysis is sourced from [Olympics Data](https://docs.google.com/spreadsheets/d/1LLEn6EnPYKO_2MqUeLneupb9oZixd15ychQ9Bj5SkNI/edit?usp=sharing)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis
This project includes various stages of data analysis to uncover insights from the Olympics data:

**5-Point Statistical Summary:** Provided a summary for all columns in the dataset to understand the central tendency and dispersion.

**Handling Missing Values:** Filled missing values using the mean for numerical columns and median for text-based columns.

**Correlation Analysis:** Analyzed relationships between numerical variables, such as age, height, and weight, to identify significant associations.

**Medal Counts:** Investigated the total number of medals won by each country and gender.

**Event Performance:** Explored participation and medal trends across different sports.

**Gender-Based Analysis:** Assessed the relationships between age, weight, and height, focusing on differences between male and female athletes.

**Time Trends:** Examined how athlete characteristics, performance, and medal distributions have evolved over time.

## Visualizations
The analysis features several visualizations to illustrate key insights:

**Bar Charts:**
- Medal counts by country, gender, and sport.
  
**Pie Charts:**
- Gender distribution of athletes.
- Sentiment analysis based on the number of medals won (0, 1, or more than 2).
  
**Box Plots:**
- Age, height, and weight distributions, with outlier detection.
  
**Scatter Plots:**
- Relationships between age and weight, and height and weight, for male, female, and combined athletes.
- Specific scatter plots for gymnastics and weightlifting to highlight differences in body types.
  
**Heatmap:**
- Correlation matrix to visualize relationships between numerical variables.
  
**Line Plot:**
- Yearly trends in the average height of athletes by gender.
  
# Conclusion
The analysis led to several important insights:

**Athlete Characteristics:**
The average height and weight of male athletes are generally higher than those of female athletes, with a noticeable gap in weight.

**Medal Counts:**
Both male and female athletes have earned a similar number of medals, with only slight differences.

**Trends Over Time:**
An overall increase in the average height of athletes was observed from the 1960s to the 2010s, with male athletes consistently taller than female athletes.
After 1990, the height of female athletes showed more fluctuations, while male heights stabilized around 180 cm.

**Sport-Specific Insights:**
Gymnasts tend to be shorter and lighter, with distinct differences between male and female athletes.
Weightlifters display a broader range of body sizes, with more overlap between genders.

## Commit History
Below is an overview of the commit history and important changes:

**Initial Setup:**

  - "Initial commit: Added Olympics data analysis notebook"
  - "Upload initial analysis script for Olympics data"

 **Data Cleaning and Preprocessing:**
 
  - "Performed data cleaning: filled missing values in 'Height' column"
  - "Cleaned dataset by handling missing data and outliers"

  **Data Analysis:**
  
  - "Analyzed medal counts by country"
  - "Explored trends in athlete performance over the years"
    
  **Visualizations:**
  
  - "Added visualizations for medal distribution by country"
  - "Created line chart showing performance trends over time"

  **Finalizing the Project:**
  
  - "Completed data analysis and added conclusions"
  - "Finalized notebook with insights and visualizations"

## View Code - [Olympics Data Analysis](Olympics Data Analysis.ipynb](https://github.com/sakhi3008/Olympics-Data-Analysis/blob/main/Olympics_Data_Analysis.ipynb)
