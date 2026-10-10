# Advanced Election Dashboard --- India General Election 2024

An interactive Power BI dashboard for exploring Indian general election
results at constituency, state, and party levels. The project includes a
Power BI report, five CSV datasets, and a written project report.

## Project contents

``` text
Election Dashboard/
├── DVI_LabDash.pbix
├── Final Report.docx
└── DATASETS/
    ├── ConstituencyWiseDetails.csv
    ├── ConstituencyWiseResults.csv
    ├── PartyWiseResults.csv
    ├── States.csv
    └── StatewiseResults.csv
```

## Dashboard scope

The dashboard is designed to analyze election outcomes across India's
543 Lok Sabha constituencies, including:

-   Constituency-level election results
-   Party-wise seats and performance
-   Vote shares and winning margins
-   State-wise comparisons
-   Map-based constituency exploration
-   KPI cards and comparative charts
-   Interactive filters and drill-downs

The dashboard uses Power Query to prepare and combine data and DAX
measures for dynamic metrics and visualizations.

## Dataset files

  -----------------------------------------------------------------------
  File                                Purpose
  ----------------------------------- -----------------------------------
  `ConstituencyWiseDetails.csv`       Constituency-level details used for
                                      detailed exploration

  `ConstituencyWiseResults.csv`       Constituency-level election results

  `PartyWiseResults.csv`              Party-level result summary

  `States.csv`                        State reference data

  `StatewiseResults.csv`              State-level result summary
  -----------------------------------------------------------------------

The CSV files are supplied with this project. Exact column definitions
and relationships should be checked in Power BI's data/model views and
in the accompanying `Final Report.docx`.

## Tools used

-   **Microsoft Power BI Desktop** --- report and interactive dashboard
-   **Power Query** --- data import, cleaning, and transformation
-   **DAX** --- calculated measures and dynamic KPIs
-   **CSV** --- structured source datasets

## Open the dashboard

1.  Download or clone this repository.
2.  Keep the `DATASETS` folder and its CSV files together.
3.  Open `DVI_LabDash.pbix` in Power BI Desktop.
4.  If Power BI reports missing source files, update the data-source
    paths in **Transform data → Data source settings** to point to the
    CSV files in your local `DATASETS` folder.
5.  Select **Refresh** to reload the data.
6.  Explore the report using its filters, map, KPI cards, and charts.

Power BI Desktop is required to edit the `.pbix` report. Viewing or
editing may require the local source CSV files and a compatible Power BI
environment.

## Repository notes

-   `Final Report.docx` contains the accompanying written project
    report.
-   This repository describes an analytics and visualization project; it
    is not an official election-results service.
-   Confirm source attribution, dataset provenance, and redistribution
    permissions before republishing the datasets or the report publicly.
