## *This poject is In Progress*

## Project Scope

Since before COVID-19's discovery, there has been public debate related to the existence and actions to take against climate change (particularly air pollution). Air pollution was heavily politized through the 2015 passage (and 2017 repeal) of the [Clean Power Plan](https://archive.epa.gov/epa/cleanpowerplan/fact-sheet-overview-clean-power-plan.html) aimed at reducing carbon pollution from power plants and the 2019 introduction of the [Green New Deal](https://www.congress.gov/116/bills/hres109/BILLS-116hres109ih.pdf) package.

As the country faces a devastating disease which spreads through air particles and the government considers climate change legislation, it is crucial to consider: **Does air quality affect Covid-19 mortality?**

As the timeline and implementation of disease mitigation efforts differs widely between states, a look at one state where all counties have the same legislation (for the most part) is more meaningful. This project will look at **New York State** whose regions display a wide range of conditions that may affect air quality such as population density, racial makeup, income level, etc.

## Objective: 

Answer: **Does air quality affect COVID-19 mortality in New York State?**

To answer this question, this project will compare the following data per county:
* COVID-19 Deaths
* Air Quality
* Demographics

## Data Sources

**COVID-19 Deaths**

Total
* Source: The U.S. Centers for Disease Control and Prevention (CDC)
* Link: [Coronavirus Cases & Deaths](https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-in-the-United-St/kn79-hsxy)

Daily Count
* Source: USAFacts.org
* Link: [New York Coronavirus Cases & Deaths](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/state/new-york)

**Air Quality**
* Source: U.S. Environmental Protection Agency (EPA)
* Links: 
    * [Outdoor Air Quality Data](https://www.epa.gov/outdoor-air-quality-data/download-daily-data) 
        * *Data Dictionary [here](https://www.epa.gov/outdoor-air-quality-data/about-air-data-reports)*
    * [Air Quality Index Breakpoints](https://aqs.epa.gov/aqsweb/documents/codetables/aqi_breakpoints.html) (as of January 11, 2021)

**Demographics**
* Source: U.S. Census Bureau
* Links
    * [County Population by Characteristics: 2010-2019](https://www.census.gov/data/tables/time-series/demo/popest/2010s-counties-detail.html) 
        1) Age Group and Sex 
        2) Age, Sex, Race, Hispanic Origin


* Source: U.S. Department of Agriculture (USDA)
* Links:
    * [County-Level Data: Poverty](https://www.ers.usda.gov/data-products/county-level-data-sets/)
    * [County-Level Data: Unemployment and Household Income](https://www.ers.usda.gov/data-products/county-level-data-sets/)
    * [Hospitals](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals/data)
    
* Source: New York State Department of Health
    * Link: [Population, Land Area, and Population Density by County, New York State - 2006](https://www.health.ny.gov/statistics/vital_statistics/2006/table02.htm) (Manually extracted square miles data)
    
**Covid Deaths Demographics**

* Source: The U.S. Centers for Disease Control and Prevention (CDC)
    * Link: [Provisional COVID-19 Death Counts by County and Race](https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-County-and-Ra/k8wy-p9cg)

## Conclusion

*In Progress*

## Technologies Used

* Python Pandas
* Python MatPlotLib
* Python Seaborn