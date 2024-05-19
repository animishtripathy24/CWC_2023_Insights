
# ODI World Cup 2023 Analysis
## Overview

This project aims to analyze the performances of players in the ODI World Cup 2023 using a comprehensive dataset. The analysis includes data cleaning, transformation, and visualization. The goal is to select a "Dream Team" of the 11 best players based on their performances.An interactive dashboard was created in Power BI to visualize key insights, including top batsmen and bowlers.


## Dataset
The dataset used for this analysis contains detailed information about each match, including batting and bowling performances. The columns in the dataset include:

`Match_no`, `Match_Between_bat`, `Team_Innings`, `Batsman_Name`, `Batting_Position`, `Dismissal`, `Runs_bat`, `Balls`,`4s`, `6s`,`Strike_Rate`, 
`Match_Between_bowl`, 
`Bowling_Team`, 
`Bowler_Name`,
`Overs`, 
`Maidens`,
`Runs_bowl`, 
`Wickets`, 
`Economy`, 
## Steps Involved
### 1. Data Upload
- **CSV File**: The dataset was provided in a CSV file format.

### 2. Data Cleaning
- **Removing Null Values**: Ensured no null values were present in critical columns.
- **Correcting Data Types**: Verified and corrected data types for each column:
  - `Match_no`: Integer
  - `Match_Between_bat`, `Team_Innings`, `Batsman_Name`, `Dismissal`, `Match_Between_bowl`, `Bowling_Team`, `Bowler_Name`: Text
  - `Batting_Position`, `Wickets`: Integer
  - `Runs_bat`, `Balls`, `4s`, `6s`, `Strike_Rate`, `Overs`, `Maidens`, `Runs_bowl`, `Economy`: Numerical

### 3. Data Transformation
- **Calculated Columns**: Created additional columns such as `Strike Rate` for batsmen using `Pandas DataFrame`
- **Filtering Irrelevant Data**: Removed rows with zero or non-sensical values in key performance metrics.

### 4. Data Analysis
- **Top Performers**: Identified top batsmen and bowlers based on various metrics such as `Runs Scored`, `Strike rate`, `Wickets Taken`, and `Economy Rate`
- **Dream Team Selection**: Based on performance metrics such as `Runs Scored`, `Strike rate`, `Wickets Taken`, and `Economy Rate`, the best 11 players were selected.

### 5. Interactive Dashboard in Power BI
- **Visualization Types**:
  - **Stacked Bar Plot for Batsmen**: Plotted top 5 batsmen with the best `strike rate` and `run scored`.
  - **Donut Chart for Bowlers**: Plotted bowlers with the `most wickets` and the most `economical bowlers`.

#### Dashboard Features
- **Slicers for Interactivity**: Added `slicers` for filtering data by `batsman name`, and `bowler name`.
- **Formatted Visuals**: Enhanced readability with appropriate titles, colors, and tooltips.
## Dream Team of 11 players Selection Criteria
### Dream Team Selection Criteria
1. **Batsmen**:
        - High total runs
        - High strike rate

2. **Bowlers**:
        - Most wickets taken
        - Low economy rate

### Dream Team Composition
1.  **Batsmen**:
        - Selected based on the highest runs and strike rates.

2.  **Bowlers**:
        - Selected based on the highest wickets and best economy rates.

3.  **All-Rounders**:
        - Selected based on the most wickets and best strike rates.
## Tech Stack and Libraries Used
| Technology   | Libraries           |
|--------------|---------------------|
| Data Upload  | Excel               |
| Data Cleaning| Pandas              |
| Data Analysis| Matplotlib, Seaborn |
| Visualization| Power BI            |

## Description

- **Data Upload (Excel)**: Excel was used for data upload and initial data exploration.
- **Data Cleaning (Pandas)**: Pandas, a powerful data manipulation library in Python, was used for data cleaning and transformation tasks. It allowed for efficient handling of datasets and easy filtering and manipulation of data.
- **Data Analysis (Matplotlib, Seaborn)**: Matplotlib and Seaborn were used for data analysis and visualization. Matplotlib is a comprehensive library for creating static, interactive, and animated visualizations in Python. Seaborn is built on top of Matplotlib and provides a high-level interface for drawing attractive and informative statistical graphics.
- **Visualization (Power BI)**: Power BI was used for creating interactive and dynamic dashboards for visualizing insights derived from the data. It offers a wide range of visualization options and allows for easy sharing and collaboration.
## Conclusion
The project provided valuable insights into player performances during the ODI World Cup 2023. The interactive Power BI dashboard offers an easy-to-understand visualization of key metrics, helping in the identification of top performers and selection of a dream team.
## Screenshots

![output](https://github.com/animishtripathy24/ODI_WORLD_CUP_2023_ANALYSIS/assets/135792519/add81992-a306-4d52-85cc-48d9c9437820)

![output](https://github.com/animishtripathy24/ODI_WORLD_CUP_2023_ANALYSIS/assets/135792519/9d9c07d3-a924-4483-9c1e-38f104669f2b)

![output](https://github.com/animishtripathy24/ODI_WORLD_CUP_2023_ANALYSIS/assets/135792519/9c00cd4a-2ed0-473b-aec5-fb903371da1d)

