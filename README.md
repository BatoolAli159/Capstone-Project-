# Los Angeles Crime Analysis (2020–2025)

## Project Agenda
1. Data Dictionary
2. Data Handling Summary
3. Introduction
4. Problem Statement
5. Project Approaches
6. Target Audience
7. Dataset Overview
8. Analysis and Key Findings
9. Limitations
10. Recommendations
11. References

---

## 1. Data Dictionary
| Field Name      | Data Type        | Description                         |
|-----------------|----------------|-------------------------------------|
| DR_NO           | String/Number   | Official crime record number        |
| DATE_RPTD       | Date            | Date the crime was reported         |
| DATE_OCC        | Date            | Date the crime occurred             |
| TIME_OCC        | Number          | Time of occurrence (24-hour format)|
| AREA            | Number          | LAPD area number                    |
| AREA_NAME       | String          | Name of LAPD area                   |
| ...             | ...             | ...                                 |

---

## 2. Data Handling Summary
Please refer to the [Jupyter Notebook](link-to-your-notebook) for details.

---

## 3. Introduction
Understanding crime trends is essential for supporting public safety and improving community well-being. The Crime Data from 2020 to the Present, provided by the City of Los Angeles, offers detailed information about incidents reported across the city, including crime types, locations, dates, weapon involvement, and victim demographics.

By analyzing this dataset, we can uncover patterns over time, identify areas with higher crime concentration, and observe how different factors influence criminal activity. This analysis helps reveal meaningful insights that can guide prevention strategies, resource allocation, and policy planning.

---

## 4. Problem Statement
Since 2020, the crime rate in Los Angeles has increased, reaching its peak during 2022–2023. The rise in armed crimes and incidents in public and residential areas has raised serious concerns about public safety and community security. This highlights the need to develop effective strategies for crime prevention, improve neighborhood safety, and increase public awareness.

---

## 5. Project Approaches
- When the crime happened
- Find the months or days with the most crimes
- Check if a weapon was used or not
- See which weapons are used the most
- What kind of crime it is (assault, burglary, etc.)
- Which crime happens the most
- Serious vs. less serious crimes
- Compare crime levels across areas
- Age, gender, and descent of the victim
- See which groups are most affected
- Where the crime happened
- Find hotspots and high-crime areas
- Count how many crimes for each category
- Use charts to compare crime numbers
- How the crime was done
- Remove wrong or missing values
- Make sure dates, numbers, and codes are correct

---

## 6. Target Audience
Jim McDonnell (Chief of the Los Angeles Police Department)

---

## 7. Dataset Overview
**Data Source:** Crime Data (2020–Present)  
**Data Size:** 1M+ Rows  
**Data Period:** 2020 – 2025  

**Main Dataset Features:**
- Reported Date & Crime Date
- Time of Crime
- Area / Location
- Crime Type & Code
- Crime Severity
- Weapon Used
- Victim
- How Crime Was Done (MO Codes)
- Case Status

**Supplementary Dataset Features:**
- Premises Type / Description
- Latitude & Longitude

---

## 8. Analysis and Key Findings
1. Crime rate increased over the years, peaking in 2023, then declining.
2. Trend of crimes over past five years: both open and solved cases.
3. Distribution of crimes by area: Central LA and 77th Street have the highest crime rates.
4. Number of crimes by area type: Public areas 413K, Residential 323K, Commercial 165K.
5. Property crimes are the most frequent, followed by violent crimes.
6. Serious vs. less serious crimes breakdown.
7. Crimes with and without weapons.
8. Most commonly used types of weapons: physical force, firearms, knives.
9. Time of day for crimes: peak at 12 PM.
10. Ages of victims: children and adults most affected.
11. Gender of victims: males slightly higher.
12. Race/ethnicity of victims: Mexican, White, and Black most common.

---

## 9. Limitations
- Data may not include all crimes.
- Some cases have incomplete information.
- Exact circumstances of crimes not recorded.
- Broad crime type grouping may hide trends.
- Only reported crimes are considered.

---

## 10. Recommendations
- Focus on reducing property crimes.
- Increase public awareness and safety measures during daytime.
- Targeted programs for vulnerable groups (children and adults).
- Strengthen monitoring in high-crime areas.
- Improve reporting and data collection.

---

## 11. References
1. [FBI UCR](https://www.fbi.gov/how-we-can-help-you/more-fbi-services-and-information/ucr)
2. [FBI 2024 Reported Crimes](https://www.fbi.gov/news/press-releases/fbi-releases-2024-reported-crimes-in-the-nation-statistics)
3. [SpotCrime Wikipedia](https://en.wikipedia.org/wiki/SpotCrime.com)
