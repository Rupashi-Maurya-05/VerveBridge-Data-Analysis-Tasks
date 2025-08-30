# Task1- NBA Draft Combine Data Analysis (2009-2017)
Task 1 of vervebridge Internship (August 2024) Data Analytics

**Project Overview:** 
NBA Draft Combine Data Analysis (2009-2017)
This project involves a comprehensive analysis of NBA Draft Combine data from 2009 to 2017, focusing on the physical attributes and performance metrics of draft prospects. The primary goal is to uncover key trends, relationships, and factors that influence the draft position of players.

**Key Metrics:**
-Draft Pick
-Height (No shoes)
-Height (With Shoes)
-Wingspan
-Standing Reach
-Weight
-Vertical (Max)
-Body Fat 
-Agility
-Sprint

**Work Flow:**

1. **Data Collection:** Gathered NBA Draft Combine data from 2009-2017, including physical and athletic measurements of prospects.
2. **Data Cleaning:** Handled missing values, ensured data consistency, and converted columns to numeric types.
3. **Exploratory Data Analysis (EDA):**
   - Performed year-wise trend analysis of average physical metrics.
   - Compared physical features of selected vs. non-selected players.
   - Generated a correlation heatmap to visualize relationships between attributes.
4. **Data Visualization:**
   - Created line plots for year-wise trends.
   - Used regression plots to explore meaningful relationships between physical attributes and draft positions.
   - Generated scatter plots and a pair plot for detailed examination of attribute relationships.
5. **Insights and Interpretation:** Extracted key insights on how physical attributes impacted draft positions and their evolution over time.
6. **Conclusion and Reporting:** Summarized findings on the significance of physical attributes in draft outcomes and trends.

---

# Task2-Big Game Census Data Visualization
 Task 2 of Vervebridge internship Data Analytics
  Here’s a **GitHub README** template for your Power BI project:
## 📊 Project Overview
This project was developed as part of Task 2 for my internship at Vervebridge. The main objective was to analyze NFL player data alongside U.S. Census population estimates to uncover trends and insights related to player birthplaces, success factors, and population-to-player ratios. Using **Power BI**, I created interactive dashboards that provide visual representations of the relationships between player development and geographical population metrics.

## 🚀 Key Metrics & Insights
- **Player Birthplace Trends**: Analyzed the distribution of NFL players across different states to identify top talent-producing regions.
- **Population-to-Player Ratio**: Visualized the ratio of population size to the number of NFL players from each state, offering insights into regions with higher representation in the NFL relative to population size.
- **Success by Geography**: Tracked average years played in the NFL by birthplace, providing a geographical perspective on player success.
- **Geospatial Distribution**: Created a choropleth map to show the distribution of players born across different states, along with their respective population estimates.

## 🔧 Tools & Technologies
- **Power BI**: Main tool for creating dynamic, interactive dashboards and visualizations.
- **Python**: Used for data cleaning, preparation, and additional analysis where necessary.
- **Excel**: Source files for population estimates and player data.

## 🔄 Workflow
1. **Data Collection**: 
   - Two key datasets were used:
     - NFL player data (player birthplaces, positions, and teams)
     - U.S. Census population data (2016 and 2017 estimates for states and places)
   
2. **Data Preparation**:
   - Data was cleaned and transformed to ensure consistency across both datasets (matching state names, removing duplicates, etc.).
   - The datasets were merged on common attributes such as state names and geographic IDs.

3. **Data Visualization**:
   - **Choropleth Maps**: Used to display the distribution of players across the U.S. by state.
   - **Bubble Charts**: Visualized the population-to-player ratio for each state.
  
Here's a template for your GitHub README file that includes a project overview, key metrics, and workflow for your Power BI dashboard project created during your Vervebridge internship:

---

# Task 3- Power BI Dashboard for Vervebridge Internship 

## Project Overview

This project was completed as part of Task 3 of my Data Analyst internship at Vervebridge. The goal of this Power BI dashboard is to provide insightful visualizations that explore the relationships between various attributes in the dataset. The dashboard focuses on analyzing **golden vs. non-golden data points**, **antecedent confidence levels**, and **trusted judgments**, enabling data-driven decision-making and trend analysis.

The dataset includes the following attributes:
- `_unit_id`: Unique identifier for each unit.
- `_golden`: Boolean flag indicating whether the data point is golden.
- `_unit_state`: State of the unit.
- `_trusted_judgments`: Number of trusted judgments.
- `_last_judgment_at`: Timestamp of the last judgment.
- `antecedent`: Antecedent variable.
- `antecedent:confidence`: Confidence level of the antecedent.
- `orig_antecedent`: Original antecedent value.
- `antecedent_gold`: The golden antecedent value.

## Key Metrics

The dashboard highlights several important metrics and trends, including:
- **Total Golden Data Points**: The count of data points labeled as golden.
- **Total Non-Golden Data Points**: The count of non-golden data points.
- **Overall Average Antecedent Confidence**: The average confidence level for all antecedent values.
- **Average Antecedent Confidence for Golden Data**: The average confidence specifically for golden data points.
- **Average Antecedent Confidence for Non-Golden Data**: The average confidence for non-golden data points.
- **Trusted Judgments**: The total number of trusted judgments in the dataset.
- **Trend Analysis**: Visualization of how antecedent confidence levels change over time.

## Dashboard Features

The Power BI dashboard includes the following visualizations:
1. **Trend Analysis (Trend Axis)**: A line chart that visualizes changes in average antecedent confidence over time.
2. **Distribution Insights**:
   - **Pie Charts**: Show the proportion of golden vs. non-golden data points.
   - **Bar Charts**: Compare the average confidence levels of golden and non-golden data points.
3. **Scatter Plot**: Visualizes the relationship between trusted judgments and antecedent confidence.
4. **Heatmap**: Shows the correlation between different attributes like antecedent confidence and trusted judgments.

## Workflow

The following steps outline the process of building the dashboard:

1. **Data Import**: Imported the dataset into Power BI from CSV format.
2. **Data Cleaning**: Reviewed and cleaned the dataset for any inconsistencies.
3. **Measure Calculation**:
   - Created custom DAX measures to calculate key metrics like `TotalGoldenDataPoints`, `AverageConfidenceGolden`, and `OverallAverageConfidence`.
4. **Visualization**: Built various visualizations to represent key insights, including trend lines, pie charts, and bar charts.
5. **Dashboard Design**: Organized visualizations into a clean, user-friendly dashboard for easy exploration.
6. **Analysis**: Performed analysis of the visualized data to identify patterns, trends, and anomalies in the dataset.

## Tools & Technologies Used

- **Power BI**: Primary tool for data visualization and dashboard creation.
- **DAX (Data Analysis Expressions)**: Used for creating custom measures and calculations.
- **Dataset**: Provided by Vervebridge, focusing on golden and non-golden data points, antecedent confidence, and trusted judgments.

## Conclusion

This project provided valuable experience in data analysis and dashboard creation, enhancing my skills in Power BI and DAX. The dashboard offers a comprehensive view of the dataset, enabling users to understand trends and relationships between key metrics.

Feel free to explore the dashboard and reach out with any feedback or questions!
