# Strait of Hormuz Supply Chain Analytics

## Project Overview

The Strait of Hormuz is a critical maritime chokepoint for global oil and gas transportation. Its strategic importance makes shipping activity, petroleum flows, and supply disruptions in the region significant areas of oil and gas supply chain analysis.

This project focuses on analyzing supply chain risks and operational performance associated with the Strait of Hormuz using data analytics. It aims to explore petroleum transportation patterns, assess potential supply disruptions, and examine the implications of maritime and logistics constraints for global energy supply chains.

## Business Problem

The Strait of Hormuz is facing a major oil and gas supply chain disruption amid escalating regional conflict, attacks on commercial vessels, and uncertainty surrounding maritime access. These developments have reduced shipping activity and disrupted petroleum movements through one of the world's most strategically important energy transportation corridors.

For oil and gas supply chains, these disruptions create challenges involving crude oil and liquefied natural gas (LNG) transportation, tanker availability, shipping schedules, alternative export routes, logistics costs, and the reliability of international energy supplies. Recent reporting also highlights the role of alternative transportation arrangements in helping maintain some regional oil exports despite constraints around the Strait.

The central business problem is understanding how instability around the Strait of Hormuz affects oil and gas transportation flows, supply chain continuity, and operational performance, using available historical and current data.

This project will investigate the following questions:

- **Maritime transportation:** How has vessel traffic through the Strait changed during the current disruption compared with the pre-disruption period?
- **Petroleum flows:** How have crude oil and petroleum product movements through the Strait changed over time?
- **Supply chain disruption:** What differences can be observed between normal operating periods and periods of heightened disruption?
- **Alternative logistics routes:** What role do alternative export routes and transportation arrangements play in maintaining petroleum flows?
- **Energy supply risk:** What do observed changes in shipping activity and petroleum flows indicate about potential risks to global oil and gas supply chains?
- **Operational decision-making:** How can data analytics help monitor transportation disruptions, identify emerging risks, and support more informed supply chain planning?

The project will use SQL, Python, Pandas, and Power BI to assess available datasets, measure changes in relevant supply chain indicators, and present evidence-based findings. Conclusions will be limited to what the available data can support.

## Project Objectives

The primary objective of this project is to apply data analytics to evaluate the impact of disruptions around the Strait of Hormuz on oil and gas supply chains, maritime transportation, and energy supply reliability.

The specific objectives are to:

1. **Analyze Maritime Activity:** Examine available vessel traffic data to identify changes in shipping activity through the Strait of Hormuz over time.

2. **Assess Petroleum Flow Patterns:** Analyze available crude oil and petroleum product flow data to understand transportation trends and identify significant changes during disruption periods.

3. **Measure Supply Chain Disruptions:** Compare selected supply chain indicators before, during, and after documented disruption periods, where reliable data is available.

4. **Evaluate Alternative Transportation Routes:** Investigate the role of alternative pipelines, export terminals, and transportation corridors in maintaining regional petroleum flows.

5. **Identify Supply Chain Risks:** Examine potential vulnerabilities related to maritime transportation, route concentration, export dependency, and interruptions to energy supply.

6. **Perform Data Quality Assessment:** Evaluate the completeness, consistency, validity, and reliability of the datasets before conducting analysis.

7. **Develop Supply Chain Performance Indicators:** Calculate relevant metrics to monitor shipping activity, petroleum flows, changes in transportation patterns, and disruption severity, depending on data availability.

8. **Build an Interactive Power BI Dashboard:** Present key metrics, trends, comparisons, and findings through visualizations that support oil and gas supply chain monitoring and decision-making.

The final objective is to produce a reproducible, data-driven analysis that demonstrates how SQL, Python, Pandas, and Power BI can be applied to real-world oil and gas supply chain challenges.

## Scope of Analysis

This project focuses on the analysis of oil and gas supply chain activities associated with the Strait of Hormuz, with particular attention to maritime transportation, petroleum flows, logistics disruptions, and energy supply chain risks.

The analysis will cover the following areas:

### 1. Maritime Transportation and Vessel Activity
- Examine available vessel traffic data and changes in maritime activity through the Strait.
- Identify trends in vessel movements across different periods.
- Assess changes in shipping activity during documented disruption periods, where data permits.

### 2. Oil and Gas Transportation Flows
- Analyze available data on crude oil, petroleum products, and liquefied natural gas (LNG) transportation.
- Examine historical flow patterns and significant changes over time.
- Assess the potential implications of observed flow changes for energy supply chains.

### 3. Supply Chain Disruption Analysis
- Establish a baseline using suitable pre-disruption data.
- Compare baseline conditions with documented disruption periods.
- Measure changes in available transportation and petroleum flow indicators.

