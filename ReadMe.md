# Solar Vehicle Analytics Dashboard

A Power BI dashboard designed to analyze and visualize telemetry data from a Solar Electric Vehicle (SEV). This project focuses on energy monitoring, battery performance analysis, solar power contribution, and vehicle efficiency using interactive business intelligence techniques.


## Project Overview

Solar electric vehicles generate large amounts of telemetry data during operation. Understanding this data is essential for optimizing vehicle performance, battery utilization, and energy efficiency.

This dashboard transforms raw telemetry data into meaningful insights through interactive visualizations, KPI tracking, and performance analytics.

The project demonstrates the application of:

* Business Intelligence (BI)
* Data Analytics
* Time-Series Analysis
* Data Visualization
* Performance Monitoring
* Dashboard Design


## Objectives

* Monitor battery performance and discharge trends.
* Analyze the relationship between vehicle speed and power consumption.
* Track solar energy generation and contribution.
* Evaluate vehicle efficiency using telemetry metrics.
* Create an interactive dashboard for data-driven decision making.


## Dataset

The dataset contains 350+ telemetry records collected at regular intervals and includes the following attributes:

| Feature               | Description               |
| --------------------- | ------------------------- |
| Timestamp             | Telemetry timestamp       |
| Speed_kmph            | Vehicle speed             |
| Battery_pct           | Battery charge percentage |
| Voltage_V             | Battery voltage           |
| Current_A             | Current drawn             |
| Solar_Power_W         | Solar panel output power  |
| Motor_Temp_C          | Motor temperature         |
| Ambient_Temp_C        | Ambient temperature       |
| Distance_km           | Distance covered          |
| Power_Consumption_W   | Vehicle power consumption |
| SOC_pct               | State of Charge           |
| Acceleration_mps2     | Vehicle acceleration      |
| Efficiency_km_per_pct | Efficiency metric         |
| Elevation_m           | Elevation data            |
| Battery_Temp_C        | Battery temperature       |
| Battery_Health_pct    | Battery health            |
| Regeneration_W        | Regenerative energy       |
| Weather               | Weather condition         |


## Tools & Technologies

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* CSV Dataset
* Data Visualization Techniques


## Data Processing Pipeline

### Data Import

* Imported telemetry dataset into Power BI.

### Data Cleaning

* Verified data types.
* Removed duplicate records.
* Processed timestamp data.
* Created derived analytical fields.

### Feature Engineering

Created additional metrics such as:

* Net Power Consumption
* Trip Duration
* Vehicle Efficiency
* Performance Indicators

### Data Modeling

Implemented DAX measures for:

* Current Battery Level
* Average Speed
* Total Distance Covered
* Total Solar Energy Generated
* Efficiency Metrics
* Thermal Performance Monitoring


## Dashboard Components

### Executive KPI Section

Key performance indicators include:

* Battery Remaining (%)
* Average Speed (km/h)
* Distance Covered (km)
* Solar Energy Generated (W)


### Battery Performance Analysis

Visualizes battery discharge trends over time.

Insights:

* Battery depletion behavior
* Energy usage patterns
* Operational efficiency


### Power Consumption vs Speed

Scatter plot analysis showing:

* Relationship between speed and power consumption
* Weather-based performance differences
* Solar contribution impact

Insights:

* Higher speeds generally increase power demand
* Outlier detection for unusual vehicle behavior


### Solar Energy Contribution

Time-series visualization showing:

* Solar power generation trends
* Peak solar generation periods
* Variations due to environmental conditions


## Key Insights

* Power consumption increases with vehicle speed.
* Solar energy contributes significantly during peak sunlight periods.
* Battery discharge follows predictable operational patterns.
* Telemetry analytics can be used for energy optimization and race strategy planning.


## Future Enhancements

* Battery Range Prediction
* Forecasting Models
* Driver Behavior Analysis
* Route Optimization
* Real-Time Telemetry Integration
* Thermal Risk Monitoring
* Predictive Maintenance Analytics

## Dashboard Preview

<img width="1417" height="798" alt="image" src="https://github.com/user-attachments/assets/6861248a-dab2-464b-85cd-ca9fdb083b3f" />

## Learning Outcomes

This project strengthened practical knowledge in:

* Power BI Dashboard Development
* Data Transformation with Power Query
* DAX Calculations
* Time-Series Data Analysis
* Telemetry Analytics
* Business Intelligence Reporting
* Data Storytelling

## Author

**Anvesha Singh**

B.Tech Data Science & Engineering
Manipal Institute of Technology

Interests:

* Data Analytics
* Business Intelligence
* Machine Learning
* Solar Vehicle Technology
* Information Security

⭐ If you found this project interesting, consider giving the repository a star.
