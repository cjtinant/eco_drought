Ecological drought prediction and mitigation
========================================================
author: C. Jason Tinant
date: April 25, 2018
autosize: true


Introduction
========================================================

- Aquatic communities rely on streamflow
- Streamflow varies in time (e.g. floods, droughts) 
- Streamflow varies in space (climate, geology, 
flow abstractions)

**Challenge:** "We understand how freshwater 
communities persist during normal and high flows 
better than we understand the ecological effects of 
droughts" - P.S. Lake


Biotic integrity has a signal to noise problem
========================================================
- We lack numeric approaches for ecosystem response 
to drought. 
- Biotic integrity metrics **should** detect land use 
changes resulting in decreased habitat quality. 
- Drought timing, magnitude, and duration also affects
community composition, and in different ways:
+ *Predictible* seasonal drought -> **community resistance & 
resilience** 
+ *Unpredictable* supra-seasonal drought -> **regime shift**


Hypothesis & Project Design
========================================================
 
**Drought is a key driver of macroinvertebrate 
community regime shift for Northern Great Plains 
streams.** 

To test hypothesis, I plan to:

1. Quantify drought process at watershed scale
2. Test effect of drought on invertebrate community
3. Compare results to other dryland studies  




General Description of Study Area
========================================================
- Northern Great Plains - Pine Ridge Reservation
- BSk climate: semi-arid cold mid-latitude steppe 
- Elevation: 2,250 to 3,700 ft (690 - 1,130 m)
- Precipitation: 15.8 to 17.2 inches (400 - 450 mm)
- Mixed-grass prairie with pine savanna on 
N. slopes; cottonwood woodlands to ash-elm forest 
- Cattle ranching with minor grass & row crops (N-SE)




Study Area Ecoregions
========================================================

- Nebraska Sand Hills: Stabilized sand dunes ($Q_{SH}$)
SW-groundwater interface - constant base flow
- Keya Paha Tablelands: Soft sandstone plains ($T_A$)
Riparian Ash-Elm forest overstory
- Pine Ridge Escarpment: Sandstone ridges ($T_A$)
Ponderosa Pine & Ash-Elm forest overstory
- White River Badlands: Escarpments ($T_{WR}$)
Cottonwood-willow woodlands over turbid ephemeral streams 




Study Area Streams
========================================================
- Low gradient dune-ripple morphology streams 
with well-developed floodplains.   
- Nebraska Sand Hills - Little White River:
Eastward flowing, baseflow dominated E5 stream type 
- Keya Paha Tablelands & Keya Paha Tablelands: North flowing 
mixed-flow, low turbidity C6 or E6 stream-types 
- White River Badlands: North flowing event-dominated, high turbidity 
from constant stream channel adjustment between C6 – G6 – F6 – E6 morphologies. 


How to define drought?
========================================================

- Drought is a persistent deficit in precipitation or 
water supply measured across space and time

Two general drought classes:

- **Operational drought**: Moisture deficit in one or more 
hydrologic cycle components. *Robust indices available*

- **Conceptual drought**: water supply deficits for 
society or ecosystems. *Objective measurements lacking*


Drought-type Hierarchy
========================================================
- **Meteorological drought**: Deficit between actual &
expected precipitation.  Leads to other drought types

-  **Agricultural drought**: Inadequate soil moisture 
to meet evapotranspiration & vegetation demands

- **Hydrological drought**:  Surface & ground water 
deficit lagging precipitation deficit & recovery 

- **Ecological drought** water shortage causing 
ecosystem stress & adversity to plants and animals by
flow reduction, higher water temps & salinity 




Drought Index Recomendations
========================================================

WMO recommends a drought index approach:

- **Standardized Precipitation Index (SPI)** for   
meteorological drought
 
-  **Standardized Precipitation Evapotranspiration Index (SPEI)**
for soil moisture drought

- **Streamflow drought index (SDI)** discussed for 
hydrological drought  

- **No WMO recommendations** for ecological drought.


Drought Index Theory
========================================================

- Precipitation or streamflow deficit or excess 
represents a Markov process

- SPI-SPEI-SDI "unskew" precipitation time-series into 
normalized wet or dry monthly or longer duration
 
- Underlying distribution estimated by L-moments.

- Pearson III, log-Logistic & log-Pearson III provide
good fits, respectively.
**Not clear which is which...**

Approach & Methods
========================================================
**Drought is a key driver of macroinvertebrate 
community regime shift for Northern Great Plains 
streams.** 

**Q1:** What are the relationships between drought types?
- Precipitation, soil moisture, stream flow droughts