### 4. Alternative Transportation Routes
- Identify relevant alternative pipelines, export terminals, and transportation corridors.
- Examine available evidence of their role in regional petroleum transportation.
- Assess the limitations of alternative routes where reliable capacity and flow data are available.

### 5. Supply Chain Risk and Operational Performance
- Examine exposure to transportation chokepoints and interruptions to maritime movement.
- Develop measurable indicators of shipping activity and petroleum flow changes.
- Identify potential operational and logistics risks supported by the available evidence.

### 6. Data Analytics and Visualization
- Use Python and Pandas for data exploration, preparation, and analysis.
- Use SQL/MySQL for structured queries, comparisons, and KPI calculations.
- Use Power BI to present findings through interactive dashboards.
- Document data sources, analytical methods, assumptions, and limitations.

### Project Boundaries

This project is an analytical study of oil and gas supply chains connected to the Strait of Hormuz. It is not intended to provide real-time maritime surveillance, predict military actions, or establish the precise financial impact of disruptions without supporting data.

The availability, geographic coverage, time range, and quality of each dataset will determine the final analyses and metrics. Any estimates or comparisons will be clearly identified, and findings will not be presented as confirmed operational facts unless supported by reliable evidence.

## Data Sources

This project will use credible public and institutional data sources to investigate oil and gas supply chain disruptions associated with the Strait of Hormuz. The selected sources will support the analysis of petroleum transportation flows, maritime activity, historical trends, and alternative energy transportation routes.

### 1. World Trade Organization (WTO) — Strait of Hormuz Trade Tracker

**Source:** https://datalab.wto.org/Strait-of-Hormuz-Trade-Tracker

**Purpose:**
- Examine shipment trends for crude oil, natural gas, and other relevant commodities.
- Identify changes in observed shipment activity during disruption periods.
- Compare recent shipping patterns with the available historical baseline.

**Data considerations:** The tracker uses vessel-tracking data based on Automatic Identification System (AIS) transmissions. Shipments may be missed when vessels stop transmitting AIS. The availability of downloadable data for independent analysis will be verified.

### 2. U.S. Energy Information Administration (EIA)

**Source:** https://www.eia.gov/international/analysis/special-topics/World_Oil_Transit_Chokepoints

**Purpose:**
- Establish historical benchmarks for oil and petroleum product transportation through the Strait.
- Examine the Strait's importance to global energy supply chains.
- Investigate alternative pipeline routes and their potential role in reducing transportation dependence on the Strait.

**Data considerations:** Published estimates may cover specific historical periods rather than provide daily, real-time operational data. The relevant reporting periods and measurement units will be documented.

### 3. International Monetary Fund (IMF) — PortWatch

**Source:** https://portwatch.imf.org/

**Purpose:**
- Investigate vessel transit activity through the Strait of Hormuz.
- Compare maritime activity across selected time periods.
- Develop baseline comparisons and monitor changes in vessel traffic.

**Data considerations:** Vessel counts and estimated shipping capacity are not equivalent to actual oil or gas volumes transported. Data coverage, reporting delays, and available download formats will be verified before analysis.

### Data Selection and Preparation

The final datasets will be selected based on relevance to the business problem, historical coverage, availability, data quality, and suitability for independent analysis.

Data preparation will include:
- Recording source names, source links, and retrieval dates.
- Assessing data structure, missing values, duplicates, and inconsistencies.
- Standardizing dates, measurement units, and relevant categorical fields.
- Documenting assumptions, limitations, and any transformations applied.

Only data that can be verified and appropriately interpreted will be used to calculate supply chain indicators or support project conclusions.

## Tools and Technologies

The project will use a combination of data analysis, database querying, data preparation, and visualization tools to investigate oil and gas supply chain disruptions around the Strait of Hormuz.

### 1. Python
**Purpose:** Data analysis and workflow automation.

Python will be used to load available datasets, explore maritime and petroleum flow data, perform analytical calculations, and automate repeatable data processing tasks where appropriate.

### 2. Pandas
**Purpose:** Data preparation and manipulation.

Pandas will be used to inspect data structures, assess data quality, handle inconsistencies where justified, standardize data fields, and prepare datasets for analysis.

### 3. SQL / MySQL
**Purpose:** Structured data analysis and KPI calculation.

MySQL will be used to store structured datasets, query historical records, compare maritime activity across selected periods, aggregate petroleum flow indicators, and calculate relevant supply chain performance metrics.

### 4. Power BI
**Purpose:** Interactive reporting and visualization.

Power BI will be used to develop an interactive dashboard showing relevant trends, period comparisons, petroleum transportation indicators, and supply chain disruption measures supported by the available data.

### 5. Git and GitHub
**Purpose:** Version control and project documentation.

Git and GitHub will be used to track project development, organize scripts and documentation, maintain analytical transparency, and present the completed portfolio project.

