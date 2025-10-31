---
editor_options: 
  markdown: 
    wrap: 72
---

# 615AssignmentF

# U.S. Strawberry Production & Profitability Analysis

## Overview

This project analyzes long-term strawberry production in the United
States using USDA/NASS data. We study how acres, yield, price, and
production relate to profitability over time. The analysis includes data
cleaning, exploratory plots, and a simple profitability model.

## Goal

Our goal is to understand economic patterns in the U.S. strawberry
industry and estimate profit trends at the farm level.

## Project Files

### File and Description

1.  clean_strawberry.csv : cleaned data, transforming, and merging raw
    USDA
2.  AssignmentF-Group-6-Final_report.pdf : Full final report with charts
    and results

## Data Sources

We use two USDA datasets: USDA NASS — strawberry production, acres
bearing, price, and utilized production.

## Methodology

### Data Cleaning Steps

1.  Filtered to U.S. Total / National level
2.  Converted numeric values from string format
3.  Pivoted long so to the wide format
4.  Filled missing values

### Key Variables Calculated

1.  Yield_per_Acre = Utilized_Production / Acres
2.  Revenue_Est = Price × Utilized Production
3.  Cost assumed \$30,000 per acre (industry estimate)
4.  Profit = Revenue − Cost
5.  Profit_per_Acre = Profit / Acres
