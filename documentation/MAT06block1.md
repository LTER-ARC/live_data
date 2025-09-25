# Block 1

Air temperature/RH, soil temperatures, and soil moisture are measured in the greenhouse, control, and F10 treatment plots. The station was first set up in 2008, using HOBO H8 4-Channel External data loggers to measure soil temperatures in the control and F10 plots. Three replicate depth profiles (surface, 10, 20 cm) at the 5, 10, and 15 meter stakes were installed about 1-2 meters inside the plots. In 2012, a CR21x logger with an AM25T multiplexer using type T thermocouples replaced the Hobos. In 2018, a CR1000 with air temperature/RH, soil temperature, and moisture was added to the greenhouse plot and the control portion of the greenhouse plot. In 2023, the AM25T multiplexer was wired to the CR1000, eliminating the separate soil logger.

## Data loggers

**Current setup:** Campbell Science CR1000 LOGGER with AM25T multiplexer

**Sensor Descriptions**

-   RELATIVE HUMIDITY/TEMPERATURE: Campbell Scientific, CS500 Temperature and Relative Humidity Probe. Uses PRT for temperature measurement, a capacitive RH chip for RH. Accuracy is ±3% over 10-90% RH; ±6% over 90-100% RH. Manufactured by Vaisala, Inc.

-   THERMOCOUPLES: Omega Engineering, Copper-Constantan wire. Range -200 to 350 °C. Limits of error: Standard wire 1.0°C or 0.75% above 0°C and 1.0°C or 1.5% below 0°C. Special wire 0.5°C or 0.4%.

-   107 THERMISTERS: Campbell Scientific, BetaTherm 100K6A1IA Thermistor, tolerance - ±0.2°C,

-   SOIL MOISTURE: Campbell Scientific, CS616, water content accuracy - ±2.5% VWC (using standard calibration with bulk EC of ≤ 0.5 dS m-1, bulk density of ≤ 1.55 g cm-3, and measurement range of 0% to 50% VWC) **NOTE: need to apply correction for measuring in peaty soils.**

**List of manufacturers and suppliers.**

Campbell Scientific, Inc. 81 W. 1800 N. Logan, Utah 84321-1784 (435)750-1739\
Omega Engineering, Inc. P.O. Box 4047, Stamford, CT 06907-0047 (800)826-6342

#### **Log of Changes**

-   2008 Added Hobo loggers to CT and F10 plots. Three replicate depth profiles (surface, 10, 20 cm).
-   2012-07-13 Campbell Scientific 21X logger with AM25T multiplexer (Longitude -149.609083, Latitude 68.622629) set up in MAT06 Block 1 CT (control) and F10 plots measuring soil temperatures using type T thermocouples. Three replicate depth profiles (surface, 10, 20 cm) were installed at the 5, 10, and 15 meter south side plot stakes about 1-2 meters inside the plots. A small pit was cut into the soil and the thermocouples were inserted into the side wall of the pit.
-   2018-06-11 CR1000 logger station with air/RH CS500 sensors in and out of the greenhouse. Using repurposed SC616 soil moisture and 107 temperature probes. Lots of extra cables.
-   2019-08-17 Changed from 21x logger to a CR10x-PB
-   2021-06-08 Ian Klupar changed the CR10x-PB logger since it stopped working during the winter.
-   2023-06-10 Savannah and Jim rewired the soil logger station, with cables extending to the GH CR1000 station. This station now only has the AMT25T multiplexer wired to the GH CR1000. The program was rewritten to include the soil plot TC. Tables were renamed – Metadata = air temperature and RH; GHPlotsoil = inside and outside soil temperatures and moisture at 10 cm; Soil_plots = soil temperature in the CT and F10.

#### **Current Data Tables**

**Greenhouse Met_data**

| Variable   | Description                                    | Units |
|------------|------------------------------------------------|-------|
| TIMESTAMP  | Time Stamp                                     |       |
| RECORD     | Record Number                                  |       |
| Air_3M_Avg | Air temperature at 3 meters                    | Deg C |
| RH         | Relative humidity at 3 meters                  | \%    |
| GH_Air_Avg | Air temperature inside greenhouse              | Deg C |
| GH_RH      | Relative humidity inside greenhouse            | \%    |
| BattV_Min  | Battery voltage minimum for measurement period | Volts |

**Greenhouse Plot Soil**

| Variable | Description | Units |
|------------------------|------------------------|------------------------|
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

**Control and F10 Soil_plots**

| Variable | Description | Units |
|------------------------|------------------------|------------------------|
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
