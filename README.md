# Data Cleaning and Validation Pipeline for DS Appropriations R3 Funding

## Overview
A Python-based data processing and auditing pipeline designed to clean, normalize, validate, and standardize financial appropriation datasets. The notebook transforms raw funding-request CSV files into structured, analysis-ready datasets while identifying inconsistencies, incomplete records, and potential discrepancies in financial reporting.

## Key Features

- **Data Ingestion & Schema Validation:** Processes raw CSV files, handles inconsistent headers, enforces expected data types, and validates records against predefined constraints.
- **Automated Data Standardization:** Normalizes currency values, percentages, Boolean (Y/N) fields, and inconsistent string formatting to ensure uniform data representation.
- **Duplicate Detection & Deduplication:** Identifies and removes redundant records to improve dataset integrity and prevent duplicate financial entries.
- **Financial Discrepancy Auditing:** Flags funding deductions lacking documented justification, enabling targeted review and improved financial accountability.
- **Missing Data Analysis:** Detects absent critical financial values and identifies incomplete records that require further verification.
- **Structured Data Export:** Generates cleaned, standardized CSV datasets suitable for downstream financial analysis, reporting, and decision-making.

## Technologies
Python, Pandas, CSV Processing, Data Validation, Data Quality Auditing

## Impact
Improves the reliability, consistency, and auditability of student organization funding data by automating repetitive data-cleaning tasks and highlighting records requiring manual review.
