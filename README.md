# my_E.D.A

# Customer Database Analysis
This project is a quick Exploratory Data Analysis (EDA) on a sample of 100 customers to understand their geographic distribution, subscription trends over time, and the security standards of their web presence.

## Overview
The analysis is contained within the `Untitled1.ipynb` notebook and focuses on cleaning raw customer data and turning it into visual insights using **Pandas** and **Matplotlib**.

The workflow covers:
* **Data Integrity**: Checking for missing values and handling date-time conversions to ensure accurate time-series plotting.
* **Geographic Insights**: Identifying the top 10 countries where our subscriber base is most active.
* **Growth Trends**: Analyzing subscription volume by year (covering 2020 through 2022).
* **Security Audit**: A simple logic check on customer URLs to determine the adoption rate of **HTTPS** versus **HTTP**.

## Key Findings
* **Top Locations**: The most significant customer concentrations were found in the Solomon Islands, Dominican Republic, and Bulgaria, among others.
* **Peak Growth**: **2021** saw the highest volume of new subscriptions within the analyzed period.
* **Security Gap**: A notable **57%** of the analyzed websites are still using HTTP, while only **43%** have migrated to HTTPS.

## Tech Stack
* **Language**: Python 3
* **Libraries**: Pandas (Data Manipulation), Matplotlib (Visualization)

## Getting Started
To replicate this analysis:
1.  Ensure you have the `customers-100.csv` file in your root directory.
2.  Install the necessary dependencies:
    ```bash
    pip install pandas matplotlib
    ```
3.  Run the cells in `Untitled1.ipynb` to generate the dashboard.

---

*Note: This is an exploratory project used to demonstrate basic data processing and visualization techniques.*
