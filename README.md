# housing

Housing Affordability by Sean Mannisto

This notebook:

Creates the dataset for my Tableau visualization of housing affordability at: https://public.tableau.com/app/profile/sean.mannisto/viz/HousingPricetoIncomeRatios/Sheet1

Creates a color and size-coded scatterplot of all US counties and their relative housing affordability

Calculates a Multiple Linear Regression Model

Calculates and plots statistics

Original Datasets:

Zillow "Housing Value Index All Homes Time Series Smoothed Seasonally Adjusted" https://www.zillow.com/research/data/

USDA "Unemployment and median household income for the U.S., States, and counties, 2000-2021" https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/

US Census API American Community Survey 2021

B25103_001E is "Median Real Estate Taxes Paid (Dollars)"

B01003_001E is "Estimate, Total Population"

Notes:

Federal Information Processing Standards (FIPS) code used as county index.
Some very low population counties have insufficient real estate data, particularly in the western Great Plains
Known Issue: Tax values above 9999 are all recorded as 10001 in the ACS
