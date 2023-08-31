# Real Estate Data Analysis

This project involves analyzing real estate data using Snowflake, Python, Google Sheets, and Brightdata. The goal is to gather, process, and analyze data from the Otodom website and answer specific questions related to property listings.

## Architecture Overview

The project architecture consists of the following components:

- **Otodom Website**: Source of real estate data.
- **Brightdata**: Downloads and exports data to Snowflake stage.
- **Snowflake**: Cloud data warehousing platform.
- **Python Scripts**: Perform data transformations.
- **Google Sheets**: Translation and manipulation.

## Workflow Steps

### Step A: Data Collection

Visit the [Otodom Website](https://www.otodom.pl/) to understand the data available for analysis.

### Step B: Dataset Download

1. Download data from [Brightdata](https://brightdata.com/).
2. Export dataset to Snowflake stage as demonstrated in your repository.

### Step C: Snowflake Setup

1. Create a Snowflake account and install SnowSQL.
2. Set up a database and virtual warehouse in Snowflake.
3. Create a table to hold the raw JSON data.
4. Define a file format object for JSON files.
5. Create an internal stage to facilitate data loading.

### Step D: Data Transformation

1. Load data from the stage into the Snowflake table.
2. Flatten the JSON data into a structured table.
3. Use Python to fetch addresses for location coordinates.
4. Translate titles from Polish to English using Python and Google Sheets.

### Step E: Data Analysis

1. Create a table with transformed data, including additional columns like price_new and surface_new.
2. Categorize properties as apartments or non-apartments based on specific criteria.
3. Perform various analysis tasks using SQL queries on the transformed data.

## Analysis and Questions

The project aims to answer several questions using the transformed data, which is provided in three parts in this repository:

1. Average rental prices for different-sized apartments in major cities.
2. Apartments matching specific size and price criteria in Warsaw suburbs.
3. Average rental prices for different apartment sizes in major cities.
4. Most expensive apartments in major cities, along with details.
5. Percentage of private & business ads on Otodom.
6. Average sale prices for apartments of a specific size range.
7. Average rental prices in Warsaw suburbs by apartment size.
8. Luxurious neighborhoods based on high-cost apartments.
9. Most affordable neighborhoods for small families in Warsaw.
10. Neighborhoods with the most and least private ads in Warsaw.
11. Average rental and sale prices in major Polish cities.

## Conclusion

The Real Estate Data Analysis project utilizes Snowflake, Python, Google Sheets, and Brightdata to gather, transform, and analyze real estate data from the Otodom website. The workflow involves data collection, transformation, and analysis, leading to insights into the Polish real estate market.





