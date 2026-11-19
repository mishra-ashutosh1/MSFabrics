# HR Analytics Dashboard using Microsoft Fabric

## Overview

This project demonstrates an end-to-end HR Analytics solution built using Microsoft Fabric. The solution ingests employee leave planning data, transforms it using Dataflow Gen2, stores it in a Lakehouse, models the data through a Semantic Model, and delivers interactive business insights through a Power BI report.

The objective is to provide HR teams and department managers with visibility into leave utilization, department-wise leave distribution, leave status tracking, and workforce planning trends.

---

## Architecture

Source Data
→ Dataflow Gen2
→ Lakehouse
→ SQL Analytics Endpoint
→ Semantic Model
→ Power BI Report

### Artifacts

- LeavePlanner Lakehouse
- LeavePlanner Dataflow Gen2
- LeavePlanner SQL Analytics Endpoint
- SM_LeavePlanner Semantic Model
- HRAnalytics Power BI Report

---

## Business Use Cases

### HR Operations

- Monitor leave requests across departments
- Track approved, pending, and planned leave
- Identify leave-heavy departments
- Support workforce planning decisions

### Management Reporting

- Department-level leave analysis
- Leave type distribution
- Leave request monitoring
- Resource allocation insights

---

## Dashboard Features

### Department Filter

Interactive slicer allowing users to analyze leave statistics by department:

- Engineering
- HR
- Finance
- Operations
- Sales

### KPI Metrics

- Total Leave Requests

### Visualizations

#### Department-wise Leave Days
Displays cumulative leave days consumed by each department.

#### Leave Type Distribution
Interactive donut chart showing the breakdown of:

- Annual Leave
- Sick Leave
- Emergency Leave
- Public Holiday
- Business Travel
- Training
- Work From Home (WFH)
- Comp Off
- Study Leave
- Mental Health Day

#### Leave Status Analysis
Tracks:

- Approved
- Pending
- Planned

#### Leave Distribution by Category
Compares employee leave requests across different leave types.

---

## Technology Stack

- Microsoft Fabric
- Dataflow Gen2
- Lakehouse
- SQL Analytics Endpoint
- Semantic Model
- Power BI
- OneLake

---

## Data Model

Key attributes used in the solution:

| Column |
|----------|
| Employee Name |
| Employee ID |
| Department |
| Leave Type |
| Start Date |
| End Date |
| Duration Days |
| Status |

---

## Insights Generated

Examples of business questions answered:

- Which department consumes the most leave?
- What percentage of requests are pending approval?
- Which leave category is most frequently used?
- How is leave distributed across departments?
- What is the overall leave utilization trend?

---

## Future Enhancements

- Integration with SharePoint Leave Planner
- Automated Fabric refresh schedules
- Power Automate approval workflow
- Monthly leave trend analysis
- Employee leave balance tracking
- Predictive workforce planning
- Executive HR scorecard

---

## Author

Ashutosh

Built using Microsoft Fabric and Power BI to demonstrate modern HR Analytics and workforce planning capabilities.# Fabric
