# Data

## Final Covariate Data Set
Final shapefile name "SDOH 2022 Old and New Indicators.zip"

| Column Name | Description|
| ------------- | ------------- |
| AFFGEOID |	AFFGEOID
|Name	|Tract Name
|E_TOTPOP	|Total Population
|GEOID|	GEOID
|EP_POV	|Living in poverty, %
|EP_UNEMP	|Unemployed, %
|EP_PCI	|Per capita income, $
|EP_AGE65|	Aged ≥ 65 y, %
|EP_AGE17	|Aged ≤ 17 y, %
|EP_DISABL|	Disability, %
|EP_SNGPNT	|Single parent, %
|EP_MINRTY	|Ethnic/racial minority %
|EP_LIMENG	|Limited English Proficiency, %
|EP_CROWD	|Crowded Housing, %
|EP_UNINSR	|Uninsured, %
|EP_RENTER	|Renters / Housing Units 
|EP_RENTBURD	|Percentage of renters paying over 30% of income towards housing estimate
|EP_NOVEH	|No vehicle, %
|EP_NOHSDP|	No high school diploma, %
|INTERNET	|Percent Internet Access
|FOREIGNBOR	|Percent Foreign Born
|FQHC	D|istance to nearest FQHC Centers
|OTHERENGL	|Percent other languages beside English spoken in household
|ESSENTIAL	|Essential Workers
|GROCERY	|Distance to nearest Grocery Stores
|LOANSTORE|	Distance to nearest Access to Loan Stores
|CIVICPART|	Civic Participation (Response Rates to Decennial Census)
|GREENSPACE	|Greenspace (NDVI)
|SURFACETEM |	Land Surface Temps - Average LSTC – MODIS with interpolated values for neighboring areas
|ELEVAT	|Elevation - meters above sea level
|WATER2	|Water Percent 
|FQHC_PA	|Population Adjusted Distance to nearest FQHC Centers
|GROCERY_PA |	Population Adjusted Distance to nearest Grocery Stores
|LOAN_PA	|Population Adjusted Distance to nearest Access to Loan Stores

## Social Variables

| Variable  | Status | Source  | Notes  | 
| ------------- | ------------- | ------------- | ------------- | 
| Internet Access | Uploaded | ACS  | B28002  2014-2018 PRESENCE AND TYPES OF INTERNET SUBSCRIPTIONS IN HOUSEHOLD |
| Foreign-born % | Uploaded | ACS  | B05002  PLACE OF BIRTH BY NATIVITY AND CITIZENSHIP STATUS |
| Access to Federal Qualified Health Centers   | Uploaded   | [Opioid Policy Scan](https://github.com/GeoDaCenter/opioid-policy-scan/blob/master/data_final/metadata/Access_FQHCs_MinDistance.md) | Euclidean Distance to FQHC center |
| Civic Participation| Uploaded | ACS  | Decennial Self-Reponse Rates 2020 |
| Other languages beside English spoken in household | Uploaded | ACS  | S1601 -Percent English speakers over 5 years old speaking other language than English at Home |

## Economic Variables

| Variable  | Status | Source  | Notes |
| ------------- | ------------- | ------------- | ----- |
| Essential Workers  | Uploaded | [Opioid Policy Scan](https://github.com/GeoDaCenter/opioid-policy-scan/blob/master/data_final/metadata/Job_Categories_byOccupation_2018.md)  | 
| Grocery Store  | Uploaded | Business Data - Reference USA | Euclidean Distance to nearest Grocery Store | 
|Money Lenders/Cash Exchange Stores| Uploaded  | Business Data - Reference USA | Euclidean Distance to Loan Store  |


## Environmental Variables

| Variable  | Status | Source  | Notes |
| ------------- | ------------- | ------------- | --------- |
| Greenspace | Uploaded | NDVI - Sentinel  | |
| Bike Lanes | In progress -  MK  | OSM  | MK check if RA has code |
| Landsurface Temperature | Uploaded | [Google Meteorology Data](https://developers.google.com/earth-engine/datasets/catalog/NASA_ORNL_DAYMET_V4)| 
| % Tract covered by water| Uploaded | NCLD |  Open water: areas of open water, generally with less than 25% cover of vegetation or soil.|
| Elevation (DEM) | Uploaded | ? | Ask MS what is the source |

## Indicators Not Included:

| Variable  |  Source  | Notes |
| ------------- | ------------- | --------- |
|~~No. of Jobs per census tract~~| LEHD -  https://lehd.ces.census.gov/data/| Not accessible at tract level |
|~~Multiple Job Holders~~| Longitudinal Employer-Househould Dynamics | Only state level available |
| ~~Park Access~~ |  OSM  | Computational Issues in accessing at the tract level |
| ~~Walkability~~ |  | May need to remove due to challenges in accessing data |

## ACS Variables (2015-2019)

1. Ethnic/racial minority %
2. Aged ≥ 65 y, %
3. Aged ≤ 18 y, %
4. Disability, %
5. No high school diploma, %
6. Limited English Proficiency, %
7. Single parent, %
8. Living in poverty, %
9. Per capita income, $
10. Unemployed, %
11. Uninsured, %
12. Renter, %
13. Rent Burden, %
14. Crowded Housing, %
15. No vehicle, %

## Potential Health Outcomes
| Variable  | Status | Source  | Notes |
| ------------- | ------------- | ------------- | --------- |
| COVID-19 | In-Progress | TBD | Looking for Regional Tract Level Data |
| Adjusted Premature Mortality Rates | In Progress - MK & IM | MK has Chicago, looking for additional regions |
|Other regional tract level data | all look | | |




