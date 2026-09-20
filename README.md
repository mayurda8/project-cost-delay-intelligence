# Project Cost & Delay Intelligence

## Project Overview

Project Cost & Delay Intelligence is a data analytics portfolio project developed using a simulated project risk and earned-value dataset covering 4,000 projects.

The project explores project cost performance, schedule delays, risk categories and forecast cost overruns. Python was used for data preparation, analysis and visualisation, with the results presented through dashboard-style visuals.

The objective was to examine project performance indicators and demonstrate how data analytics can support project monitoring and more informed decision-making.

> **Note:** This is an independent portfolio project using simulated data. It is not an internal Sandvik project or a production project management system.

## Key Findings

The analysis of 4,000 simulated projects identified the following:

| Metric                                                       |          Result |
| ------------------------------------------------------------ | --------------: |
| Projects analysed                                            |           4,000 |
| Projects experiencing delays                                 |  2,448 (61.20%) |
| Projects over budget                                         |  3,395 (84.88%) |
| Projects both delayed and over budget                        |  2,110 (52.75%) |
| Average schedule delay                                       |     0.99 months |
| Average cost overrun per project                             |      $72,518.30 |
| Total planned budget                                         |   $4.57 billion |
| Total actual cost                                            |   $4.86 billion |
| Net cost difference                                          | $290.07 million |
| Average forecast overrun among projects forecast over budget |           7.59% |
| Median cumulative CPI                                        |           0.948 |

These findings describe the supplied simulated dataset and should not be interpreted as estimates of real-world project performance.

## Project Objectives

* Analyse project cost and schedule performance.
* Identify patterns in project delays and cost overruns.
* Compare outcomes across project types and risk categories.
* Explore Earned Value Management indicators, including CPI and SPI.
* Estimate forecast cost at completion and variance at completion.
* Create clear visualisations to communicate findings.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* Power BI (dashboard development)

## Dataset

The project uses a simulated project risk and earned-value dataset containing project-level information and monthly earned-value metrics.

The analysis includes 4,000 unique projects. The earned-value dataset contains monthly records used to calculate and examine cumulative performance metrics.

The data is not real company or operational data.

Dataset source and access details should be provided here, subject to the dataset provider's licence and redistribution terms.

## Methodology

### 1. Data Preparation

* Loaded the project risk, project outcome and earned-value datasets.
* Prepared the tabular data for analysis.
* Checked project identifiers, record counts and missing values.
* Combined project-level risk and outcome information.

### 2. Exploratory Data Analysis

* Examined project delays and cost overruns.
* Compared project performance across project types.
* Analysed delay and over-budget percentages by risk category.
* Visualised the relationship between schedule delay and cost overrun.

### 3. Earned Value Analysis

* Examined Planned Value (PV), Earned Value (EV) and Actual Cost (AC).
* Analysed cumulative Cost Performance Index (CPI) and Schedule Performance Index (SPI).
* Calculated Estimate at Completion (EAC) and Variance at Completion (VAC).
* Examined forecast cost overruns across the project portfolio.

### 4. Visualisation

Created charts to communicate:

* Forecast cost overrun distribution.
* Cumulative CPI distribution.
* Average and median forecast overruns by project type.
* Delays and over-budget rates by risk level.
* Schedule delay versus cost overrun.
* Projects with the largest forecast cost overruns.

## Forecasting Approach

The project uses cumulative CPI-based estimates to explore forecast cost performance.

The Estimate at Completion (EAC) is calculated using the project's planned budget and cumulative cost performance. Forecast overrun percentages are then used to compare estimated cost against planned budget.

These values are model-based estimates derived from the simulated data and its assumptions. They are not guaranteed final costs.

## Visualisations

The dashboard image and analysis charts are available in the `dashboard/` folder.

The visualisations are intended to make project performance patterns easier to explore and communicate.

## Limitations

* The dataset is simulated and may not represent real project environments.
* Findings depend on the dataset's assumptions, distributions and construction.
* Relationships observed in the charts do not establish causation.
* Risk categories should not be interpreted as direct predictors of project outcomes.
* CPI-based cost forecasts depend on the assumption that observed cost efficiency remains relevant to future work.
* The available SPI values are effectively constant at 1.0 in the final project-level records, limiting their usefulness for comparing schedule performance in that view.
* The project is an analytical prototype, not a deployed forecasting or project-control system.
* Results should not be generalised to actual organisations without validation against suitable real-world data.

## Repository Structure

```text
project-cost-delay-intelligence/
├── README.md
├── notebooks/
│   └── project_cost_delay_analysis.ipynb
├── dashboard/
│   ├── ProjectCost_Delay_Intelligence_LinkedIn_Dashboard.png
│   └── project_cost_delay_dashboard.pbix
├── data/
│   └── README.md
├── outputs/
│   └── ProjectCost_Delay_Intelligence.csv
└── .gitignore
```

Files should only be included where they are available and permitted for public sharing.

## Skills Demonstrated

* Data cleaning and validation
* Exploratory data analysis
* Project cost and schedule analysis
* Earned Value Management
* KPI analysis
* Data visualisation
* Python and Pandas
* Dashboard development
* Communicating analytical findings and limitations

## Author

Mayur Prakash Gaikwad

Project Engineer | Data Analytics | Python | Power BI
