# Deloitte Australia — Data Analytics Job Simulation (Forage)

This repository contains my completed work from Deloitte Australia's Data
Analytics job simulation on Forage. The simulation consisted of two tasks:
building a Tableau dashboard to analyze factory telemetry data, and using
Excel to classify pay equality scores across job roles and factories.

## Task 1: Telemetry Data Analysis (Tableau)

**Goal:** Analyze IoT telemetry data from Daikibo's factories to identify
equipment downtime patterns and determine which factory has the most
downtime.

**What I did:**
- Imported and structured JSON telemetry data in Tableau Public
- Created a calculated field (`Unhealthy`) to quantify downtime in minutes
  based on device health status
- Built two visualizations: downtime by factory, and downtime by device type
- Combined both into an interactive dashboard with filter actions, so
  selecting a factory filters the device breakdown chart

**Key finding:** Daikibo Factory Seiko had the highest total downtime, driven
primarily by Laser Welder failures.

**Files:**
- `Daikibo-telemetry-dashboard.twbx` — full interactive Tableau workbook
- `daikibo-dashboard-final.jpg` — dashboard screenshot

## Task 2: Pay Equality Classification (Excel)

**Goal:** Classify employee pay equality scores across factories and job
roles into three categories — Fair, Unfair, and Highly Discriminative —
to support a forensic investigation into potential pay discrimination.

**What I did:**
- Built a nested `IF` formula to classify each row's equality score:
  - **Fair**: score between -10 and +10
  - **Unfair**: score between -20 and -11, or +11 and +20
  - **Highly Discriminative**: score beyond ±20
- Applied the classification across all factory/role combinations

**Files:**
- `Equality_Table_Completed.xlsx` — completed classification table

## Skills Demonstrated

Data visualization, dashboard design, Tableau calculated fields, filter
actions, Excel formula logic (nested IF/AND), data classification,
analytical reasoning.

---
*Completed as part of the Deloitte Australia Data Analytics virtual
job simulation on [Forage](https://www.theforage.com/).*
