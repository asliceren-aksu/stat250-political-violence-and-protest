# Political Violence and Protest in Türkiye — STAT 250 Term Project

**Applied Statistics · Middle East Technical University · June 2026**

We analyzed political violence and protest events recorded by ACLED in Türkiye from 2016 to 2023. The course workbook contained **32,447 rows and 31 variables**. After cleaning and consolidating repeated records by event ID, the analysis covered **22,110 events**.

[Analysis notebook](Stat250_Project_Group_11.ipynb) · [Report summary](REPORT_SUMMARY.md)

## Analysis

- Standardized categories and consolidated actor and source information at the event level.
- Compared event types, reporting coverage, population context, and reported fatalities.
- Used proportion tests, chi-square tests, Welch’s t-test and ANOVA, and regression to examine five research questions.

## Reproduce the workflow

Install the packages in `requirements.txt`. With authorized access to the original course workbook, place it beside the notebook as `Acled_Stat250.xlsx` and run the notebook in order. The cleaning cells generate the workbook used in the analysis section. A new ACLED export may differ from the original course workbook in schema and coverage.

Source: [ACLED](https://acleddata.com/). This repository contains the analysis code and aggregate findings. See [ACLED’s access guidance](https://acleddata.com/faq/how-can-i-access-and-use-acled-data) and [terms of use](https://acleddata.com/terms-use) for the data.

## Team

Hasan Akkaya · Aslı Ceren Aksu · Ahmet Genç