**Q2:** What are abiotic drivers of regime shift?
- $\Delta$ water quality vs. $\Delta$ water quantity

**Q3:** Which taxa groups are resilient to $\Delta$ water quantity 
& indicate $\Delta$ water quality (e.g land use change)


Q1: Relationships between drought types 
========================================================

| TASK | DATASET(S) | METHOD | OUTCOME |
|------|:-----|:---------:|:------:|
| 1. Calculate SPI, SPEI & SDI indices | $\bar{x}$ monthly precip., temp. & discharge | 'SPEI' package & new code | Indices at 3, 6, 9 & 12-month scales |
| 2. Pair met. stations & gages |	Geographic coordinates |	Thiessen poly. --- 'deldir' |	Paired datasets |
| 3. Characterize hydrology | Indices at 3, 6, 9 & 12-month scales |	Coefficient of determination | Watershed characteristics |
| 4. Cluster similar watersheds | Mean daily streamflow | ‘clValid’ & 'vegan' | Gaged watshed groups |
|	5. Cluster ungaged watersheds |	gSSURGO data for SD & Neb. | ArcGIS & ‘randomForest’ | Ungaged watshed groups |


Q2: What are abiotic drivers of regime shift?
========================================================

| TASK | DATASET(S) | METHOD | OUTCOME |
|------:|:-----|---------|:------:|
| 1. Visualize compositional species patterns | Taxa – site & environmental – site matrices --- SDI indices & WQ parameters	| Non-metric dimensional scaling (NMS) ordination by CRAN ‘vegan’ package |	Estimate environmental gradients |
| 2. Compare community differences for non-drought vs. drought years | Taxa – site matrix, environmental – site matrix |	PERMANOVA	| Test drought hypothesis |


Q3: How do results compare with other dryland studies?   
========================================================

| TASK | DATASET(S) | METHOD | OUTCOME |
|------:|:-----|---------|:------:|
| 1. Visualize compositional species patterns 
| Taxa – site & environmental – site matrices --- SDI indices & WQ parameters	
| Non-metric dimensional scaling (NMS) ordination by CRAN ‘vegan’ package 
|	Estimate environmental gradients |

| 2. Compare community differences for non-drought vs. drought years | Taxa – site matrix, environmental – site matrix |	PERMANOVA	| Test drought hypothesis |






Expected Results
========================================================

* **Drought drives community change** --- based on several rejected hypotheses;
* More interesting is *variance along gradients*: drought magnitude, water quality & watershed physiology

* **Seasonal drought** --- resilience & recovery within one-year
* **Supra-seasonal drought** --- regime shift to smaller-bodied & r-selected taxa; more gastropods

* **Baseflow buffers against change**: resistance & resilience directly correlated with baseflow


Work Plan/Timetable 1/x
========================================================


| DATE | OBJECTIVE(S) |	TASK(S)	| MILESTONE(S) | OTHER |
|------:|:-----|---------|:------:|:-----:|
| 2018--04 | PhD Candidacy |	Committee Approval |	Written & oral proposal feedback | |
| 2018--05 | Outline Dissertation | Create GitHub repository in Thesisdown format | Knit three dissertation chapters | Complete water policy paper & NSF dissemination |
| 2018--06 | Complete Objective 1	| calculate drought indices, characterize watershed hydrology, cluster watersheds | Characterize droughts, gaged watersheds, ungaged watersheds | Journal identification |


Work Plan/Timetable 1/x
========================================================
| DATE | OBJECTIVE(S) |	TASK(S)	| MILESTONE(S) | OTHER |
|------:|:-----|---------|:------:|:-----:|
| 2018--08 | Complete Objective 2 | NMS Ordination | Data munging, Visualize taxa patterns |	OST	Dissemination |
| 2018--09 | Prepare for completion | Revisit timeline | Identify Journals | SDSMT Seminar Dissemination |
| 2018--10 | Complete Objective 3 | Update IBI & WPP | PERMANOVA | |
| 2018--11 | Prepare for PhD defense  | Finalize draft dissertation | Validate formatting | schedule date |
| 2018--12 | PhD defense  |  |  |  |









Overview of Study Area
========================================================



![plot of chunk library](Ecol_Drought_Prediction_Proposal-figure/library-1.png)



Overview of Study Area
========================================================



```
Error in download.file(url, destfile = tmp, quiet = !messaging, mode = "wb") : 
  cannot open URL 'http://maps.googleapis.com/maps/api/staticmap?center=34.753117,-119.751324&zoom=15&size=640x640&scale=2&maptype=terrain&language=en-EN&sensor=false'
```
