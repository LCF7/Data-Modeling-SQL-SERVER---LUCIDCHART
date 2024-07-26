# Real Estate Data Modeling Project

## Overview

This project involved data modeling using Lucidchart and SQL SERVER to model and normalize a table containing real estate data into the following dimensions:

- **Home Type**
- **Province**
- **City**
- **Location**
- **Property Status**
- **Date**

The goal was to prepare the data for use with BI tools such as Power BI and Tableau.

![Data Model](https://drive.google.com/uc?export=view&id=15sIoBPrjX0DQS7-myD1dHWPbcHXvUwXW) 

## Project Steps

1. **Database and Schema Creation**
   - Created the database and defined schemas for raw and staging data.

2. **Dimension Tables Creation**
   - Created dimension tables for home type, province, city, location, property status, and date.
   - Populated the dimension tables with distinct values from the raw data.

3. **Fact Table Creation**
   - Created a fact table to store the real estate listings with references to the dimension tables.
   - Inserted data into the fact table by joining the raw data with the dimension tables.

4. **Data Population and Testing**
   - Inserted and tested data in each of the dimension and fact tables to ensure accuracy and completeness.

![Data Model](https://drive.google.com/uc?export=view&id=1fw2APwGriwySzghAHcuanhchFocFV9Ue) 
![Data Model](https://drive.google.com/uc?export=view&id=1h0KYgWQtSDyLgh29dBvDg_e8LVbwlcco)

## Data Model

The data model consists of the following tables:

- **dim_home_type**
- **dim_province**
- **dim_city**
- **dim_location**
- **dim_property_status**
- **dim_date**
- **fact_listing**

### PowerBI:
![Data Model](https://drive.google.com/uc?export=view&id=1dJJOzQ2Y_kdKLKwR2p8q0EIqlpDIqfAC) 

### Tableau:
![Data Model](https://drive.google.com/uc?export=view&id=1DylnkiqKkdtL7AHWW-lKxV3y14zWJvf8)

Each table was carefully designed to ensure proper normalization and to support efficient querying and reporting.

## Objective

The objective of this project was to have the data ready for connection to BI tools like Power BI and Tableau, enabling detailed and dynamic real estate analysis.

## Usage

To use this data model:

1. Connect your BI tool (Power BI, Tableau) to the database.
2. Use the dimension and fact tables to create insightful visualizations and reports.
3. Explore various aspects of the real estate market using the prepared data.


