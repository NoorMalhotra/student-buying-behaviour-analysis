# Student Buying Behaviour — Data Analytics Project

A reproducible exploratory data analysis (EDA) project using the public **Consumer Decision Making Data** dataset from Mendeley Data.

## Research question
What patterns appear in survey responses about online-shopping decisions among Indian university students?

## Dataset
- **Name:** Consumer Decision Making Data
- **Source:** [Mendeley Data](https://data.mendeley.com/datasets/8rcsspgxnt/1)
- **DOI:** [10.17632/8rcsspgxnt.1](https://doi.org/10.17632/8rcsspgxnt.1)
- **Supplied workbook structure:** 3,329 rows × 95 columns

The workbook audit found **1,695 exact duplicate rows**. Their cause has not been established, so the notebook reports them transparently and performs a sensitivity check rather than silently deleting them. Results should be considered preliminary until this is resolved.

## Repository structure
```text
student-buying-behaviour/
├── data/
│   └── .gitkeep
├── notebooks/
│   └── student_buying_behaviour_eda.ipynb
├── outputs/
│   └── figures/
├── requirements.txt
├── .gitignore
└── README.md
```

## Run it locally
1. Clone/download this repository.
2. Download the workbook from the Mendeley Data source page.
3. Place it at `data/consumerresponses.xlsx`.
4. Install packages:
   ```bash
   pip install -r requirements.txt
   ```
5. Open Jupyter and run `notebooks/student_buying_behaviour_eda.ipynb` from top to bottom.

## What the notebook does
- Inspects shape, columns, missing cells, and exact duplicate rows.
- Summarizes selected demographic and shopping variables.
- Analyses the actual website-design survey item.
- Creates a chart and compares the original workbook with distinct full rows as a sensitivity check.
- Documents limitations and avoids causal claims.

## Important interpretation note
The survey item asks respondents how important website design and graphics are to their purchase decisions. Ratings of 4–5 represent **reported importance**, not proof that design causes purchases.

## Attribution
Credit the original dataset authors and cite the Mendeley Data record: **Consumer Decision Making Data**, DOI `10.17632/8rcsspgxnt.1`. Review the source page's licence and terms before redistributing the raw workbook.

## Current status
Exploratory analysis / preliminary. Duplicate-row provenance remains unresolved.
