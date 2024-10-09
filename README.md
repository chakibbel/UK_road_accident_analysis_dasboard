# Road Accidents Data Analysis and Dashboard

This project involves a detailed analysis of road accidents in the UK, with both a Power BI dashboard and Python analysis (in Jupyter notebook) to ensure accuracy and insights. The Power BI report visualizes key metrics, trends, and comparisons, while the Python analysis serves as a quality control (QC) to verify the results. 

## Project Overview

This project is divided into two main parts:

1. **Python Analysis (Jupyter Notebook)**
   - A detailed data analysis was conducted to verify the data.
   - Quality checks were applied on the calculations and results shown in the Power BI report.
   - Python visualizations, including accident location maps and casualties data by region, were created to cross-verify the dashboard insights.
   
2. **Power BI Dashboard**
   - An interactive dashboard was created to provide a comprehensive view of road accidents in the UK, highlighting key metrics and trends.
   - Key performance indicators (KPIs) such as accident count, casualty count, and percent changes year over year are displayed for easy interpretation.

## Data

The dataset used for this analysis contains the following columns:
- **Latitude**: Latitude of the accident location.
- **Longitude**: Longitude of the accident location.
- **Local_Authority_(District)**: The district where the accident occurred.
- **Number_of_Casualties**: The total number of casualties in the accident.
- **Vehicle_Type**, **Road_Type**, and **Period_of_Day**: Additional attributes describing the accident.

### Key Analytical Steps

#### Python Analysis
- **Data Cleaning & Transformation**: The dataset was cleaned for missing values and consistency across records.
- **Geospatial Visualization**: Accident locations were mapped using Folium, and casualty counts were visualized using proportional markers.
- **Aggregations**: Accident data was aggregated by district to calculate the total casualties per region.
- **Cross-Verification**: Calculations and trends in the Power BI dashboard were verified using Python-based analysis.

#### Power BI Dashboard
- **KPI Metrics**:
  - **Accident Count (Current Year)**: The total number of accidents that occurred during the current year.
  - **Casualty Count (Current Year)**: The total number of casualties for the current year.
  - **Percent Change**: Year-over-year comparison showing the percentage increase or decrease in accident and casualty numbers.

- **Monthly Accident Trend**:
  - A line chart visualizing the trend of accidents per month for each year, helping to identify seasonal patterns or trends.

- **Vehicle Type and Road Type Breakdown**:
  - Accidents are aggregated by vehicle type (car, bike, van, etc.) and road type (urban, rural, highway), showing which vehicles are involved in more accidents and the road types that are prone to accidents.

- **Period of the Day**:
  - Analysis of accidents based on the time of day (morning, afternoon, evening, night), which highlights the periods with the highest number of incidents.

## Files in this Repository

- **Jupyter Notebook (`road_accidents_analysis.ipynb`)**: Contains the Python code for data analysis, aggregation, and verification.
- **Power BI Dashboard (`Road_Accident_Dashboard.pbix`)**: Interactive dashboard showing key insights from the road accident data.
- **README.md**: This file, providing an overview of the project.

## Technologies Used

- **Python**: pandas, folium, matplotlib
- **Power BI**: For creating the interactive dashboard
- **Jupyter Notebook**: For conducting data analysis and QC checks

## Insights and Results

- **Accident Count & Casualties**: Analyzed yearly accident and casualty numbers with year-over-year percent change to understand the progression of accidents.
- **Monthly Trends**: The monthly trend analysis helped identify peak periods for road accidents and track changes across different years.
- **Vehicle and Road Type Insights**: The data highlighted which vehicle types and road types were more prone to accidents, providing a focused view of risk areas.
- **Time of Day Patterns**: The distribution of accidents over the day revealed high-risk periods, which can be critical for planning road safety interventions.

## Conclusion

This project showcases the power of combining Python for data cleaning, verification, and analysis with Power BI for creating interactive visualizations. The integration of Python as a QC tool ensures that the insights presented in Power BI are accurate and reliable.

