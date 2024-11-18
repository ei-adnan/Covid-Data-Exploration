# Covid-Data-Exploration

The **Covid Data Exploration** is a data analysis project focusing on exploring and interpreting global trends related to the COVID-19 pandemic. This project involves working with two datasets, **CovidDeaths.xlsx** and **CovidVaccinations.xlsx**, which were pre-processed in Microsoft Excel and subsequently loaded into a Microsoft SQL Server database for comprehensive analysis and visualization.

---

## Project Structure

The repository includes the following key files:

- **CovidDeaths.xlsx**: Dataset detailing global COVID-19 death statistics.
- **CovidVaccinations.xlsx**: Dataset capturing global COVID-19 vaccination statistics.
- **COVID-Data-Exploration.sql**: SQL queries used to explore and analyze the datasets.
- **Query For Tableau Visualization.sql**: SQL queries designed to prepare the data for visualization in Tableau.

---

## Visual Representation

Explore the interactive Tableau dashboard created as part of this project:

[COVID-19 Data Exploration Dashboard](https://public.tableau.com/views/CovidDataExploration_17319420817670/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

- The Tableau dashboard provides an intuitive visual representation of key insights from the COVID-19 datasets.
- It also allows users to interact with the data, explore trends, and gain a deeper understanding of the global impact of the pandemic.
## Data Exploration Overview

---

The **COVID-Data-Exploration.sql** file contains a series of SQL queries developed to uncover insights about the COVID-19 pandemic. These queries were executed in Microsoft SQL Server Management Studio and helped generate insights that serve as a foundation for data visualizations.

### Key Analysis Steps

1. **Initial Data Review**:
   - Basic queries to inspect and order data from the `CovidDeaths` and `CovidVaccinations` tables.

2. **Death Rate Analysis**:
   - Calculated death rates as a percentage of total cases.
   - Assessed the proportion of the population infected with COVID-19.

3. **Country-Level Insights**:
   - Identified countries with the highest infection rates relative to their populations.
   - Highlighted countries with the highest death counts per capita.

4. **Global and Continental Trends**:
   - Analyzed data to determine the severity of the pandemic across different regions.
   - Compared total deaths and deaths per population by continent to provide a global perspective.

---

## Usage

To use this project, you will need to have Microsoft SQL Server installed. You can then download the **CovidDeaths.xlsx** and **CovidVaccinations.xlsx** datasets, clean them in Excel, and load them into the SQL Server. Finally, you can run the SQL queries from the **COVID-Data-Exploration.sql** file to explore the data.
