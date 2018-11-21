# Australian and New Zealand Soil Mark-up Language (ANZSoilML)

> ANZSoilML documentation can be found on the project wiki: [https://github.com/ANZSoilData/ANZSoilML/wiki](https://github.com/ANZSoilData/ANZSoilML/wiki)  
> The ANZSoilML github.io home page is here: [https://anzsoildata.github.io/ANZSoilML/](https://anzsoildata.github.io/ANZSoilML/)

## Summary
ANZSoilML is a GML application schema that specifies a set of feature-types and supporting structures for information used in the Australian and New Zealand soil sciences. It is primarily concerned with observed properties of Soils and associated Landscapes as specified in the:
- _Australian Soil and Land Survey Field Handbook, Third edition, 2009, The National Committee on Soil and Terrain._
- New Zealand _Soil Description Handbook, Revised edition, 1995, Milne, J.D.G., Clayden, B., Singleton, P.L., Wilson, A.D._

ANZSoilML was derived from OzSoilML, which was developed under the auspices of the Australian Collaborative Land Evaluation Program (ACLEP) http://www.clw.csiro.au/aclep/.

Copyright (c) CSIRO 2018. All rights reserved.

## Contributors

| Agency | Contact |
| ------ | ------- |
| CSIRO, Australia | [Peter Wilson](https://people.csiro.au/w/p/peter-wilson) |
| Federation University of Australia | [Bruce Simons](http://www.cerdi.edu.au/cb_pages/staff.php#bruce_simons) |
| Manaaki Whenua (Landcare Research), New Zealand | [Alistair Ritchie](https://www.landcareresearch.co.nz/about/people/staff-details?id=cml0Y2hpZWE=) |


## Implementations
List of ANZSoilML implementations

Federation University Australia (CeRDI)
http://services.cerdi.edu.au/anzsoilml/wfs?request=getCapabilities 

FeatureType request endpoints
Soil Specimen
http://services.cerdi.edu.au/anzsoilml/wfs?request=getFeature&typeName=anzsmlss:SoilSpecimen&count=10&maxFeatures=10
Observations
http://services.cerdi.edu.au/anzsoilml/wfs?request=getFeature&typeName=om:OM_Observation&count=10&maxFeatures=10

Basic WFS request Router (friendly URLs for Feature ID requests) 
http://id.cerdi.edu.au/anzsoilml/feature/specimen/1
http://id.cerdi.edu.au/anzsoilml/feature/observation/1
Note: These default to WFS version 2.0.0 and outputFormat GML3.2  (requests to WFS 1.x.x result in malformed outputs)
