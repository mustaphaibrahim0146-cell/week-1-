# Data Note 

**Week 3 Deliverable.** GeoDev Lab Africa, Cohort one.

Author: Mustapha Ibrahim

## OSM Roads, OFFA LGA

-**Extraction Date**: 20 sept 2026 

-**Retriever**: via QuickOSM 

-**Geometry Type**: line

-**Features count**: 1950

### COMPLETNESS 

- Newly constructed health facilities were identified in Essa C Ward and Ojomu Central Ward that were not included in the original dataset. These facilities were flagged as missing data and should be added or verified before the final accessibility analysis. 

- Newly constructed road at some area in Ojomu north wards

### CURRENCY 

- Most of the available spatial data were updated between 2020 and 2024. Recent developments, including the new market in Ojomu South-East and the newly constructed road in Shawo South-East, may not be fully represented in the datasets.

### POSITIONAL ACCURACY 

- The mapped road features align well with the available satellite imagery, with no systematic positional offset or noticeable displacement observed. 

### ATTRIBUTE ACCURACY 

- Attribute data such as facility names, ward names and feature classifications were checked and found to be generally accurate and consistent, with only minor updates required for newly added facilities.

### FITNESS FOR PURPOSE

- The datasets are generally suitable for the healthcare accessibility analysis in Offa LGA. However, missing newly constructed health facilities and recent roads may affect the accuracy of the 5 km accessibility assessment, so these features should be updated or flagged before the final analysis.


## CRS and preparation

- All source layers arrived in EPSG: 4326
- study area: wards in Offa LGA, of Kwara state.
- All layers clipped to study area, then reprojected to EPSG: 32632 (UTM 32N)
- Area check: KWARA, OFFA 73.463km² according to the publish file its 95.45km²
- working files in data/processing / raw files

