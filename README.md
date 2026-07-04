# AI-Ready Workforce Intelligence System

An enterprise-grade workforce analytics solution built using SQL, Python, Power BI, and Power Automate to provide automated workforce intelligence, employee risk assessment, high-performer identification, KPI monitoring, and executive reporting.

---

## Business Problem

HR leaders often spend significant time consolidating workforce data from multiple sources to identify workforce risks, monitor departmental KPIs, and recognize high-performing employees.

This solution automates the entire process and delivers actionable workforce intelligence through dashboards and scheduled executive reports.

---

## Solution Architecture

CSV Workforce Data
        │
        ▼
Python Data Processing
        │
        ▼
SQL Database
        │
        ├── Department KPI View
        ├── Employee Risk View
        └── High Performers View
        │
        ▼
Power BI Dashboard
        │
        ▼
Power Automate Cloud Flow
        │
        ▼
Weekly Workforce Intelligence Email
```

---

## Technology Stack

- Python
- SQL
- Power BI
- Power Automate
- Outlook
- CSV Data Sources

---

## Key Features

✅ Workforce KPI Monitoring

✅ Department Headcount Analysis

✅ Average Salary Insights

✅ High-Risk Employee Identification

✅ High Performer Recognition

✅ Automated Weekly Reporting

✅ Executive Email Distribution

✅ Power BI Dashboard Integration

---

## Power Automate Flow

Recurrence Trigger (Friday 5 PM)
        ↓
Get Department KPI CSV
        ↓
Get Employee Risk CSV
        ↓
Get High Performers CSV
        ↓
Parse CSV Data
        ↓
Create HTML KPI Tables
        ↓
Generate Workforce Intelligence Report
        ↓
Send Outlook Email
```

---

## Sample Deliverables

- Workforce KPI Dashboard (Power BI)
- Automated Workforce Intelligence Email
- Department KPI Summary
- High-Risk Employee Report
- High Performer Report

---

## Future Enhancements

- AI-Based Attrition Prediction
- Employee Sentiment Analysis
- Copilot Integration
- Forecasting Workforce Demand
- Azure Machine Learning Models

---

## Author

Anitha Nadar
