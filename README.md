# Beyond the Numbers: Exploring Casualties and Humanitarian Conditions in Gaza (2023–2026)

## Overview

This project presents an Exploratory Data Analysis (EDA) of conflict-related casualties, humanitarian indicators, and infrastructure damage in Gaza between October 2023 and May 2026.

The analysis examines trends in reported deaths, injuries, famine-related deaths, aid-seeker casualties, and damage to critical infrastructure such as residential buildings, educational facilities, and places of worship.

The goal of this project is to transform raw humanitarian data into meaningful insights that help understand the scale and evolution of the crisis over time.

---

## Dataset Source

This dataset is based on data published by **Tech for Palestine**.

Original source:

https://data.techforpalestine.org/

The data is publicly available through the Tech for Palestine Data API and contains regularly updated humanitarian indicators related to the Gaza conflict.

---

## Project Objectives

The analysis aims to answer questions such as:

* How have deaths and injuries evolved throughout the conflict?
* Which periods experienced the highest casualty counts?
* What proportion of reported deaths were women and children?
* When did famine-related deaths begin to emerge?
* Is there a relationship between famine-related deaths and aid-seeker casualties?
* How has infrastructure destruction evolved over time?
* What patterns exist between casualties and the destruction of educational and residential buildings?

---

## Dataset Features

The dataset includes information on:

### Casualties

* Daily deaths
* Cumulative deaths
* Daily injuries
* Cumulative injuries
* Children deaths
* Women deaths

### Humanitarian Indicators

* Famine-related deaths
* Child famine deaths
* Aid-seeker deaths
* Aid-seeker injuries

### Professional Casualties

* Medical personnel deaths
* Journalist deaths
* Civil defense personnel deaths

### Infrastructure Damage

* Residential buildings destroyed
* Educational buildings destroyed
* Educational buildings damaged
* Mosques destroyed
* Mosques damaged
* Churches destroyed
* Civic buildings destroyed

---

## Data Cleaning

The following preprocessing steps were performed:

* Converted `report_date` to datetime format.
* Set `report_date` as the dataset index.
* Standardized column naming conventions.
* Investigated missing values and reporting inconsistencies.
* Evaluated differences between reported and extrapolated indicators.
* Assessed data quality issues related to cumulative and daily metrics.

---

## Exploratory Data Analysis

### Univariate Analysis

The analysis explored:

* Reporting sources and reporting periods.
* Daily and cumulative deaths.
* Daily and cumulative injuries.
* Distribution of deaths and injuries.
* Women and children casualty proportions.
* Famine-related deaths.
* Aid-seeker deaths and injuries.

### Bivariate Analysis

Relationships explored include:

* Famine-related deaths vs aid-seeker deaths.
* Daily deaths vs daily injuries.
* Educational building destruction vs cumulative deaths.
* Residential building destruction vs cumulative deaths.
* Correlation analysis among humanitarian and casualty indicators.

---

## Key Findings

* Daily deaths and injuries showed substantial variability with several extreme spikes throughout the conflict.
* Women and children accounted for a significant proportion of reported fatalities.
* Famine-related deaths and aid-seeker deaths increased sharply during the same period, indicating worsening humanitarian conditions.
* Educational infrastructure experienced significant destruction, particularly during the early stages of the conflict.
* Residential destruction increased dramatically alongside rising casualty counts.
* Strong correlations were observed among several cumulative humanitarian indicators, although these relationships should be interpreted cautiously due to the cumulative nature of the variables.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---


## Final Note

This project is an exercise in data analysis, but the data represents real people and real communities affected by conflict.

Behind every observation is a human story. The figures presented throughout this analysis are not merely statistics; they reflect lives lost, families affected, communities displaced, and futures disrupted.

Understanding the data is important, but remembering the people behind the data is equally important.
