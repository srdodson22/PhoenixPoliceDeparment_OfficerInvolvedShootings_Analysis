# Officer-Involved Shootings Analysis: Phoenix Police Department (2017–2024)

## Project Type  
Graduate Analytics Project

## Problem Statement  
Police actions during suspect encounters—especially in minority communities—have been the subject of significant scrutiny. Across the U.S., there have been repeated instances where excessive force was used during arrests, some resulting in fatalities. This project explores data on officer-involved shootings (OIS) within the Phoenix Police Department from 2017 to 2024 to uncover potential racial and geographic disparities.

## Objectives  
- Analyze officer-involved shooting data to understand patterns in suspect demographics and police response  
- Identify trends by race, age, and precinct  
- Estimate population disparities using demographic data to contextualize incident rates  
- Encourage data-informed discussion around policing practices in Phoenix

---

## Datasets Used

### Officer-Involved Shooting Dataset  
**Source**: [Phoenix Open Data](https://www.phoenixopendata.com/dataset/ois)  
Details include:  
- Date and time of incident  
- Suspect age, race, and ethnicity  
- Officer race and ethnicity  
- Suspect weapon (if applicable)  
- Police precinct involved  

### Population Demographics by Precinct  
**Source**: [Statistical Atlas](https://statisticalatlas.com/place/Arizona/Phoenix/Race-and-Ethnicity)  
Demographic breakdowns (2017-2024 estimates) for:  
- Hispanic population  
- Black population  
- White population  
- Used to calculate shooting incidents per demographic group per precinct

---

## Methodology

### 🧼 Data Cleaning & Preparation
- Parsed and standardized race and ethnicity fields for comparison  
- Mapped each OIS incident to the corresponding precinct  
- Grouped and counted incidents by race, weapon type, and year  
- Merged population data to estimate per capita incident rates  

### Analysis Highlights
- Examined total and annual OIS incidents by race  
- Analyzed age distribution of suspects  
- Explored precinct-level variation in OIS frequency  
- Calculated shooting rates relative to population sizes  

---

## Important Note  
Misplaced Python notebook for suspect feature grouping due to using a free trial with Anaconda.   

---

## 🧩 Future Plans  
- Rebuild grouped demographic analysis notebook  
- Add per capita heatmaps by precinct  
- Integrate mapping tools for geographic visualizations  
- Explore officer-level patterns (e.g., repeat involvement, demographic comparisons)

---

## Project Link   
Project: [PPD_OIS_Analysis](PPD_OIS_Analysis)  
Presentation: [PPD_OIS_Analysis_Presentation](https://drive.google.com/file/d/1K9AWC3-a7GtFIzlzC7ZgoJVJwZWUkyxQ/view?usp=sharing)

