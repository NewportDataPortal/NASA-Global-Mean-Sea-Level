# NASA Global Mean Sea Level Data

Data downloaded from [NASA Global Climate Change Vital Signs](https://climate.nasa.gov/vital-signs/sea-level/).

This file contains Global Mean Sea Level (GMSL) variations computed at the NASA Goddard Space Flight Center under the auspices of the NASA MEaSUREs program. The GMSL was generated using the Integrated Multi-Mission Ocean Altimeter Data for Climate Research (http://podaac.jpl.nasa.gov/dataset/MERGED_TP_J1_OSTM_OST_ALL_V4.2). It combines Sea Surface Heights from TOPEX/Poseidon, Jason-1, OSTM/Jason-2, and Jason-3 to a common terrestrial reference frame with all inter-mission biases, range and geophysical corrections applied and placed onto a georeferenced orbit. This creates a consistent data record throughout time, regardless of the instrument used.

If you use these data please cite:
GSFC. 2017. Global Mean Sea Level Trend from Integrated Multi-Mission Ocean Altimeters TOPEX/Poseidon, Jason-1, OSTM/Jason-2 Version 4.2 Ver. 4.2 PO.DAAC, CA, USA. Dataset accessed [YYYY-MM-DD] at http://dx.doi.org/10.5067/GMSLM-TJ42.

For information on how the data were generate please refer to:
Beckley, B. D., Callahan, P. S., Hancock, D. W., Mitchum, G. T., & Ray, R. D. (2017). On the 'cal-mode' correction to TOPEX satellite altimetry and its effect on the global mean sea level time series. Journal of Geophysical Research: Oceans, 122. https://doi.org/10.1002/2017JC013090

Beckley, B.D.,  N. P. Zelensky, S. A. Holmes, F. G. Lemoine, R. D. Ray, G. T. Mitchum, S. D. Desai & S. T. Brown, Assessment of the Jason-2 Extension to the TOPEX/Poseidon, Jason-1 Sea-Surface Height Time Series for Global Mean Sea Level Monitoring, Marine Geodesy, Vol 33, Suppl 1, 2010. DOI:10.1080/01490419.2010.491029

As indicated below, heights in various columns are above or below the 20 year time-mean height. If you accessed these data from http://sealevel.nasa.gov or http://climate.nasa.gov, heights plotted there are with respect to the first cycle (January) of 1993.

#### Global Mean Sea Level (GMSL) variations from TPJAOS v4.2

##### column description
1. altimeter type 0=dual-frequency  999=single frequency (ie Poseidon-1)
2. merged file cycle #
3. year+fraction of year (mid-cycle)
4. number of observations
5. number of weighted observations
6. GMSL (Global Isostatic Adjustment (GIA) not applied) variation (mm) with respect to 20-year TOPEX/Jason collinear mean reference
7. standard deviation of GMSL (GIA not applied) variation estimate (mm)
8. smoothed (60-day Gaussian type filter) GMSL (GIA not applied) variation (mm)  with respect to 20-year mean
9. GMSL (Global Isostatic Adjustment (GIA) applied) variation (mm) )  with respect 20-year mean
10. standard deviation of GMSL (GIA applied) variation estimate (mm)
11. smoothed (60-day Gaussian type filter) GMSL (GIA applied) variation (mm) )  with respect to 20-year mean
12. smoothed (60-day Gaussian type filter) GMSL (GIA applied) variation (mm); annual and semi-annual signal removed )  with respect to 20-year mean

Missing or bad value flag: 99900.000