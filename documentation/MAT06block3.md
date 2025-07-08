

# Arctic LTER moist acidic tussock tundra 2006 (MAT06) plots

## Block 3

Air temperature/RH, soil temperatures, and soil moisture are measured in the greenhouse, control, and F10 treatment plots. The station was first set up in 2008, in just control and F10 plots, measuring soil temperatures using three replicate depth profiles (surface, 10, 20 cm) at the 5, 10, and 15 meter stakes about 1-2 meters inside the plots. In 2018, the station was moved closer to the new greenhouse plot. Air temperature/RH, soil temperature, and moisture were added in the greenhouse plot and the control portion of the greenhouse plot.

### Log Changes.

* Initial setup: 2008-06-11.  A Campbell Scientific 21X logger, AM16/32 multiplexer, and type T thermocouples were set up in block 3. Depth profiles were set up at the 5, 10, and 15 meter stakes about 1-2 meters inside the Control (CT) and 10 grams Nitrogen plus 5 grams Phosphorus per meter squared (F10) plots. Three depths, surface, 10, and 20 cm, were installed into the side of a small dug pit.
  * CT_1 SUR, CT_1 10CM, CT_1 20CM, CT_2 Sur, CT_2 10CM, CT_2 20CM, CT_3 Sur, CT_3 10CM, CT_3 20CM, F10_1 Sur, F10_1 10CM, F10_1 20CM, F10_2 Sur, F10_2 10CM, F10_3 20CM, F10_3 Sur, F10_3 10CM, F10_3 20CM
* 2011-06-09, upward and downward LiCor PAR sensors were added.
* 2012-06-10 Added up and down CS300 Pyranometers for Albedo.
* 2018-08-10 Move the station closer to the GH so Temperature/RH, thermistors, and soil moisture sensors can reach. Changed logger to a CR1000 and multiplexer to an AM25T. Added greenhouse HMP60 temperature and relative humidity, CS616 soil moisture, and 107 soil temperature sensors.  Three 107 were placed in CT and GH plots at ~ 20 cm.  Only 1 CT and 1 GH CS616 soil moisture sensors were installed at ~ 20 cm. Need to add more.
  * Measurements added:
  * AirTControl_Avg, RHCT, Air_GH_Avg, RH_GH,
  * T107_C_CT1_Avg, T107_C_CT2_Avg, T107_C_CT3_Avg, T107_C_GH1_Avg, T107_C_GH2_Avg, T107_C_GH3_Avg, VW_CT_Avg, PA_uS_CT_Avg, VW_GH_Avg, PA_uS_GH_Avg
  * Measurements for all sensors are 30-minute averages of 1-minute reads.
* 2019-08-16 Changed radio from FreeWave FG radio to a Campbell Sci. RF401 with Pak Bus OS version 4.
* 2019-08-20 Changed output so there are two tables. One for the Met data (60 sec reads and 30 min averages) and a second one for the soil data (180 sec reads and 180 min averages). This should help the battery drain in the winter.

Data Tables
----------------------------------------------------
**Table: MetData**
Interval: 30 MIN
Fields:
 BattV_Avg    Units: Volts
 AirTControl_Avg    Units: Deg C
 RHCT    Units: %
 Air_GH_Avg    Units: Deg C
 RH_GH    Units: %
**Table: SoilData**
Interval: 180 MIN
Fields:
 T107_C_CT1_Avg    Units: Deg C
 T107_C_CT2_Avg    Units: Deg C
 T107_C_CT3_Avg    Units: Deg C
 T107_C_GH1_Avg    Units: Deg C
 T107_C_GH2_Avg    Units: Deg C
 T107_C_GH3_Avg    Units: Deg C
 VW_CT_Avg
 PA_uS_CT_Avg    Units: uSec
 VW_GH_Avg
 PA_uS_GH_Avg    Units: uSec
 CT1_SUR_AVG_Avg    Units: Deg C
 CT1_10cm_AVG_Avg    Units: Deg C
 CT1_20cm_AVG_Avg    Units: Deg C
 CT2_SUR_AVG_Avg    Units: Deg C
 CT2_10cm_AVG_Avg    Units: Deg C
 CT2_20cm_AVG_Avg    Units: Deg C
 CT3_SUR_AVG_Avg    Units: Deg C
 CT3_10cm_AVG_Avg    Units: Deg C
 CT3_20cm_AVG_Avg    Units: Deg C
 NP1_SUR_AVG_Avg    Units: Deg C
 NP1_10cm_AVG_Avg    Units: Deg C
 NP1_20cm_AVG_Avg    Units: Deg C
 NP2_SUR_AVG_Avg    Units: Deg C
 NP2_10cm_AVG_Avg    Units: Deg C
 NP2_20cm_AVG_Avg    Units: Deg C
 NP3_SUR_cm_AVG_Avg    Units: Deg C
 NP3_10_AVG_Avg    Units: Deg C
 NP3_20cm_AVG_Avg    Units: Deg C
 RTempC_Avg    Units: Deg C