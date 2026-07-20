# Employee Attrition Analysis

An independent analysis of the **IBM HR Analytics Employee Attrition dataset** (1,470 employee records) to identify the strongest predictors of voluntary employee turnover, using pivot table analysis in Excel.

## Objective

Identify which factors — department, overtime status, and job satisfaction — most strongly predict whether an employee leaves the company, and translate the findings into actionable HR recommendations.

## Tools Used

- Microsoft Excel (Pivot Tables)
- Dataset: [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets) (Kaggle)

## Key Findings

| Factor | Finding |
|---|---|
| **Overtime** | Employees working overtime leave at **31%**, vs **10%** for those who don't — roughly 3x higher |
| **Job Satisfaction** | Attrition falls steadily from **23%** (lowest satisfaction) to **11%** (highest satisfaction) |
| **Department** | Sales has the highest attrition at **21%**, ahead of HR (19%) and R&D (14%) |

## Recommendations

1. Prioritise a workload/overtime review within Sales, where overtime prevalence and attrition risk intersect.
2. Investigate root causes of low job satisfaction via pulse surveys or exit interviews.
3. Pilot a retention intervention (workload rebalancing or flexible scheduling) for employees logging regular overtime, and track attrition over the following two quarters.

## Files in this repo

- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — raw dataset
- `attrition-analysis.xlsx` — pivot table analysis (3 tabs: by Department, by OverTime, by Job Satisfaction)
- `attrition-analysis.pdf` — full written findings report

## Full Report

See [`attrition-analysis.pdf`](./attrition-analysis.pdf) for the complete write-up, including methodology and recommendations.
