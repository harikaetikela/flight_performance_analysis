# Aviation Delay Analysis (2001) Using Hadoop & Hive Project

This project analyzes U.S. airline on‑time performance for the year 2001 using Hadoop and Hive as part of the Scalable Databases course. The dataset includes millions of flight records and provides insights into arrival and departure delays across airports and carriers.

## Data Source
- Airline On‑Time Performance Data (2001)
- Harvard Dataverse (Data Expo 2009)
- Includes arrival, departure, carrier, and airport information for all U.S. commercial flights

## Methods
- Created HDFS directories and set permissions
- Downloaded datasets directly into Hadoop using URLs
- Built Hive tables for:
  - Flight data (harika2001)
  - Airports
  - Carriers
- Executed analytical HiveQL queries to compute:
  - Total arrival delay hours
  - Total departure delay hours
  - Combined delay metrics
  - Top airports and carriers by delay volume

## Key Findings
### Top 3 Airports (Total Delay Hours)
1. **ORD – Chicago O’Hare:** 111,461 hours  
2. **DFW – Dallas–Fort Worth:** 80,373.70 hours  
3. **ATL – Atlanta:** 67,940.77 hours  

### Top 3 Carriers (Total Delay Hours)
1. **UA – United Airlines:** 219,476.65 hours  
2. **WN – Southwest Airlines:** 213,070.73 hours  
3. **AA – American Airlines:** 168,831.25 hours  

### Overall Delay Trends (2001)
- Departure delays (779,681.57 hours) were **48.8% higher** than arrival delays  
- Total delay time across all flights: **1,307,046.37 hours**  
- Departure delays exceeded arrival delays by **252,316.77 hours**

## Repository Contents
- `Scalable Databases project phase 1_Harika.pptx` — Full presentation with tables, analysis, and insights

## Skills Demonstrated
Hadoop, HiveQL, big‑data processing, SQL analytics, data engineering, presentation design

