# Lex-Python-StudentProject-Housing

## The Effects of Multi-Unit Housing on Neighborhoods in the U.S.
The two datasets for this project detail a wide variety of characteristics for the roughly 940 Metropolitan and Micropolitan Statistical Areas in the U.S., each of the 50 States, the District of Columbia, and Puerto Rico, for all years 2010-2021. For roughly 60 years, the U.S. has largely followed an urban planning model that enormously prioritizes single-family housing and urban sprawl, and that I suspect is bankrupting, isolating, and segregating the communities it is implemented in. The data has been compiled from seven other data sets to interrogate the effects that multi-unit housing has in the areas where it is built in and where it already exists.

### Collection Methods
As I am an independent student, all the data here is external. It is all from authoritative sources, some public and some private. Most of it is official government survey data collected and/or calculated annually, with the exception of the Zillow data which is calculated quarterly from their own database. I have chosen these datasets because they contain the most thorough information on housing units and value, population change and density, other characteristics of U.S. neighborhoods and households, and government finances. 
### Citations:
##### United States Environmental Protection Agency (EPA). (2022). Smart Location Database. Retrieved from: https://edg.epa.gov/EPADataCommons/public/OA/EPA_SmartLocationDatabase_V3_Jan_2021_Final.csv (More info: https://www.epa.gov/smartgrowth/smart-location-mapping#SLD)
##### United States Census Bureau. (2010-2021). Annual Building Permits by State by Structure. Retrieved from https://www.census.gov/construction/bps/
##### United States Census Bureau. (2010-2020). American Community Survey Data. Retrieved from https://data.census.gov/cedsci/table?q=dp04&g=0100000US%243100000&tid=ACSDP5Y2020.DP04
##### United States Census Bureau. (2010-2021). Population Totals and Components of Change. Retrieved from https://www.census.gov/programs-surveys/metro-micro/data/tables.All.List_2143640002.html, https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html#par_textimage
##### United States Census Bureau. (2010-2021). Public Sector Annual Surveys. Retrieved from https://data.census.gov/cedsci/table?t=State%20and%20Local%20Government%20Finances&g=0100000US%240400000&tid=GOVSTIMESERIES.GS00SG01
##### Federal Housing Finance Agency. (2010-2021). Housing Price Index (HPI) by Metro Area and State. Retrieved from https://www.fhfa.gov/DataTools/Downloads/Pages/House-Price-Index.aspx
##### Zillow Housing Data. (2010-2021). Zillow Home Value Index (ZHVI) by Metro Area and State. Retrieved from https://www.zillow.com/research/data/
##### United States Census Bureau. (2021). Cartographic Boundary Files. https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html

## Contents
##### EPA Smart Location Database
I have chosen to derive 15 variables from this recently compiled data from the Environmental Protection Agency. Notable are employment figures, total acreage per area, housing units and occupied households, households that own cars and how many, population density, employment density, and perhaps most importantly a weighted average for both the national walkability index and access to a transit stop.
Because this data is not a time series, I include it in a separate table.
##### Housing Starts (Building Permits)
Includes the number of housing permits issued per state by the type of housing approved. This data implies what kind of new housing is getting built.
##### Housing Units by Type and Value
Data collected from the American Community Survey lists estimates for the number of housing units by type as well as for the number of homes by their value. Also included are estimates for what rent costs and gross rent as a percentage of household income (GRAPI). 
##### Population and Components of Change
This data details population estimates per area by year as well as its change and causes of change, including natural change (births and deaths) and migrational change (domestic and international migration). 
##### State Government Finances
Estimates of each state’s total revenue, total tax revenue, and total expenditure.
##### FHFA Housing Price Index (HPI)
The Federal Housing Finance Agency compiles an index each year detailing the percentage change among all single-family homes in an area.
##### Zillow Housing Value Index (ZHVI) for Single-Family Homes
Similarly, Zillow gives its best value estimates for single-family homes in an area. From this data I included the raw value estimates and derived a similar index to the HPI of percentage change.
##### State and CBSA Shapefiles
Shapefiles for the 50 U.S. states and ~930 metropolitan and micropolitan areas, later converted to json files through a free online site for use in creating geographic visualizations.
