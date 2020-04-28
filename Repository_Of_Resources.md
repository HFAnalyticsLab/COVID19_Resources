# Repository of resources to support COVID-19 response analytics
This is a repository collecting together links to practical resources for analysts working to support health and care during the COVID-19 pandemic. Inclusion within this repository does not indicate that the Health Foundation endorses the resource, or offers any opinion on its validity or accuracy.

## Contents
* [Modelling projections](https://github.com/HFAnalyticsLab/COVID19_Resources/blob/master/Repository_Of_Resources.md#modelling-projections)
* [Identifying vulnerable groups](https://github.com/HFAnalyticsLab/COVID19_Resources/blob/master/Repository_Of_Resources.md#identifying-vulnerable-groups)
* [Processing data](https://github.com/HFAnalyticsLab/COVID19_Resources/blob/master/Repository_Of_Resources.md#processing-data)
* [Dashboards](https://github.com/HFAnalyticsLab/COVID19_Resources/blob/master/Repository_Of_Resources.md#dashboards)

## Modelling projections

### [Bed projections: covid19-reqd-beds-projection](https://github.com/nhs-bnssg-analytics/covid19-reqd-beds-projection) 
#### What the resource does
"Simple script to generate a projection of beds required to support given trajectory of covid19 cases requiring hospitalisation."
Takes inputs on expected hospitalisations and length of stay, to output capacity requirement projections.
#### Who developed the resource
[NHS BNSSG Analytics](https://github.com/nhs-bnssg-analytics/)

### [Capacity-dependent death projections: covid-simr](https://github.com/nhs-bnssg-analytics/covid-simr) 
#### What the resource does
"Simple script to generate a projection of deaths arising from insufficent acute/ICU capacity for a given trajectory of covid19 cases requiring hospitalisation, and to model the effect of various user-defined mitigating scenarios."
#### Who developed the resource
[NHS BNSSG Analytics](https://github.com/nhs-bnssg-analytics/)

### [33N COVID ICU capacity model](https://covid.33n.co.uk/login) 
#### What the resource does
A model looking at ICU resource (ventilation, PPE) and workforce planning. Excel and web tools available. 
Discussed in the FutureNHS modelling [huddle](https://future.nhs.uk/DataAnalyticsCovid19/view?objectID=19407216). Must register with 33N for access. 
#### Who developed the resource
[33N](https://www.33n.co.uk/)

### [LSHTM CCMID Hospital Bed Occupancy Projections](https://cmmid-lshtm.shinyapps.io/hospital_bed_occupancy_projections/)
#### What the resource does
Webapp to forecast bed occupancy for COVID-19 patients using recent data on admission and an exponential growth model.
You can choose to model critical or non-critical care beds.
#### Who developed the resource
[LSHTM CCMID](https://cmmid.github.io/)

## Identifying vulnerable groups
### [Shielded patient list - NHS Digital methodology](https://digital.nhs.uk/coronavirus/shielded-patient-list/methodology)
#### What the resource does
Documents describing the methodology that has been used to identify patients who meet the high risk criteria for contracting coronavirus (COVID-19), who should be shielded for at least 12 weeks.
#### Who developed the resource
NHS Digital

### [COVID-19 phenomics](https://covid19-phenomics.org/#section-algorithms)
#### What the resource does
"A comprehensive, open-access resource providing the research community with information, tools and phenotyping algorithms for defining COVID-19 related phenotypes in UK electronic health records data."
#### Who developed the resource
HDR UK COVID-19 Phenomics; Spiros Denaxas [@SpirosDenaxas](https://twitter.com/SpirosDenaxas)

### [Comorbidity package in R](https://cran.r-project.org/web/packages/comorbidity/vignettes/comorbidityscores.html)
#### What the resource does
"`Comorbidity` is an R package for computing comorbidity scores based on ICD codes data. As of version 0.1.0, comorbidity can calculate the Charlson comorbidity score and the Elixhauser comorbidity score, using either the ICD-9 or ICD-10 coding system." 
#### Who developed the resource
Alessandro Gasparini

### [Imperial frailty index](https://github.com/HFAnalyticsLab/Hospital_admissions_frailty/blob/master/doc/frailty_score.md)
#### What the resource does
Definition and associated code to identify frailty in Admitted Patient Care records in HES. This definition of frailty was used to support Imperial College London in estimating hospital capacity for admissions for COVID pneumonia. 
#### Who developed the resource
[Fiona Grimm](https://github.com/fiona-grimm) (Health Foundation), with collaborators at Imperial College London


## Processing data

### [COVID-19 UK Historical Data](https://github.com/tomwhite/covid-19-uk-data)
#### What the resource does
This github repository collates the historical UK government data on numbers of tests, confirmed cases, and deaths for COVID-19, and provides it in an easily consumable format (CSV), in both wide and tidy data forms. Includes daily counts of confirmed cases for (upper tier) local authorities in England, health boards in Scotland and Wales, and local government district for Northern Ireland.
#### Who developed the resource
[Tom White](https://github.com/tomwhite)

### [Weekly provisional coronavirus (COVID-19) figures 2020](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/adhocs/11589weeklyprovisionalcoronaviruscovid19figuresbylocalresilienceforumenglandandwales2020) 
#### What the resource does
Numbers of weekly deaths (provisional) by age groups, region and usual residence (counties)
#### Who developed the resource
Office of National Statistics

### [Weekly provisional Deaths](https://github.com/Lextuga007/NHSRdatasets/blob/ONSMortality/Working%20files/ONSMortality.csv) 
#### What the resource does
Weekly provisionally registered deaths for England and Wales from [ONS](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/datasets/weeklyprovisionalfiguresondeathsregisteredinenglandandwales) has been reordered for analysis and inclusion to the [NHSRdatasets R package (available on CRAN)](https://github.com/nhs-r-community/NHSRdatasets). Available as an [.RData file](https://github.com/nhs-r-community/NHSRdatasets/blob/master/data/ONSMortality.RData).
#### Who developed the resource
[Zoë Turner](https://github.com/Lextuga007)

## Dashboards

### [NHS COVID-19 Situation Operational dashboard](https://improvement.nhs.uk/account/)
#### What the resource does
Dashboard based on COVID-19 Daily Sitrep data collection, from acute, mental health and community providers. Must request access, permissions granted by NHSI. 
#### Who developed the resource
[NHS](https://future.nhs.uk/DataAnalyticsCovid19/view?objectId=18941424)

### [Daily confirmed coronavirus cases and deaths in the UK published by Public Health England](https://trafforddatalab.shinyapps.io/covid-19/#section-deaths) 
#### What the resource does
Shiny Dashboard showing graphical numbers (linear and logarithmic) of confirmed UK cases, deaths and an international comparison as released from Public Health England and published through European Centre for Disease Prevention and Control.
#### Who developed the resource
[Trafford Data Lab](https://github.com/traffordDataLab)

### [Weekly Deaths: England and Wales](https://ukpublichealthdata.shinyapps.io/weekly_deaths/) 
#### What the resource does
Weekly deaths from [ONS](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/datasets/weeklyprovisionalfiguresondeathsregisteredinenglandandwales) plotted with forecasting from the Prophet R package.
#### Who developed the resource
Ian Bowns

## Mapping Tools
### [SHAPE Strategic Health Asset Planning and Evaluation](https://shapeatlas.net/) 
#### What the resource does
Mapping tool for Strategic Health Asset Planning and Evaluation now includes COVID-19 site status on the map, including Hot and Cold status for GP practices. Registration is required by formal registration and licence agreement. It is free for NHS professionals and Local Authority professionals with a role in Public Health or Social Care. 
#### Who developed the resource
Public Health England