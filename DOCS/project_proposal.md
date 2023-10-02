**Project Title - Patterns and Implications of Missing Immigrants Data**

Prepared for UMBC Data Science master’s degree Capstone by Dr Chaojie (Jay) Wang

Author: Aditya Sirangi

GitHub: <https://github.com/AdityaSirangi>

# Background

The Project maintains a database that records incidents in which migrants have died during the process of migration to international destinations, regardless of their legal status.

The project collects data on migrant fatalities resulting from transportation accidents, shipwrecks, violent attacks, medical complications during journeys, and other causes.

It also includes cases where the deceased are found at border crossings, categorized as migrants based on belongings and characteristics.

The project's data are used to inform international indicators, such as the Sustainable Development Goals Indicator, which focuses on the number of people who died or disappeared during migration.

In addition to the database, the project publishes reports, briefings, and infographics, providing analysis of the data by geographic region, risks on irregular migration routes, identification of missing migrants, challenges faced by families of missing migrants, and data collection methodology.

The project provides information and resources to assist those searching for missing migrants.

# Why It Matters:

The Missing Migrants Project is a critical initiative because it sheds light on the tragic loss of life during migration and highlights one of the significant political failures of our time.

The project calls for immediate and safe routes for migration to prevent further migrant deaths and address the needs of families affected.

It emphasizes the importance of better data to inform policies that can help end migrant deaths and provide support to families.

The initiative is funded by various governments and organization.

The project aims to raise awareness of the challenges and risks faced by migrants during their journeys and advocate for safe migration for all.

# Data set:

The dataset contains information related to incidents involving migrants' deaths. This data is sourced from the International Organization for Migration's Missing Migrants Project (IOM MMP) and provides insights into incidents that occurred in various regions. Below is a summary of the dataset columns:

|**Column Name**|**Data Type**|**Description**|
| :-: | :-: | :-: |
|Main ID|object|An identifier for the incident|
|Incident ID|object|A unique identifier for each incident|
|Incident Type|object|Describes the type of incident|
|Region of Incident|object|Specifies the region where the incident occurred|
|Website Date|object|The date when the incident was reported on the website|
|Incident Year|int64|The year in which the incident took place|
|Reported Month|object|The month when the incident was reported|
|Number of Dead|float64|The count of deceased individuals in the incident|
|Minimum Estimated Number of Missing|float64|The minimum estimated count of missing individuals|
|Total Number of Dead and Missing|int64|The total count of both dead and missing individuals|
|Number of Survivors|float64|The count of survivors in the incident|
|Number of Females|float64|The count of female individuals involved in the incident|
|Number of Males|float64|The count of male individuals involved in the incident|
|Number of Children|float64|The count of children involved in the incident|
|Region of Origin|object|Specifies the region of origin of the individuals involved|
|Cause of Death|object|Describes the cause of death for the individuals|
|Country of Origin|object|Specifies the country of origin of the individuals|
|Migration Route|object|Describes the migration route associated with the incident|
|Location of Death|object|Specifies the location where the incident resulted in death|
|Information Source|object|The source of information for the incident|
|Coordinates|object|Geographic coordinates of the incident location|
|UNSD Geographical Grouping|object|The geographical grouping as per the United Nations|
|Article Title|object|The title of an article related to the incident|
|Source Quality|float64|A measure of the quality of the information source|
|URL|object|The URL associated with the incident|




# Predictions and future Work:
- regression model for Predicting Total Number of Dead and Missing Immigrants
The target Variable is a Dependent Variable : Total Number of Dead and Missing

- features 
Incident Type
Incident year
Number of Dead
Number of Survivors
Number of Females
Number of Males
Number of Children
Cause of Death
Country of Origin
Migration route
- model to predict whether a missing immigrant is more likely to be found alive or not based on available features.
- identify patterns in missing immigrant incidents.
- recommendations for policies and interventions to reduce the number of missing immigrants.
