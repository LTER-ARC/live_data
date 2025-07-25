#### **Log of Changes**

* 2008  Added Hobo loggers to CT and F10 plots. Three replicate depth profiles (surface, 10, 20 cm).
* 2012-07-13 Campbell Scientific 21X logger with AM25T multiplexer (Longitude -149.609083 Latitude 68.622629) set up in MAT06 Block 1 CT (control) and F10 plots measuring soil temperatures using type T thermocouples. Three replicate depth profiles (surface, 10, 20 cm) were installed at the 5, 10, and 15 meter south side plot stakes about 1-2 meters inside the plots. A small pit was cut into the soil and the thermocouples were inserted into the side wall of the pit.
* 2018-06-11 CR1000 logger station with air/RH CS500 sensors in and out of the greenhouse. Using repurposed SC616 soil moisture and 107 temperature probes. Lots of extra cables.
* 2019-08-17 Changed from 21x logger to a CR10x-PB
* 2021-06-08 Ian Klupar changed the CR10x-PB logger since it stopped working during the winter.
* 2023-06-10 Savannah and Jim rewired the soil logger station, with cables extending to the GH CR1000 station. This station now only has the AMT25T multiplexer wired to the GH CR1000.  The program was rewritten to include the soil plot TC. Tables were renamed – Metadata = air temperature and RH; GHPlotsoil = inside and outside soil temperatures and moisture at 10 cm; Soil\_plots = soil temperature in the CT and F10.

#### **Current Data Tables**

**Greenhouse Met\_data**

| Variable | Description | Units |
| --- | --- | --- |
| TIMESTAMP | Time Stamp |  |
| RECORD | Record Number |  |
| Air_3M_Avg | Air temperature at 3 meters | Deg C |
| RH | Relative humidity at 3 meters | % |
| GH_Air_Avg | Air temperature inside greenhouse | Deg C |
| GH_RH | Relative humidity inside greenhouse | % |
| BattV_Min | Battery voltage minimum for measurement period | Volts |

**Greenhouse Plot Soil**

| Variable | Description | Units |
| --- | --- | --- |
| TIMESTAMP | Time Stamp |  |
| RECORD | Record Number |  |
| GHCT_1_10cm_Avg | Control section of Greenhouse plot, inter-tussock soil temperature at 10 cm Replicate 1 | Deg C |
| GHCT_2_10cm_Avg | Control section of Greenhouse plot, inter-tussock soil temperature at 10 cm Replicate 2 | Deg C |
| GHCT_3_10cm_Avg | Control section of Greenhouse plot, inter-tussock soil temperature at 10 cm Replicate 3 | Deg C |
| GH_1_10cm_Avg | Greenhouse, Inter-tussock soil temperature at 10 cm Replicate 1 | Deg C |
| GH_2_10cm_Avg | Greenhouse, Inter-tussock soil temperature at 10 cm Replicate 2 | Deg C |
| GH_3_10cm_Avg | Greenhouse, Inter-tussock soil temperature at 10 cm Replicate 3 | Deg C |
| GHCT_1_10cm_VW | Greenhouse control plot volumetric water content. Replicate 1 | fractional percent |
| GHCT_1_10cm_PA_uS | Greenhouse control plot probe output period. Replicate 1 | uSec |
| GHCT_2_10cm_VW | Greenhouse control plot volumetric water content. Replicate 2 | fractional percent |
| GHCT_2_10cm_PA_uS | Greenhouse control plot probe output period. Replicate 2 | uSec |
| GHCT_3_10cm_VW | Greenhouse control plot volumetric water content. Replicate 3 | fractional percent |
| GHCT_3_10cm_PA_uS | Greenhouse control plot probe output period. Replicate 3 | uSec |
| GH_1_10cm_VW | Greenhouse plot volumetric water content. Replicate 1 | fractional percent |
| GH_1_10cm_PA_uS | Greenhouse plot probe output period. Replicate 1 | uSec |
| GH_2_10cm_VW | Greenhouse plot volumetric water content. Replicate 2 | fractional percent |
| GH_2_10cm_PA_uS | Greenhouse plot probe output period. Replicate 2 | uSec |
| GH_3_10cm_VW | Greenhouse plot volumetric water content. Replicate 3 | fractional percent |
| GH_3_10cm_PA_uS | Greenhouse plot probe output period. Replicate 3 | uSec |

**Control and F10 Soil\_plots**

| Variable | Description | Units |
| --- | --- | --- |
| TIMESTAMP | Time Stamp | TS |
| RECORD | Record Number | RN |
| RTempC_Avg | Reference temperature on AM25T multiplexer | Deg C |
| CT_1_sur_Avg | Control plot surface (just in moss) temperature. Profile 1. | Deg C |
| CT_1_10CM_Avg | Control plot 10 cm temperature. Profile 2. | Deg C |
| CT_1_20CM_Avg | Control plot 20 cm temperature. Profile 2. | Deg C |
| CT_2_SUR_Avg | Reference temperature on AM25T multiplexer | Deg C |
| CT_2_10CM_Avg | Control plot surface (just in moss) temperature. Profile 2. | Deg C |
| CT_2_20CM_Avg | Control plot 10 cm temperature. Profile 3. | Deg C |
| CT_3_SUR_Avg | Control plot 20 cm temperature. Profile 3. | Deg C |
| CT_3_10CM_Avg | Reference temperature on AM25T multiplexer | Deg C |
| CT_3_20CM_Avg | Control plot surface (just in moss) temperature. Profile 3. | Deg C |
| F10_1_SUR_Avg | F10 plot surface (just in moss) temperature. Profile 1. | Deg C |
| F10_1_10CM_Avg | F10 plot 10 cm temperature. Profile 2. | Deg C |
| F10_1_20CM_Avg | F10 plot 20 cm temperature. Profile 2. | Deg C |
| F10_2_SUR_Avg | Reference temperature on AM25T multiplexer | Deg C |
| F10_2_10CM_Avg | F10 plot surface (just in moss) temperature. Profile 2. | Deg C |
| F10_2_20CM_Avg | F10 plot 10 cm temperature. Profile 3. | Deg C |
| F10_3_SUR_Avg | F10 plot 20 cm temperature. Profile 3. | Deg C |
| F10_3_10CM_Avg | Reference temperature on AM25T multiplexer | Deg C |
| F10_3_20CM_Avg | F10 plot surface (just in moss) temperature. Profile 3. | Deg C |

