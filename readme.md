A practical athlete monitoring system designed to support training decision-making through training load analysis, performance tracking, and movement assessment.

---
## Navigation

[Overview](#system-overview) | [Users](#intended-users) | [Metrics](#performance-metrics) | [Dashboard](#performance-dashboard) | [Calculator](#training-load-calculator) | [Dartfish](#dartfish-movement-analysis) | [Resources](#resources)

---

## System Overview

| Component | Purpose |
|---|---|
| Training Load Analysis | Tracks workload using duration and RPE |
| Recovery Monitoring | Identifies fatigue and injury risk trends |
| Performance Dashboard | Summarizes athlete condition visually |
| Training Load Calculator | Estimates session demand before training |
| Dartfish Movement Analysis | Assesses movement quality and intensity |

---

## Intended Users

This system is designed for:
- Coaches monitoring athlete workload
- Athletes tracking training intensity
- S&C professionals
- Sport Science Researchers interested in performance analysis

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

---

## Performance Dashboard

The dashboard can provide a visual summary of:
- Average Training Load (AU)
- Average Fatigue Level (%)
- Average Injury Risk (%)

### Dashboard Preview

![Dashboard](dashboard.png)
*Figure 1. Interactive dashboard example displaying average training load by session type between Athlete 1 and Athlete 2.*

The dashboard above is generated from a PivotTable and updates automatically when the data or slicers are changed in the Excel Workbook.

---

## Training Load Calculator

An interactive calculator allows users to estimate training load for new sessions.
- Input: duration and RPE
- Output: training load and load category

### Calculator Preview

![Calculator](TrainingLoadCalculator.png)
*Figure 2. Training load calculator used to estimate workload from session duration and RPE*

The calculator above shows how training load is generated from session inputs. It allows users to estimate workload and classify session intensity based on duration and RPE.

---

## Dartfish Movement Analysis
While the Excel system tracks workload and performance data, movement analysis provides additional insight into how technique influences these outcomes.
Dartfish provides visual analysis of movement, allowing athletes to assess technique, correct errors, and improve performance. It can be applied to a variety of movements while helping relate movement mechanics to training load, fatigue, and injury risk.

### Example: Deadlift Analysis

#### Set Up Analysis

![Deadlift Setup](videoframe1.png)
*Figure 3. Steup position showing joint angle and starting posture.*

In the setup phase, the athlete demonstrates a hip hinge position with a neutral spine and appropriate knee angle of approximately 55°. This position allows for effective force production while maintaining proper alignment. Proper setup is critical for reducing injury risk and preparing the body for high-intensity effort.

#### Bar Path Analysis

![Deadlift Lift](videoframe2.png)
*Figure 4. Bar path analysis illustrating movement efficiency during force production.*

During the lifting phase, the athlete generates force through coordinated extension at the hip and knee. The bar path remains vertical and close to the body, which improves efficiency and reduces unnecessary strain. This phase requires high muscular effort and contributes to increased RPE, leading to higher training load values.

---

## Resources

[Download the Excel Project](trainingloadanalysis.xlsx)

---

#### About This Project

This project was developed as part of the UofC KNES381 course and demonstrates practical skills in athlete monitoring, data analysis, and performance assessment using Excel and Dartfish.
