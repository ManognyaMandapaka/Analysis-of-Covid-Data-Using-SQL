# COVID-19 Data Exploration Using SQL

This project involves deep exploration of global COVID-19 data using SQL. By joining COVID-19 case and vaccination datasets, the analysis uncovers key trends in infections, mortality, and vaccination across countries and continents.

## Project Overview

Using Microsoft SQL Server, we queried, cleaned, and analyzed two key datasets:
- **CovidDeaths$**: Tracks daily COVID-19 cases and deaths by location.
- **CovidVaccinations$**: Tracks global vaccination rollout over time.

The goal was to extract insights on infection rates, death rates, and vaccination progress, and to create reusable views and tables to power future visualizations (e.g., in Power BI or Tableau).

## Data Source

- [Our World in Data](https://ourworldindata.org/covid-deaths) COVID-19 dataset
- Accessed from SQL Server database named `PortfolioProject`

## Tools Used

- SQL Server Management Studio (SSMS)
- T-SQL: CTEs, Temp Tables, Window Functions, Aggregates, Views
- Joins, Filtering, Grouping, and Ranking
- Data Cleaning (casting, null handling)

## Key SQL Concepts Applied

- **CTEs** for clean modular queries
- **Window functions** to calculate rolling vaccination metrics
- **Aggregate functions** for country-wise and global stats
- **Temp tables** for reusable intermediate results
- **Views** to support dashboard development

## Key Insights

- **Mortality Rate Analysis**: Calculated likelihood of death per infection across countries.
- **Infection Penetration**: Measured infection rate as a percentage of population.
- **Top Countries by Infection/Death**: Ranked countries by highest total cases and deaths.
- **Continent-Level Summaries**: Grouped total deaths by continent for macro-level insights.
- **Vaccination Tracking**: Tracked cumulative vaccinations per country using rolling sums.
- **Population Coverage**: Estimated percentage of each country's population vaccinated.

