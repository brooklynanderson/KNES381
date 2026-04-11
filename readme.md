# Athlete Performance Monitoring System
A practical athlete monitoring system designed to support training decision-making through training load analysis, performance tracking, and movement assessment.

---

## What's Included

This athlete monitoring system can be used by coaches and athletes to track workload, performance and recovery.
- Training load analysis using duration and RPE
- Fatigue and injury risk monitoring
- Interactive performance dashboard
- Training load calculator for session planning
- Movement analysis to assess athlete's functionality and ensure proper form

---

## Who Can Use This?

This system is designed for:
- Coaches monitoring athlete's workload
- Athletes tracking training intensity
- S&C professionals
- Sport Science Researchers looking at performance analysis

---

## Performance Metrics

### Training Load (AU)
Training load was calculated using the session RPE method:

**Training Load = Duration X RPE**

This value is expressed in arbitrary units (AU), meaning it is used as a relative measure of workload rather than a direct physical quantity.

### Fatigue Level (%)
Used to estimate recovery and readiness
### Injury Risk (%)
Used to identify potential increases in risk with higher workloads
### Load Category
Categorizes training load as low, moderate or high.

---

## Athlete Data Tracking

The dataset includes:

- Athlete (Athlete 1 and Athlete 2)
- Session Type (Skate, Lift, Game, Conditioning, Recovery)
- Duration (Minutes)
- RPE (Rate of Perceived Exertion)
- Recovery (Hours)
- Fatigue Level (%)
- Injury Risk (%)
- Load Category (Low, Moderate, High)

---

## Athlete Monitoring System

The Excel workbook functions as a dynamic athlete monitoring system:

- Training Load is calculated using a formula that multiplies duration and RPE
- Load Category was created using an IF function:
  - Low (<300)
  - Moderate (300-600)
  - High (>600)
- A PivotTable summarizes performance data
- A PivotChart visualizes trends
- Slicers allows interactive filtering by athlete and session type

This allows for quick assessment of how workload impacts fatigue and injury risk.

---

## Performance Dashboard

The dashboard can provide a visual summary of:
- Average Training Load (AU)
- Average Fatigue Level (%)
- Average Injury Risk (%)

### Dashboard Preview

![Dashboard](dashboard.png)

The dashboard above is generated from a PivotTable and updates automatically when the data or slicers are changed in the Excel Workbook.

---

## Training Load Calculator

An interactive calculator allows users to estimate training load for new sessions.
- Input: duration and RPE
- Output: training load and load category

### Calculator Preview

![Calculator](TrainingLoadCalculator.png)

The calculator above shows how training load is generated from session inputs. It allows users to estimate workload and classify session intensity based on duration and RPE.

---

## Dartfish Movement Analysis
Dartfish provides visual analysis of how movement mechanics contribute to athlete performance.

### Example: Breakdown of Sprint Acceleration

#### Phase 1: Set up

This phase shows..

#### Phase 2: Force Production

This phase shows...

#### Phase 3

This phase shows...

Coming soon...

---

## Key Insights
- Game and conditioning sessions produce the highest training loads
- Recovery sessions show the lowest workload and fatigue levels
- Higher training loads are associated with increased fatigue and injury

---

## Resources

[Download the Excel Project](trainingloadanalysis.xlsx)


### About This Project

This project was developed as part of the UofC KNES381 course and demonstrates practical skills in athlete monitoring, data analysis, and performance assessment using Excel and Dartfish.
