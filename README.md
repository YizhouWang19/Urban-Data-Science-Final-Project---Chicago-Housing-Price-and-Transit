Finding affordable housing with easy access to public transportation is a challenge in many cities. This study examines the correlation between median housing values and public transit accessibility in Chicago for 2018 and 2021. The aim is to provide insights into the relationship between transportation infrastructure, housing affordability, and urban development in Chicago.2 Problem Statement 

Studies show a positive correlation between housing prices and proximity to public transit, though this can lead to the displacement of low-income residents. Contradictory findings indicate areas with high public transit might have lower-income populations, suggesting varied impacts based on socio-economic factors. The Hedonic Price Model is used to quantify the effect of transit proximity on housing prices.

The research explores how public transit accessibility affects housing prices, demographics, and economic characteristics within Chicago. It addresses the gap in understanding the localized impact of transit stations on housing prices and demographics during the Covid and post-Covid era. The hypothesis is that housing prices are positively correlated with public transportation density and influence demographic patterns and housing vacancy rates.

Housing Data:

B25077_001E: Median value (dollars) of owner-occupied housing units.
B25085_001E: Price asked for vacant-for-sale-only and sold, not occupied housing units.
B25001_001E: Total housing units.
B25002_003E: Vacant housing units.
B25003_002E: Owner-occupied housing units.
B25003_003E: Renter-occupied housing units.
Demographic Data:

B06011_001E: Median income in the past 12 months (in 2019 inflation-adjusted dollars) by place of birth in the United States.
B05007_001E: Foreign-born population.
B02001_001E: Total population by race
B02001_002E: Total white population by race
4.1.2 Public Transit Data in Chicago
Stops and Routes in Chicago is available from the datahub of the Chicago Metropolitan Agency for Planning (CMAP)

https://datahub.cmap.illinois.gov/search?categories=%252Fcategories%252Ftransit

Ridership for different Routes is available from the Regional Transportation Authority (RTA) - Mapping and Statistics

https://rtams.org/ridership

Stops:

2023 CTA Bus Stops - February 7, 2023
2023 Pace Bus Stops - May 1, 2023
2023 Metra Rail Stations - 2023
Routes/Lines:

2023 Pace Bus Routes - 2023
2023 CTA Bus Routes - February 7, 2023
2023 CTA Rail Lines - February 7, 2023
2023 Metra Rail Lines - 2023
Ridership:

Metra Station Ridership (Boarding & Alighting Survey) 2002-2018
Metra Total Rail Ridership By Line 2015-2023
CTA Rail Ridership By Station 2015-2023
CTA Bus Ridership By Route 2015-2023
Pace Bus Ridership by Route 2015-2023 p by Route 2015-2023
4.2 Analysis methods
The unit of analysis is the 866 census tracts within the county. The accessibility to public transport is indicated by the density of public transportation stops.

For this study, Global and Local Moran's I is used to analyze the basic data pattern along with the simple visualizations. Local Global Moran's I is used to evaluate the spatial autocorrelation of housing prices. Global Moran's I is used to measure spatial autocorrelation, determining whether similar values of a variable are clustered together geographically, which helps in identifying patterns such as the clustering or dispersion of demographic groups, real estate values, or accessibility features across a given area.

OLS, spatial regime, spatial lag model, and Spatial Durbin Model are applied to figure out what indicators are related to house prices. For this topic, it is possible to explore the relationship between housing prices and public transportation stop, the corresponding ridership, the distance between each tract and the closest stop, the percentage of non-whites, the median per capita income, and the percentage of immigrants and build a best-fit regression model around housing prices. This analysis will help identify the most significant predictors of housing prices in the city of Chicago and understand the impact of public transportation accessibility on these prices, controlling for other factors.
