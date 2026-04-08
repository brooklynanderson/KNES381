# Athlete Training Load Analyzer

## Overview
This project analyzes training load and recovery patterns in athletes using Excel. The goal was to create a simple system that tracks workload, fatigue, and injury risk across different types of training sessions.

## What is Training Load?
Training load was calculated using the session RPE method:

**Training Load = Duration X RPE**

This value is expressed in arbitrary units (AU), meaning it is used as a relative measure of workload rather than a direct physical quantity.

## Dataset
The dataset includes:
- Athlete (Athlete 1 and Athlete 2)
- Session Type (Skate, Lift, Game, Conditioning, Recovery)
- Duration (minutes)
- RPE (Rate of Perceived Exertion)
- Recovery (hours)
- Fatigue Level (%)
- Injury Risk (%)

## Calculations
- **Training Load** was callculated using duration and RPE
- **Load Category** was created using an IF function:
  - Low (<300)
  - Moderate (300-600)
  - High (>600)
 
## Data Visualization
A PivotTable and PivotChart were created to analyze:

- Average Training Load (AU)
- Average Fatigue Level (%)
- Average Injury Risk (%)

These values were grouped by session type.

## Interactive Features
Slicers were added for:
- Athlete
- Session Type

This allows to filter the data and instantly update the chart.

## Key Findings
- Game and conditioning sessions produced the highest training loads
- Recovery sessions showed the lowest workload and fatigue levels
- Higher training loads were generally associated with increased fatigue and injury risk
- Athlete 2 tended to experience slightly higher fatigue and injury risk values

## Conclusion
This project demonstrates how simple Excel tools can be used to monitor athlete workload and recovery. The simplified calculations give insight into training patterns and potential fatigue trends.

## Excel File

[Download the Excel Project](trainingloadanalysis.xlsx)

## Dashboard Preview

(Image coming soon)
