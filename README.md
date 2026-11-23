# UK Financial Complaints Analysis (FCA data, 2022 H1 – 2026 H1)

Group project for the MSc Business Analytics Project Lab at UCL.

## Question
Which UK financial products and firms receive the most consumer complaints,
and how has this changed between 2022 H1 and 2026 H1?

## Data
Public complaints data from the Financial Conduct Authority (FCA):
https://www.fca.org.uk/data/complaints-data-2026-h1
- Aggregate data: complaints opened for 50 products in 5 product groups
- Firm-level data: complaints opened for each reporting firm, 9 half-years

## What the notebook covers
- **Part A–B:** cleaning the aggregate and firm-level data
- **Part C:** overall complaint trends by product group
- **Part D:** which products get the most complaints
- **Part E:** firm-level comparison

## Key findings
- Total complaints are broadly flat (−3.9% from 2022 H1 to 2026 H1).
- Banking and insurance make up about 88% of all complaints.
- Pensions and investments complaints are rising fastest (about +26% each).
- Large jumps are usually driven by one or two products, not broad increases.

## How to run
The notebook was built in Google Colab and reads the data from a shared
Google Drive folder. To run it elsewhere, put the two cleaned CSVs in one
folder and change `PROJECT_DIR` in the first code cell.

## Tools
Python, pandas, matplotlib, Jupyter / Google Colab
