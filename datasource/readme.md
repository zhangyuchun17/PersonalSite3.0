# LGBT+ rights index - Data package

This data package contains the data that powers the chart ["LGBT+ rights index"](https://ourworldindata.org/grapher/lgbt-rights-index?v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website. It was downloaded on February 19, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## LGBT+ rights index
The LGBT+ Policy Index measures a country’s LGBT+ policy landscape by capturing the implementation of 18 different LGBT+ policies. Policies included in the index are limited to those adopted across at least three countries or are explicitly advocated for by transnational activists.
Last updated: April 27, 2023  
Date range: 1991–2019  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Velasco (2020); Population based on various sources (2023) – with major processing by Our World in Data

#### Full citation
Velasco (2020); Population based on various sources (2023) – with major processing by Our World in Data. “LGBT+ rights index” [dataset]. Velasco, “LGBT+ policies (Kristopher Velasco)”; Various sources, “Population” [original data].
Source: Velasco (2020), Population based on various sources (2023) – with major processing by Our World In Data

### What you should know about this data
* These policies that define the index are subdivided between progressive policies and regressive policies. Among the progressive policies are: Same-sex sexual acts Legal, Equal Age of Consent, Employment Discrimination, Hate Crime Protections, Incitement to Hatred, Civil Unions, Marriage Equality, *oint Adoptions, Gender Marker Change, LGB Military, Transgender Military, Ban on Conversion Therapies, and Ban on Gender Assignment Surgeries on Children.
* On the other hand, the regressive policies are: Death Penalty for Same-Sex Sexual Acts, Propaganda Laws, Same-Sex Sexual Acts Illegal, Unequal Age of Consent, and Ban on Marriage Equality.
* This policy is not measured in a binary (adopted/not-adopted) scheme; the author follows Frank and colleagues ([2010](https://www.jstor.org/stable/25782170), [2017](https://www.jstor.org/stable/26166859)) in considering that similar policies can meaningfully vary in scope, benefits, punishment, etc. So, he determines the robustness of each policy by reviewing five indicators.
* These indicators are (between parentheses are the scoring schemes): *Proportion of Population Living Under Law*, to acknowledge subnational variations (0-1), *Scope of Genders Subject to Law*, as they can be typically differentiated by gender (0: no law, 0.5: just men or women, 1: both), *Maximum Level of Punishment*, for regressive policies (0: no law, 0.2: less than 3 years, 0.4: over 3 years and less than 15 years, 0.6: over 15 years and less than life in prison, 0.8: life in prison, 1: death penality), *Ease of Access*, to benefits the law outlines (0: no law, 0.25: significant barriers, 0.5: moderate barriers, 0.75: little to few barriers, 1: no barriers, and *Evidence of Enforcement* that considers whether at least one case has happenedthe previous year where this was implemented (0: no evidence, 1: evidence).
* To create the index, the scores for each policy are summed together annually, with progressive policies receiving a positive score and regressive policies receiving a negative score. This results in an index ranging from -5 to +13. No country reaches these extremes, demonstrating that countries can get better and worse in their policy environments.

### Sources

#### Velasco – LGBT+ policies (Kristopher Velasco)
Retrieved on: 2023-06-15  
Retrieved from: https://osf.io/preprints/socarxiv/3rtje/  

#### Various sources – Population
Retrieved on: 2023-03-31  
Retrieved from: https://ourworldindata.org/population-sources  

#### Notes on our processing step for this indicator
We estimated regional aggregations by using [Our World in Data definitions of regions](https://ourworldindata.org/world-region-map-definitions) and our [consolidated population data](https://ourworldindata.org/population-sources).


    