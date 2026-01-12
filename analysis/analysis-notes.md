# Excel Data Consolidation Dashboard

## Project Objective
The objective of this project was to consolidate raw Excel data into a single, reliable dataset and build pivot-driven analysis and dashboards to support performance monitoring and reporting.

The project emphasizes data accuracy, traceability, and clarity of insights rather than advanced automation.

---

## Data Overview
The project uses two primary datasets located in the `Data/` folder:

- **Raw Dataset.xlsx**  
  Represents the original input data prior to cleaning and consolidation.

- **Consolidated Data.xlsx**  
  The final, cleaned dataset used for analysis and dashboard development.

All datasets included in this repository have been sanitized and do not contain real or sensitive information.

---

## Data Consolidation & Cleaning Process
A structured approach was followed to ensure data quality and consistency:

1. **Data Review**
   - Assessed column structure and data types
   - Identified duplicates, missing values, and inconsistent formats

2. **Standardization**
   - Renamed columns for consistency
   - Converted dates and numeric fields to appropriate formats
   - Normalized categorical values (e.g., status, categories)

3. **Consolidation**
   - Combined the cleaned data into a single master dataset using the index-match function
   - Preserved key identifiers to maintain traceability

4. **Validation**
   - Verified row counts before and after consolidation
   - Checked for duplicate records using key fields
   - Performed spot checks for outliers and invalid values

---

## Analysis Methodology
Analysis was performed using Excel pivot tables located in:

- `Workbook/KPI-Pivot_Table_Charts.xlsx`

Pivot tables were used to:
- Aggregate key metrics
- Compare performance across categories
- Identify trends and outliers

These pivot tables served as the analytical foundation for the dashboard.

---

## Dashboard Development
The main dashboard is contained:

- `KPI/Dashboard.xlsx`

Design considerations included:
- Clear display of key KPIs
- Interactive slicers for filtering
- Clean and consistent formatting
- Easy refresh and usability

The dashboard allows users to quickly explore the data and identify key patterns without navigating raw tables.

---

## Audit & Change Tracking
An audit log is maintained in:

- `KPI/audit_log.xlsx`

The audit log documents:
- Data cleaning actions
- Structural changes
- Rationale for key decisions

This supports transparency and traceability throughout the analysis process.

---

## Key Insights (Summary)
- A small subset of records accounted for a significant share of overall performance
- Some low-activity or inactive segments continued to generate measurable impact
- Data inconsistencies in the raw dataset would have affected reporting accuracy without standardization

(Note: Specific values are omitted due to data sanitization.)

---

## Limitations
- The workflow relies on manual Excel processes
- Data refresh requires consistent input structure
- The project focuses on descriptive reporting rather than predictive analysis

---

## Reproducibility
To update the analysis:
1. Replace `Raw Dataset.xlsx` with updated data of the same structure
2. Refresh pivot tables in `KPI/Pivot_Table.xlsx`
3. Review validation checks and audit log entries
4. Refresh the dashboard in `Dashboard.xlsx`

---

## Conclusion
This project demonstrates practical Excel skills in data consolidation, validation, index-match function, pivot-table analysis, and dashboard reporting.  
It reflects a real-world reporting workflow where data accuracy, documentation, and usability are critical.

