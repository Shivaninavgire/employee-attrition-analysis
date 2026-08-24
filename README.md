# employee-attrition-analysis
# Employee Attrition Analysis

## Project Overview

Employee attrition is an important Human Resources (HR) challenge because employees leaving an organization can increase recruitment and training requirements, affect productivity, and result in the loss of organizational knowledge.

This project focuses on understanding employee attrition using HR employee data. The project covers business understanding, dataset understanding, exploratory data analysis (EDA), problem formulation, ethical considerations, and project planning.

The long-term objective is to build a machine-learning classification model that can predict whether an employee is likely to leave the organization and provide insights that can support responsible employee-retention strategies.

---

## Business Problem

Organizations need to understand patterns associated with employee attrition so that HR teams and managers can take proactive and appropriate retention actions.

### Problem Statement

> To analyze employee HR data and identify patterns associated with employee attrition, with the objective of predicting whether an employee is likely to leave the organization.

---

## Project Objectives

- Understand the employee attrition business case.
- Understand the role of HR analytics.
- Identify business stakeholders.
- Understand the impact of employee attrition.
- Review and document all HR dataset features.
- Identify the target variable and feature types.
- Perform basic exploratory data analysis.
- Formulate employee attrition as a binary classification problem.
- Define business and model evaluation KPIs.
- Identify ethical considerations.
- Create a structured workflow and project roadmap.
- Prepare the project for future machine-learning modeling.

---

## Dataset Overview

The dataset contains **1,470 employee records and 35 columns**.

| Dataset Property | Result |
|---|---:|
| Records | 1,470 |
| Columns | 35 |
| Integer columns | 26 |
| Object/Categorical columns | 9 |
| Target variable | `Attrition` |
| Missing values | 0 |
| Duplicate rows | 0 |
| Attrition = No | 1,233 |
| Attrition = Yes | 237 |
| Approximate attrition rate | 16.12% |

---

## Target Variable

The target variable is:

`Attrition`

- `No` → Employee did not leave the organization
- `Yes` → Employee left the organization

This makes the problem a **binary classification problem**.

For future machine-learning modeling:

```text
No  → 0
Yes → 1
