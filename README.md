# automation-roi-calculator
Cost comparisons and return-on-investment analysis with Python and Excel.

Overview

This project explores the potential financial benefits of automating invoice processing. It uses a synthetic dataset generated with Python to support cost comparisons and return-on-investment analysis.

Objectives

* Generate sample invoice-processing data using Python.
* Compare manual processing costs with automated processing costs.
* Estimate potential savings and payback periods.
* Visualise findings using Excel and Tableau.

Tools

* Python
* pandas
* CSV
* Microsoft Excel
* Tableau

Dataset

The dataset contains 12 months of synthetic invoice-processing data, including:

* Monthly invoice volume
* Manual processing time per invoice
* Assumed automation rate
* Exception rate
* Labour cost per hour
* Monthly software cost
* One-off setup cost

All figures are illustrative and do not represent actual company data.

Files

* generate_dataset.py — Generates the synthetic dataset.
* automation_roi_dataset.csv — Generated dataset.
* README.md — Project documentation.

How to Run

1. Install Python and pandas.
2. Run python generate_dataset.py.
3. The CSV dataset will be created in the current directory.
4. Import the dataset into Excel or Tableau for further analysis.
