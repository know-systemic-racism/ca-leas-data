# California Law Enforcement Agencies
This is a list of California law enforcement agencies that we have gathered and curated for the purpose of finding and tracking policy manuals and military equipment inventories. Each row represents a law enforcement agency.

The reason for compiling this list is to have a base set of URLs and related information for California LEAs that will be incorporated into the Know Systemic Racism Knowledge Graph. Stanford Libraries' KNOW Systemic Racism project began work in collaboration with the Electronic Frontier Foundation (EFF) to gather this list and details about California law enforcement agencies between 2018-2022. We continued to refine the list and add details into August 2023.

## Methodology
This dataset includes a list of POST (Peace Officer Standards and Training) participating law enforcement agencies (LEAs) in California. This list is based on the [California's Commision on Police Officer Standards and Training](https://post.ca.gov/le-agencies). Some LEAs on that list do not appear on this list because our primary interest is in identifying the policy manuals. For example, some LEAs, particularly community college police departments, are part of a shared resource and use the same policy. We added the website URL for each agency as well as an archived version of that URL at the point in time when we gathered it. We are very grateful to Archive.org for webarchving this and other material on the Web and encourage others to support their work. 

These LEAs now all have entries within Wikidata and we have added the Wikidata QID to this list to make this dataset more durable and to make it open to continual development by the community.



## california-leas-2023-08-16.csv headings
- **ksrid lea**: This is the index number used to disambiguate the LEAs within the Know Systemic Racism Project. The SB978 prefix is a legacy prefix that associates this project with the California law requiring that these policies be posted publicly. The following number is purely an index and is not ordered. 
- **agency name**: Name of each California law enforcement agency as listed on their posted policy manual. Exceptions include when a shortened name is listed on a manual, but a consistent posted reference is referred elsewhere.
- **site url**: The official website of the law enforcement agency at the time that these were gathered. These URLs can change over time, particularly if an agency migrates to another web site platform.
- **webarchive url**: To maintain a consistent link to the site at the time of reference, we use the webarchive link made available by Archive.org's Wayback Machine. 
- **lea qid**: This is the unique identifier from Wikidata. Entity pages can be found by adding the prefix "https://www.wikidata.org/wiki/" followed by the QID.
- **reference**: Reference refers to a parent police department that the list LEA is part of.
- **city**: The city refers, in most cases, to the LEA headquarters city. There are exceptions for railroads, schools, etc.
- **city qid**: The wikidata identifier for the US city where the LEA is headquartered.
- **latlon**: Latitude and longitude for either the specific headquarter location or, when that is not available, the city.
- **street address**: Where available, we have included the full street address of of the LEA headquarters
- **county**: Like city, this refers in most cases to the LEA headquarters county.
- **county qid**: The wikidata identifier for the US county where the LEA is headquartered.
- **zip code**: The 5-digit zip code
- **lea type**: The type is based on the CA.Gov Post listing type. Possible values are: College/University, Police, School, Transit, Probation, Sheriff, District Attorney, Port, Airport, Parks, Public Safety, School District, Communications.


## Long LEA list 2022-11-21.csv Headings
- **Ref**: This is the index number used to disambiguate the LEAs within the Know Systemic Racism Project. The SB978 prefix is a legacy prefix that associates this project with the California law requiring that these be posted publicly. The following number is purely an index and is not ordered. 
- **LEA Name**: Name of each California law enforcement agency as listed on their posted policy manual. Exceptions include when a shortened name is listed on a manual, but a consistent posted reference is referred elsewhere.
- **Reference**: Reference refers to a parent police department that the list LEA is part of, as noted in California LEA csv
- **Contract**: Contract refers to a designation of whether an LEA enters a formal, legally binding agreement to provide law enforcement services to another LEA for a fee, as noted in California LEA csv
- **Post Participating**: POST agencies refer to the Peace Officer Standards and Training (POST) which was established by the Legislature in 1959 to set minimum selection and training standards for California law enforcement. Post participating refers to the agencies that comply with the rules and regulations of this standard, as stated by the POST site.
- **City**: The city refers, in most cases, to the LEA headquarters city. There are exceptions for railroads, schools, etc.
- **County**: Like city, this refers in most cases to the LEA headquarters county.
- **LEA Type**: The type is based on the CA.Gov Post listing type. Possible values are: College/University, Police, School, Transit, Probation, Sheriff, District Attorney, Port, Airport, Parks, Public Safety, School District, Siskiyou County, Communications
- **Policy Manual Exists**: TRUE or FALSE refers to whether the policy manuals are identified and available for download. The result was initially based on a script then Q/Aed manually.
- **Mil Equip Policy Exists**: TRUE or FALSE refers to whether the manuals are identified and available for download. The result was initially based on a script then Q/Aed manually.
- **Notes**: Additional information found through online searches to contextualize present or missing information

## LEA_KSR.json
This is the schema to be used with OpenRefine to populate Wikidata entries based on the california-leas-2023-0816.csv above.
