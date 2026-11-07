# Loan Default: Exploratory Data Analysis

Finds the traits that predict whether a loan applicant will struggle to repay, so a lender can approve, reduce, or reprice loans with less risk.

## Problem

A lender wants to approve only applicants who can repay. This analysis looks for the driver variables behind default to support portfolio management and risk analysis.

## Approach

1. Load and inspect the application dataset
2. Clean data: review missing values by column, drop columns with more than 40 to 50% missing values (including `EXT_SOURCE_1`), drop flag and social-circle columns judged irrelevant, and leave `OCCUPATION_TYPE` untreated (31% missing) to avoid distorting a categorical variable
3. Column-by-column analysis against the default target
4. Analysis of the previous-applications dataset alongside the current applications

## Files

| File | Purpose |
| --- | --- |
| `EDA Assignment  Anand pratap.ipynb` | Full analysis |
| `EDA ASSIGMENT _anand pratap.pdf` | Report |

## Stack

Python, pandas, matplotlib, seaborn