### Analytical Workflow

1. **Data acquisition:** Retrieve relevant datasets from verified public and institutional sources.
2. **Data exploration:** Inspect dataset structure, coverage, variables, and measurement units.
3. **Data quality assessment:** Investigate missing values, duplicates, inconsistent records, and potential anomalies.
4. **Data preparation:** Clean and standardize data where justified by documented findings.
5. **Database development:** Load suitable structured datasets into MySQL.
6. **Supply chain analysis:** Use SQL and Python to investigate trends, compare periods, and calculate relevant indicators.
7. **Dashboard development:** Build Power BI visualizations to communicate evidence-based findings.
8. **Documentation:** Record data sources, analytical decisions, limitations, and business insights.

## Key Performance Indicators (KPIs)

This project will develop and analyze relevant indicators to assess maritime transportation activity, petroleum flows, and oil and gas supply chain disruption around the Strait of Hormuz.

The final KPIs will depend on the availability, quality, and level of detail of the selected datasets.

### 1. Maritime Transportation KPIs

- **Vessel Transit Count:** Number of observed vessel transits through the Strait over a defined period.
- **Vessel Transit Change (%):** Percentage change in observed vessel transits compared with a selected baseline period.
- **Average Daily Vessel Transits:** Average number of observed transits per day during the analysis period.
- **Disruption-Period Transit Change:** Difference between observed vessel activity during a documented disruption period and the selected baseline.

### 2. Oil and Gas Flow KPIs

- **Estimated Petroleum Transit Volume:** Estimated quantity of petroleum transported through the Strait over a defined period, where reliable volume data is available.
- **Oil Flow Change (%):** Percentage change in reported oil transit volumes relative to a selected baseline.
- **LNG Transit Activity:** Observed or reported LNG shipment activity, depending on the available dataset.
- **Petroleum Flow Trend:** Changes in reported petroleum transportation volumes over time.

### 3. Supply Chain Disruption KPIs

- **Transit Disruption Index:** Relative change in observed vessel transits compared with a defined historical baseline.
- **Baseline-to-Disruption Difference:** Absolute difference between baseline and disruption-period measurements.
- **Disruption Duration:** Number of days in a documented disruption period, based on verified event dates.
- **Recovery in Vessel Activity:** Change in observed transit activity following a disruption, where sufficient post-disruption data is available.

### 4. Alternative Route and Supply Risk Indicators

- **Alternative Route Availability:** Identification of relevant alternative pipelines and export routes.
- **Alternative Route Capacity:** Reported transportation capacity of relevant alternatives, where reliable published estimates are available.
- **Alternative Route Utilization:** Actual or estimated use of alternative routes relative to their reported capacity, only where compatible flow and capacity data exists.
- **Chokepoint Dependence:** Assessment of the share of relevant petroleum flows associated with the Strait, where suitable comparable data is available.

### KPI Calculation Principles

- Percentage changes will use clearly defined baseline and comparison periods.
- Baseline periods will be selected using documented disruption dates and data coverage.
- Vessel counts will not be treated as direct measurements of petroleum volumes.
- Reported transportation capacity will not be treated as actual throughput.
- Missing, estimated, or incomplete data will be clearly identified.
- No KPI will be reported as a confirmed result until the underlying data has been obtained, assessed, and analyzed.

## Repository Structure

The repository will be organized into dedicated directories for data storage, data quality assessment, data preparation, SQL analysis, Python workflows, Power BI reporting, and project documentation.
strait-of-hormuz-supply-chain-analytics/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── python/
│   ├── 01_data_acquisition.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_quality_assessment.ipynb
│   └── 04_data_cleaning_and_preparation.ipynb
│
├── mysql/
│   ├── 01_database_setup.sql
│   ├── 02_maritime_traffic_analysis.sql
│   ├── 03_petroleum_flow_analysis.sql
│   ├── 04_supply_chain_kpi_calculations.sql
│   └── 05_disruption_period_comparison.sql
│
├── power_bi/
│   ├── dashboard/
│   └── screenshots/
│
├── reports/
│   ├── data_quality_report.md
│   ├── maritime_traffic_analysis.md
│   ├── petroleum_flow_analysis.md
│   └── supply_chain_risk_assessment.md
│
├── docs/
│   ├── data_sources.md
│   ├── data_dictionary.md
│   └── kpi_definitions.md
│
├── requirements.txt
└── .gitignore

###Repository Management Principles

Preserve original source data separately from prepared datasets.

Document every material data-cleaning decision.

Keep analytical scripts organized by purpose.

Avoid uploading credentials, API keys, or sensitive information.

Avoid committing large raw datasets when licensing, file-size limits, or source terms prohibit it.

Use source links and documented retrieval dates so the analysis can be traced back to its origin.
