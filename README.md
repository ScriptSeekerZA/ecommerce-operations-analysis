# South African E-commerce Operations Analysis

## Project Overview

This project analyses a **synthetic e-commerce order dataset** created
to represent a fictional South African online clothing retailer. The
dataset covers August to October 2026 and contains 1,200 original order
records.

The objective was to demonstrate how Excel can be used to clean
operational data, investigate data-quality issues, monitor e-commerce
performance and communicate actionable business insights.

> **Data disclaimer:** All records are synthetic and were created for
> portfolio and learning purposes. They do not represent a real
> retailer, customer, or transaction.

## Tools and Techniques

-   Microsoft Excel
-   Power Query for data cleaning and transformation
-   Excel formulas for KPI calculations
-   PivotTables and PivotCharts
-   Interactive dashboard with slicers
-   Data-quality auditing and validation
-   Operational performance analysis

## Project Workflow

1.  **Raw data review:** Inspected the original order dataset and its
    fields.
2.  **Data cleaning:** Used Power Query to remove duplicate records,
    standardise text fields and reconstruct 10 missing quantity values
    using available order-value, unit-price and discount information.
3.  **Data-quality audit:** Investigated missing values and exceptions,
    distinguishing legitimate blanks from issues requiring follow-up.
4.  **KPI calculations:** Built calculations for order volumes,
    delivery, returns, cancellations and delivered sales.
5.  **Operational analysis:** Examined sales channels, regions, delivery
    performance and recorded return reasons.
6.  **Dashboard and insights:** Created an interactive executive
    dashboard and summarised findings for management.

## Key Results

  Measure                                  Result
  --------------------------------- -------------
  Original records                          1,200
  Records after duplicate removal           1,194
  Delivered orders                            788
  Delivery rate                            66.00%
  Returned orders                             114
  Overall order return rate                 9.55%
  Cancelled orders                             83
  Cancellation rate                         6.95%
  Delivered sales                     R629,672.05

## Selected Business Insights

### Sales channel return rates

-   Mobile App: **10.61%**
-   Marketplace: **10.00%**
-   Online Store: **8.20%**

The Mobile App had the highest return rate in this dataset, while the
Online Store had the lowest. These differences may warrant further
investigation into product information, sizing guidance and customer
expectations. The figures alone do not establish the causes of returns.

### Regional delivered sales

-   Coastal: **R321,917.70**
-   Inland: **R307,754.35**

The Coastal region generated R14,163.35 more delivered sales than
Inland.

### Delivery performance

-   Coastal average delivery time: **7.51 days**
-   Inland average delivery time: **7.41 days**

The difference between the regional averages was small in this dataset.

### Recorded return reasons

Among the 112 returned orders with a recorded reason:

-   Size issue: 24
-   Wrong item: 24
-   Changed mind: 23
-   Damaged item: 22
-   Not as expected: 19

Two returned orders had no recorded reason and were retained as
data-quality exceptions rather than assigned an assumed reason.

## Data Quality and Limitations

The audit identified several items requiring review:

-   Six duplicate records were removed, leaving 1,194 records.
-   Ten missing quantity values were reconstructed from other available
    fields.
-   Twelve orders had missing Customer_ID values.
-   Fifteen orders had missing courier information.
-   Missing shipping and actual delivery dates were reviewed against
    order status. Many blanks were consistent with orders still
    processing, cancelled or shipped but not yet delivered.
-   One returned order had no actual delivery date.
-   Two returned orders had no recorded return reason.

Missing values were not automatically replaced with zero or guessed
values. Exceptions were retained and documented where source information
would be needed to resolve them.

## Workbook Contents

The Excel workbook includes:

-   Executive dashboard
-   Management insights
-   KPI calculations
-   Data-quality audit report
-   Supporting PivotTables and analysis worksheets
-   Cleaned and raw data
-   Data dictionary and project brief
-   Supporting audit queries and outputs

## What This Project Demonstrates

This project demonstrates practical experience in:

-   Preparing and validating operational datasets
-   Using Power Query to create a repeatable cleaning workflow
-   Building operational KPIs
-   Analysing sales, returns and delivery performance
-   Creating interactive Excel reporting
-   Translating data findings into management-focused insights

------------------------------------------------------------------------

*Portfolio project \| Excel and Power Query \| Synthetic South African
e-commerce dataset \| August--October 2026*
