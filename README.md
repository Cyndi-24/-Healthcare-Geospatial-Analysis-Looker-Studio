# Healthcare Geospatial Analysis | Looker Studio

## Introduction

This Looker Studio project uses geospatial analysis to examine healthcare visits, chronic disease burden, and healthcare facility distribution across locations in India, identifying geographic patterns in healthcare demand and service distribution.

## Objective

The objective of this analysis is to identify geographic differences in healthcare demand, chronic disease burden, and facility distribution across India, highlighting locations with greater healthcare needs.

## Analysis Questions

1. How are healthcare visits distributed across states and cities in India?
2. Which locations record the highest levels of emergency healthcare visits?
3. Where is the burden of hypertension and diabetes most concentrated?
4. How are healthcare facilities distributed across states?

## Data Preparation 

The dataset was largely analysis-ready, requiring only minor preparation in Looker Studio before visualization. This included:

- Reviewing and correcting field data types where necessary to ensure geographic and numerical fields were interpreted correctly.
- Creating calculated fields required for the analysis and KPI reporting.
- Using distinct facility identifiers to calculate the number of healthcare facilities represented in the dataset.
- Configuring geographic dimensions to support state- and city-level analysis.

## Analysis and Visualization 

### Healthcare Overview

The dataset records 19.31M total healthcare visits, 5.70M emergency visits, 6.92M hypertension cases, and 5.55M diabetes cases across 1,200 healthcare facilities.
