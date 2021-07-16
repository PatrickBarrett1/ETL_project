Context:
Wanted to explore potential correlation bewteen Chicago crime and Chicago unemployement rates.

Content:

Data Source: 
Crime data: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2
Unemployment data: https://www2.illinois.gov/ides/lmi/Pages/Illinois_Chicago_Metropolitan_Area_Unemployment_Rates.aspx

Both data sets are CSVs.

Removed null values.

Used the date range of 2001-2020.

Did groupby Year and 'Primary Type' of crime to get count of crimes committed each year.

Removed 2021 Unemployement data.

Load data in to dataframes.

Created ETL-project database using postgres for connection.
