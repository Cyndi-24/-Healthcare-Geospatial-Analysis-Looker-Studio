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
An interactive Looker Studio dashboard was developed to visualize and explore the healthcare dataset across geographic locations in India.

![image alt](https://github.com/Cyndi-24/-Healthcare-Geospatial-Analysis-Looker-Studio/blob/main/Geospace%20analysis/dashboard_image.png)

### Healthcare Overview

The dataset records 19.31M total healthcare visits, 5.70M emergency visits, 6.92M hypertension cases, and 5.55M diabetes cases across 1,200 healthcare facilities.

## Analysis & Findings

### 1. How are healthcare visits distributed across states and cities in India?

Vizag records the highest city-level visits at 1.20M, followed by Hyderabad at 1.17M and Chandigarh at 1.10M. This concentration shows that healthcare demand is not evenly distributed across cities, highlighting locations where service demand is comparatively greater.

### 2. How do total and emergency healthcare visits vary geographically across India?

Andhra Pradesh records the highest total and emergency visits at 2.30M and 654K respectively. However, Maharashtra records fewer total visits than Madhya Pradesh and Tamil Nadu but a higher volume of emergency visits, showing that overall healthcare demand and emergency-care demand do not follow the same geographic pattern.

### 3. Where is the burden of hypertension and diabetes most concentrated?

Maharashtra records the highest hypertension burden with 773,642 cases, while Andhra Pradesh records the highest diabetes burden with 559,784 cases. The different geographic concentrations suggest that healthcare planning for chronic diseases may need to reflect condition-specific burden rather than treating chronic disease demand as uniform across states.

### 4. How are healthcare facilities distributed across states?

Andhra Pradesh has the highest facility representation with 131 facilities, followed by Maharashtra with 126 and Tamil Nadu with 113. When considered alongside differences in visits and disease burden, facility counts alone do not establish whether capacity is sufficient, but they provide a basis for identifying states where demand and available healthcare infrastructure should be assessed together.

## Recommendations

- **Prioritize high-demand locations:** States and cities with consistently higher healthcare visits should receive greater attention in capacity and resource planning.

- **Plan chronic disease services by condition:** The differing geographic patterns of hypertension and diabetes suggest that disease-management resources should reflect condition-specific burden rather than a uniform approach across states.

- **Assess emergency-care demand separately from overall visits:** Since emergency and total visit patterns do not always align, emergency-care planning should consider emergency demand independently of overall healthcare utilization.

- **Evaluate facility capacity alongside demand:** Facility counts should be considered together with healthcare visits and disease burden to identify locations where existing infrastructure may require further capacity assessment.

## Limitations

- States with larger populations may naturally record more healthcare visits and disease cases, so higher totals do not necessarily mean a greater health burden.
- Some states have more healthcare facilities represented in the dataset, which may contribute to their higher visit and disease totals.
- The number of facilities does not show how large or well-resourced they are, including differences in staffing, beds, or available services.

## Conclusion

The analysis shows how healthcare needs differ by location and provides useful insights for identifying where healthcare resources and services may require greater attention.
