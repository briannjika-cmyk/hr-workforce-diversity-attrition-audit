# HR Workforce Diversity & Attrition Audit

An Excel-based review of an HR employee attrition dataset. The repository includes the raw CSV dataset and an analysis workbook containing pivot tables and a chart.

## Repository contents

| Path | Description |
|---|---|
| `data/raw/WA_Fn-UseC_-HR-Employee-Attrition.csv` | Raw employee attrition dataset |
| `data/raw/README.md` | Dataset source note |
| `sheets/HRDataset Analysis (1).xlsx` | Excel workbook containing the analysis |
| `images/Screenshot 2026-11-18 221248.png` | Project image |

## Workbook

Open `sheets/HRDataset Analysis (1).xlsx` in Microsoft Excel or another spreadsheet application compatible with `.xlsx` workbooks to review:

- Pivot-table summaries
- Chart results
- Workbook-level transformations and calculations
- Results of checks performed during the analysis

The workbook is the primary source for the analysis in this repository. The README should not present counts or conclusions for missing values or duplicate records unless they have been verified in the workbook or raw data.

## Raw Dataset

The raw dataset is stored in:

`data/raw/WA_Fn-UseC_-HR-Employee-Attrition.csv`

The source note in `data/raw/README.md` identifies the dataset as IBM HR Analytics and points to Kaggle for the original source. Use this source when examining employee counts, demographic fields, employment characteristics, compensation fields, and attrition outcomes.

## Data Quality

The repository’s workbook and raw dataset should be checked explicitly for:

- Missing values
- Duplicate rows
- Unexpected data types
- Inconsistent categorical values
- Blank or invalid employee identifiers
- Values outside realistic ranges

Any conclusions in this section should be based on repeated verification against the workbook and raw CSV rather than assumptions.

## Workbook Analysis

The Excel workbook contains the main analysis and should be used to interpret employee attrition from the available fields.

When updating this section, include only observations supported by the workbook:

- Which employee characteristics were compared
- Which attrition groups were summarized
- Which fields were used as pivot-table categories
- Any visible chart results
- The exact values and trends shown in the workbook

Avoid attributing causes to correlation-based observations unless the analysis explicitly tests or establishes them.

## Analysis and Findings

This section should report the findings that can be directly observed or calculated from the dataset.

Findings may cover:

- The number of employees represented
- Overall attrition status distribution
- Differences in attrition across workforce categories
- Demographic or job-related patterns shown by the pivot tables
- Comparison of the records in the chart with the underlying workbook data
- Summary of missing or duplicate records if verified

Because findings must remain evidence-based, no unsupported explanations or causal statements should be included.

## Recommendations

Recommendations should be grounded in the workbook findings and may include:

- Prioritizing further analysis of employee groups showing higher attrition
- Improving the collection of missing or inconsistent fields
- Standardizing categorical values used for reporting
- Creating monitoring measures for recurring attrition patterns
- Validating findings with additional HR or operational data
- Reviewing high-risk workforce segments through follow-up analysis rather than assuming a direct cause

## Data Governance and Limitations

The analysis should be interpreted as a descriptive audit of the supplied records.

The workbook alone does not establish:

- Why employees left
- Whether observed differences are statistically significant
- Whether findings apply beyond this dataset
- Causal relationships between employee characteristics and attrition
- Suitability of individual-level decisions from aggregate trends

## How to Use the Workbook

1. Download or open `sheets/HRDataset Analysis (1).xlsx`.
2. Review the worksheets and pivot tables.
3. Compare workbook results with `data/raw/WA_Fn-UseC_-HR-Employee-Attrition.csv`.
4. Use the workbook filters and dimensions to explore employee attrition patterns.
5. Document and verify any findings before using them for workforce decisions.

## Source

The raw employee data is an IBM HR Analytics-style attrition dataset supplied through the project repository.
