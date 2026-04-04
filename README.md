# Data-Cleaning-for-DS-Appropriations-R3-Funding
Summary

This notebook inputs raw CSV files containing funding requests, standardizes the file, reformats the strings, removes duplicates, and an audit to showcase where incomplete data is.

What it does:

Ignores headers and enforces certain constraints if typed wrong
Cleans $, %, and standardizes Y/N inputs
Identifies and reports rows where a financial deduction occurred but no justification was provided.
Identifies missing critical amounts.
Outputs a standardized CSV.
