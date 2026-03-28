# Power-bi-dashboard
The goal of this is to create a Power BI dashboard that allows users to track
COVID-19 cases and vaccination progress across different states and countries. The dataset
contains information on confirmed cases, recoveries, deaths, vaccination totals, and other
relevant statistics.
Data Sources Description:
1. Raw COVID-19 Case Data (raw_data_Indian_states.csv):
○ Date: The date of the data entry.
○ State: The state in India.
○ Confirmed: Total confirmed cases of COVID-19.
○ Recovered: Total recoveries from COVID-19.
○ Deceased: Total deaths due to COVID-19.
○ Other: Other factors like quarantined or under observation.
○ Tested: Total number of tests conducted.
2. Vaccination Data (vaccination-data.csv):
○ Country: The name of the country.
○ ISO3: Country code.
○ WHO_REGION: The WHO region the country belongs to (e.g., EMRO, EURO,
AFRO).
○ DATA_SOURCE: The source of vaccination data (reporting or official).
○ DATE_UPDATED: The date the data was updated.
○ TOTAL_VACCINATIONS: Total number of vaccine doses administered.
○ PERSONS_VACCINATED_1PLUS_DOSE: Number of people vaccinated with at
least one dose.
○ TOTAL_VACCINATIONS_PER100: Total vaccinations per 100 people.
○ PERSONS_VACCINATED_1PLUS_DOSE_PER100: Number of people with at
least one dose per 100.
○ PERSONS_FULLY_VACCINATED: Total number of people fully vaccinated.
○ PERSONS_FULLY_VACCINATED_PER100: Number of people fully vaccinated
per 100.
VACCINES_USED: List of vaccines used in the country.
○ FIRST_VACCINE_DATE: The date when vaccination started in the country.
○ NUMBER_VACCINES_TYPES_USED: Number of different vaccine types used.
3. Case Time Series (case_time_series.csv):
○ Date: Date of the data entry.
○ Date_YMD: The date in YMD format.
○ Daily Confirmed: Number of confirmed cases reported that day.
○ Total Confirmed: Cumulative total confirmed cases up to that date.
○ Daily Recovered: Number of recoveries reported that day.
○ Total Recovered: Cumulative total recoveries up to that date.
○ Daily Deceased: Number of deaths reported that day.
○ Total Deceased: Cumulative total deaths up to that date.
Task Description:
1. Data Import and Transformation:
○ Import all three datasets into Power BI.
○ Perform data cleaning where necessary (e.g., handling missing data, date format
conversions).
○ Merge datasets based on common fields like Date or State for Indian data and
Country for global vaccination data.
2. Data Model:
○ Create relationships between the datasets (e.g., link vaccination data with
time-series case data using the Date field).
○ Ensure the model is optimized for analysis.
3. Dashboard Creation:
○ KPIs (Key Performance Indicators):
■ Total Confirmed Cases: Sum of confirmed cases.
■ Total Recoveries: Sum of recovered cases.
■ Total Deaths: Sum of deceased cases.
■ Total Vaccinations Administered Globally: Sum of vaccinations
administered globally.
■ Fully Vaccinated Population Percentage: Percentage of fully
vaccinated people globally and by country.
○ Visualizations:
■ Line Chart: Show the trend of confirmed, recovered, and deceased cases
over time.
■ Bar Chart: Display confirmed cases and recoveries by state/country.
■ Map Visualization: Use a map to show vaccination progress and
COVID-19 cases by country.
■ Pie/Donut Chart: Display the distribution of vaccine types used globally
or within a country.
■ Gauge/Target: Show vaccination progress as a percentage of the total
population (goal is to achieve 100% vaccination).
Filters and Slicers:
○ Create slicers for Date, Country, State, and WHO Region to allow dynamic
filtering of the data.
○ Enable filters to view specific time periods (e.g., monthly or weekly trends).
5. Interactions:
○ Ensure that visuals interact with each other, allowing users to select a country,
state, or time range and see how it affects all other data on the dashboard.
Expected Deliverables:
1. Power BI Dashboard:
○ The dashboard should include all KPIs and visualizations, clearly showing trends
in COVID-19 cases and vaccination data.
○ The dashboard should be interactive and provide clear insights into the spread of
COVID-19 and vaccination progress globally and within India.
2. Report:
○ A short explanation of the visualizations used.
○ Justifications for the chosen KPIs.
○ Insights derived from the data (e.g., trends, anomalies, etc.).
Evaluation Criteria:
● Data Cleaning and Transformation: Proper handling of missing data, date formats, and
data merges.
● Dashboard Design: User-friendly layout, clear visualization of KPIs, and effective use of
filters and slicers.
● Insights and Analysis: Ability to generate meaningful insights from the data.
● Use of Power BI Features: Effective use of various Power BI functionalities such as
relationships, calculated columns, measures, and visual interactions.
Suggested Timeline(20 Days):
● Data Import and Cleaning: 2 days
● Data Modeling: 3 day
● Dashboard Design and Visualization: 11 days
● Report Writing: 4 day
Target Skills:
● Data Import and Data Cleaning in Power BI
● Data Modeling and Relationships
● Visualizations: Line charts, Bar charts, Maps, Pie charts, Gauge charts
● KPIs and Calculations
● Filters and Slicers
● Interactive Dashboard Design

Datasets :  
1.   Vaccination data : https://1drv.ms/x/c/e13aa2cccc0d16d0/IQApWp0xTVu2TazyD0ndaPJ8AaR8Oy4bsS6i7U5PKPHcOXg?e=1Ouj5D
2.   Raw data indian states : https://1drv.ms/x/c/e13aa2cccc0d16d0/IQDivOWCKbCtQIEV-tPZZgvmAeKLmAk7PlaXnFHhxnzzoAc?e=fvq2x3
3.   case time series : https://1drv.ms/x/c/e13aa2cccc0d16d0/IQAyqVus9q83SbjK55dW1NimAVmmO4HdzjT9y-hkE7lvifs?e=FovtFM
4. 
