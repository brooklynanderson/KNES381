<p align="center">
<strong style="font-size:20px;">
Athlete Monitoring System for Training Load, Recovery & Movement Analysis
<strong>
</p>

<p align="center">
Track performance • Analyze workload • Improve movement quality
</p>

---

## Navigation

<p align="center">
  <a href="#system-overview"><strong>Overview</strong></a> ·
  <a href="#intended-users"><strong>Users</strong></a> ·
  <a href="#performance-metrics"><strong>Metrics</strong></a> ·
  <a href="#performance-dashboard"><strong>Dashboard</strong></a> ·
  <a href="#training-load-calculator"><strong>Calculator</strong></a> ·
  <a href="#dartfish-movement-analysis"><strong>Dartfish</strong></a> ·
  <a href="#resources"><strong>Resources</strong></a>
</p>

---

## System Overview

| Component | Purpose |
|---|---|
| Training Load Analysis | Tracks workload using duration and RPE |
| Recovery Monitoring | Identifies fatigue and injury risk trends |
| Session Planning Tool | Estimates workload before training begins |
| Movement Analysis | Assesses movement quality using Dartfish |

---

## Intended Users

This system is designed for:

- Coaches monitoring athlete workload
- Athletes tracking training intensity
- Stength & Conditioning professionals
- Sport Science practitioners

---

## Performance Metrics

These metrics provide the foundation for monitoring athlete workload.

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

## System Functionality

The Excel workbook functions as a dynamic athlete monitoring system:

- Training Load is calculated using a formula that multiplies duration and RPE
- Load Category was created using an IF function:
  - Low (<300)
  - Moderate (300-600)
  - High (>600)
- A PivotTable summarizes performance data
- A PivotChart visualizes trends
- Slicers allow interactive filtering by athlete and session type

This allows for quick assessment of how workload impacts fatigue and injury risk.

<br>

<h2 align="center">Athlete Monitoring in Practice</h2>

---

## Performance Dashboard

This dashboard provides a visual summary of training load, fatigue and injury risk across session types. It updates automatically based on filters and input data.

<p align="center">
 <img src="dashboard.png" width="100%"> 
</p>

---

## Training Load Calculator

<div style="display: flex; align-items: center; gap: 30px;">

<div style="flex: 1;">
<img src="TrainingLoadCalculator.png" width="100%">
</div>

<div style="flex: 1;">
<p>
This tool allows users to estimate training load based on session duration and RPE, helping plan training intensity before sessions occur.
</p>
</div>

</div>

---

## Dartfish Movement Analysis

While the Excel system tracks workload and performance data, movement analysis provides additional insight into how technique influences these outcomes. Dartfish provides visual analysis of movement, allowing athletes to assess technique, correct errors, and improve performance. It can be applied to a variety of movements while helping relate movement mechanics to training load, fatigue, and injury risk.

#### Example: Deadlift Analysis

<div style="display: flex; gap: 20px;">

<div style="flex: 1; text-align: center;">
<img src="videoframe1.png" width="100%">
</p><em>Figure 1. Set-up position showing joint angle and starting posture. </em></p>
</div>

<div style="flex: 1; text-align: center;">
<img src="videoframe2.png" width="100%">
<p><em>Figure 2. Bar path illustrating efficient movement during lifting.</em></p>
</div>

</div>

<p>
Proper setep ensures effective force production while minimizing injury risk. A vertical bar path imprpves efficiency and increases force output, contributing to changes in RPE and overall training load.
</p>

---

## Resources

[Download the Excel Project](trainingloadanalysis.xlsx)

### About This Project

This project was developed as part of the UofC KNES381 course and demonstrates practical skills in athlete monitoring, data analysis, and performance assessment using Excel and Dartfish.
