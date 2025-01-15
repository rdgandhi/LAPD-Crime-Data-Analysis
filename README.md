# LAPD Crime Data Analysis

## Project Overview  
This project analyzes crime data provided by the Los Angeles Police Department (LAPD) to identify trends, patterns, and insights that can assist in understanding the dynamics of crime in Los Angeles. Leveraging Python's data manipulation, visualization, and analysis libraries, the project aims to uncover actionable insights for law enforcement, policymakers, and the general public.  

Key objectives include:  
- Understanding the distribution and frequency of crimes by type, location, and time.  
- Identifying seasonal and spatial patterns in criminal activity.   
- Developing visualizations to effectively communicate findings.  

---

## Introduction  
The LAPD collects extensive data on criminal activities across the city, which is publicly available and updated regularly. This project aims to process, explore, and analyze this data to extract meaningful insights. By leveraging Python libraries such as Pandas, Matplotlib, Seaborn, and Folium, this analysis provides a deeper understanding of crime dynamics in Los Angeles and contributes to informed decision-making.  

This repository includes the following components:  
1. **Data Exploration and Cleaning:** Preparing and validating the dataset for analysis.  
2. **Exploratory Data Analysis (EDA):** Generating summary statistics, visualizing trends, and examining relationships.  
3. **Geospatial Analysis:** Mapping crime locations to explore spatial patterns.  
4. **Key Insights and Recommendations:** Highlighting significant findings for stakeholders.  

---

## Dataset Description  
The dataset used in this project is sourced from the **Los Angeles Police Department Crime Data** and includes records of reported crimes. Below is an overview of the dataset:  

### Data Source  
- **Name:** LAPD Crime Data  
- **URL:** [LAPD Data Portal](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data)  
- **Period Covered:** 2020 to Present  
- **Update Frequency:** Monthly  

### Key Variables  
| **Column Name**    | **Description**                                                        |  
|--------------------|------------------------------------------------------------------------|  
| `DR_NO`            | Unique identifier for each crime report                                |  
| `Date Rptd`        | Date the crime was reported                                            |  
| `DATE OCC`         | Date the crime occurred                                                |  
| `TIME OCC`         | Time the crime occurred (24-hour format)                               |  
| `AREA NAME`        | Name of the LAPD division or area                                      |
| `Rpt Dist No`      | A four-digit code that represents a sub-area within a Geographic Area  |
| `Crm Cd`           | Indicates the crime committed as code                                  |
| `Crm Cd Desc`      | Description of the crime type                                          |
| `Mocodes`          | Modus Operandi                                                         |
| `Vict Age`         | Age of the victim                                                      |  
| `Vict Sex`         | Gender of the victim                                                   |  
| `Vict Descent`     | Ethnic descent of the victim                                           |  
| `Premis Cd`        | The type of structure, vehicle, or location where the crime took place |
| `Premis Desc`      | Defines the Premise Code provided.                                     |
| `Weapon Used Cd`   | The type of weapon used in the crime.                                  |
| `Weapon Desc`      | Defines the Weapon Used Code provided.                                 |
| `Status`           | Status of the case                                                     |
| `Status Desc`      | Defines the Status Code provided                                       |
| `LOCATION`         | Generalized location of the crime                                      |
| `LAT`              | Latitude coordinate for the crime location                             |  
| `LON`              | Longitude coordinate for the crime location                            |  

### Dataset Size  
- **Number of Records:** ~500,000 (as of the latest update)  
- **File Format:** CSV  


---