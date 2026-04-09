# Employee Risk Classification using Decision Support System

## Project Overview
This project implements a Decision Support System (DSS) to help organizations identify employees at risk and recommend appropriate actions. The system uses rule-based logic to analyze employee data and support HR decision-making.

## Problem Statement
Organizations often struggle to identify employees who are at risk of leaving. Manual analysis is time-consuming and inefficient, leading to delayed decisions and increased attrition.

This project solves this problem by developing a system that classifies employees into risk levels and provides actionable recommendations.

## Objective
- Identify high-risk employees
- Support HR decision-making
- Reduce employee attrition
- Improve workforce management

## Dataset Features
- employee_id
- department
- satisfaction_score
- attendance_percent
- overtime_hours
- performance_rating

## Decision Support System

### Risk Classification Logic
- High Risk: Low satisfaction and high overtime
- Medium Risk: Low satisfaction or low attendance
- Low Risk: Stable employees

### Recommendation Logic
- High Risk: Immediate HR intervention
- Medium Risk: Monitor and training
- Low Risk: Maintain performance


## How to Run
1. Open notebook in Google Colab
2. https://colab.research.google.com/drive/14cMDYs6PnDt_ptyWkv8yPUucH5nHjmRI
3. Run all cells
4. View risk classification and recommendations

## Output
The system generates:
- Risk level for each employee
- Recommended actions

## Business Insights
- Employees with low satisfaction and high overtime are high risk
- Attendance impacts employee stability
- Early identification helps reduce attrition

## Conclusion
This DSS helps convert raw employee data into actionable insights, enabling faster and more effective HR decisions.
