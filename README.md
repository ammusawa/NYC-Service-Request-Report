# NYC Service Request Analysis Overview

The NYC Service Request System dataset captures public complaints submitted to various agencies in New York City. This project demonstrates data cleaning, transformation, and visualization using Power BI, providing actionable insights into complaint trends and patterns across agencies, complaint types, and boroughs.

## Tools & Technologies

- **Power BI Desktop** – for data cleaning, transformation, and visualization
- **Power Query** – to handle missing data, trim text, and remove duplicates
- **Charts & Dashboards** – bar charts, line charts, and KPI cards to summarize insights

## Data Cleaning & Transformation

The dataset was processed in Power BI with the following steps:

- **Handle missing values** – Replaced blanks and nulls with 'Unknown' or removed rows as appropriate.
- **Trim spaces and clean text** – Ensured consistent formatting for all text columns.
- **Fix data types** – Converted numeric and date columns to proper types.
- **Remove negative values** – Only valid complaints were retained.
- **Remove duplicates** – Ensured each record is unique.

After cleaning, the data was ready for analysis and visualization.

## Dashboard Insights

- The **NYPD** received the highest number of complaints overall (63,393), indicating it is the most frequently contacted agency.
- The most recurring complaint type over time was **Heat/Hot Water**, peaking at 2,948 cases on the 13th, mostly directed to HPD.
- On **13 December 2019**, complaint volume to the NYPD rose to 3,734, with **Noise – Residential** leading at 1,149 complaints.
- **Queens** accounted for the largest share of complaints to the NYPD, contributing 63.36% (17,842 complaints), making it the dominant borough in complaint volume.

## Visualizations

The Power BI dashboard includes:

- **Bar charts** – Total complaints by agency, complaints by product/issue type
- **Line charts** – Complaint trends over time
- **KPI cards** – Key metrics like total complaints, highest complaint category, and dominant borough
- **Slicers** – For Specification

These visualizations provide a clear, interactive overview of the complaint patterns and trends across NYC.

## Purpose

This project helps city administrators and analysts:

- Monitor complaint volumes and types by agency and borough
- Identify trends in recurring complaints
- Allocate resources efficiently and improve response time
- Make data-driven operational decisions

## Project Outcome

A fully cleaned, transformed, and visualized dataset with actionable insights for the NYPD, HPD, and other NYC agencies.
