# Project Title: Aircraft Risk Analysis Project

## Project Overview
This project aims to analyze aviation risk to support business expansion into the aircraft industry. Our goal is to determine which aircraft models are the lowest risk for purchase and operation. This analysis is driven by aviation accident data sourced from the National Transportation Safety Board (NTSB), covering incidents from 1962 to 2023.
## Business Problem
As part of a diversification strategy, the company is exploring investment in the aviation sector, targeting both commercial and private aircraft markets. However, the company lacks expertise in assessing aviation risks. This project will provide actionable insights to the aviation division head, aiding in identifying the safest aircraft models to minimize operational and financial risk.

## The Data
The dataset used for this project is sourced from the National Transportation Safety Board (NTSB) and contains aviation accident data from 1962 to 2023. This dataset includes information about civil aviation accidents and selected incidents in the United States and international waters.
You can find it from kaggle [here](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses).
### Data Folder Structure
- *data/*
  - aviation_accident_data.csv (or other relevant files)

## Key Points
- The analysis will address missing values,duplicates, data aggregation, and visualization techniques to support data-driven decision-making.
- The final deliverable will include three concrete business recommendations based on the findings from the data analysis.
- Emphasis will be placed on effectively communicating the results and insights to stakeholders, particularly the head of the aviation division.

## Methodology
1. *Data Cleaning*
   - standardized the column names.
   - identified the relevant columns for analysis
   - filled/replaced null values in the relevant columns
   - converted event date to datetime format
   - filtered yer=ar from event date and converted it to numeric type of data
     

2. *Data Analysis*
   - Time Trends: Analyze accident trends over time to identify safer periods of operation
   - Accident Frequency Analysis: Evaluate accident rates per aircraft make
   - Severity Analysis: Assess the severity of accidents across different makes
   - accident rates depending on weather condition

3. *Data Visualization*
   -I created an interactive visualization using Tableau Public that provides insights into evaluating aircraft safety metrics. This dashboard allows users to explore various safety metrics associated with different aircraft dynamically.

You can view the visualization here: [Interactive Dashboard for Evaluating Aircraft Safety Metrics](https://public.tableau.com/app/profile/caren.kyalo/viz/submit_17272715244940/InteractiveDashboardforEvaluatingAircraftSafetyMetrics)

   -The Interactive dashboard presenting the findings. key visualizations include:
   -Accident frequency by aircraft make (bar chart)
   -Trends of accidents over time(line graph)
   Tools used for visualization (e.g., Tableau, Matplotlib).

## Recommendations
1. *Recommendation 1*: we shoud invest in the aviation industry since the number of accidents have reduced with a high percentage in the recent years
2. *Recommendation 2*: The personal flights are the most affected sector in the aviation industry therefore we don't recomment it but rather we can invest in business flights they are not affected more than the personal flights
3. *Recommendation 3*: Cessa make seems to have caused more accidents thus we can recommend makes like Hughes or Boeing to be used since they cause few accidents

## Conclusion
This project delivers a comprehensive risk analysis to support the company’s aviation expansion strategy. It will provide crucial insights into aircraft safety, allowing for well-informed decision-making about which aircraft models to invest in.

## Contact Information
- *Author*: Caren Kyalo
- *Email*: caren.kkyalo@gmail.com
  
