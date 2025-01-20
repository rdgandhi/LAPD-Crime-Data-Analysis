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

---

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
### Key Analyses and Guiding Questions

The project addresses the following key questions:

1. Victimization Likelihood Based on Demographics.
   - What are the patterns of victimization across different age groups in Los Angeles?
   - How do patterns of victimization differ between genders in terms of crime?
   - How does the incidence and type of victimization vary across different ethnic groups in Los Angeles?
2. How safe is a specific location in Los Angeles based on crime statistics?
3. How do crime rates fluctuate over different times of the dayin Los Angeles?
4. How do crime rates fluctuate over different days of the week Los Angeles?
5. How do crime rates fluctuate over different seasons in Los Angeles?
6. What are the patterns of crime distribution across different neighborhoods in Los Angeles?
7. What are the geographic trends in the top nine crime types across various neighborhoods in Los Angeles?
8. What breakdown of crime case statuses in Los Angeles?
9. What is the percentage of closed cases across different areas of Los Angeles?

---

### Technology Used

- Python
- Jupyter Notebook
- Libraries:
  - pandas (data manipulation)
  - NumPy (numerical operations)
  - matplotlib & seaborn (data visualization)
  - plotly (interactive visualizations)
  - geopandas & folium (geographic mapping)

---

### Insights
Based on the crime data analysis across Los Angeles neighborhoods, several significant observations have surfaced that point to the necessity for more focused public safety strategies.

**Public Safety Recommendations**
- Increase patrols and enhance community engagement in regions with higher crime rates, particularly where "adult arrest" percentages are low, such as in the Central and Southeast areas.
- Establish dedicated youth programs in areas with elevated juvenile crime involvement specifically 77th Street, Foothill, and West Valley. Implement mentorship opportunities and organize activities to divert at-risk youth from criminal behavior.
- Streamline investigative methods to reduce the high number of unresolved cases (currently at 82.6%). Focus on enhancing training and adopting new technologies to improve investigative efficiency and resolution rates.
- Roll out public safety campaigns during the fall and winter months, focusing on theft and assault prevention, and adjust strategies during times of higher retail activity in the spring and summer.
- Allocate more law enforcement resources to specific days, like Fridays, when crime rates tend to spike compared to other days of the week.
- Given that crime tends to increase between 12 PM and 12 AM, residents should stay vigilant during these hours, avoiding distractions, especially in crowded public areas. Additionally, between 6 PM and 12 AM, when vehicle theft rates rise, individuals should take extra precautions, such as parking in well-lit spaces and securing belongings.

**Safety Tips for Men and Women:**
- For Men, be mindful of potentially confrontational situations, particularly in social settings, and steer clear of actions that could lead to violent escalations.
- For Women, be cautious about sharing personal information online. Strengthen privacy settings on social media to minimize risks related to identity theft.
- Targeted outreach programs for Hispanic/Mexican individuals in areas with higher crime rates can address underlying socio-economic issues and provide valuable community support.

---

### Future Scope
- **Investigating Socio-Economic Factors:** Explore the relationship between socio-economic factors, such as income levels and unemployment rates, and crime rates across the city.  
- **Formulating Key Questions:** Analyze questions like, "How do income levels and unemployment rates influence crime rates?" to identify trends and correlations.  
- **Utilizing Public APIs:** Leverage data from public APIs provided by the Los Angeles Police Department to incorporate accurate and real-time crime statistics.  
- **Developing a Dynamic Dashboard:** Create a bi-weekly updating dashboard to visualize crime data dynamically, empowering law enforcement with timely and actionable insights.  
- **Enhancing Practical Applications:** Strengthen the real-world application of the analysis by providing decision-makers with tools for proactive and informed crime prevention strategies.  
