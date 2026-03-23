# Enterprise Renewal Risk Prediction in Databricks

## Overview
This project predicts which enterprise clients are at risk of non-renewal three months before contract end, allowing teams to prioritize retention actions.

## Business Problem
Enterprise customer churn can create substantial revenue loss. The goal was to identify high-risk accounts early enough to support proactive interventions.

## Project Components
- 7 Databricks notebooks covering data generation, feature engineering, modeling, evaluation, and business action design
- SQL queries powering a Databricks dashboard
- Exported dashboard JSON for version control

## Methods
- Feature engineering from monthly client health signals
- Prediction snapshot built 3 months before renewal
- Classification model to estimate renewal risk
- Segmentation of accounts into actionable risk tiers

## Key Outputs
- Risk score by account
- Estimated churn volume
- Top drivers of account risk
- Dashboard for business stakeholders

## Tech Stack
Databricks, Python, SQL, Spark, MLflow (optional), GitHub

## Files
- `/notebooks` → Databricks notebooks
- `/dashboard_queries` → SQL for dashboard tiles
- `/dashboards` → exported dashboard JSON
- `/images` → screenshots used in this README

## Dashboard Preview
![Dashboard](images/dashboard_overview.png)

## Business Impact
This project shows how a data science workflow can move from raw account signals to an operational retention dashboard that supports targeted interventions.