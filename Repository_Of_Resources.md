# Repository of resources to support COVID-19 response analytics
This is a repository collecting together links to practical resources for analysts working to support health and care during the COVID-19 pandemic. Inclusion within this repository does not indicate that the Health Foundation endorses the resource, or offers any opinion on its validity or accuracy.

## Contents
* [Modelling projections](https://github.com/HFAnalyticsLab/COVID19_Resources/blob/master/Repository_Of_Resources.md#modelling-projections)
* [Identifying vulnerable groups](https://github.com/HFAnalyticsLab/COVID19_Resources/blob/master/Repository_Of_Resources.md#identifying-vulnerable-groups)

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

