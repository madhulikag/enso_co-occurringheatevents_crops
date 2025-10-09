# enso_co-occurringheatevents_crops

Code for the paper: Understanding ENSO’s Influence on Co-occurring Heat Events across Global Croplands

The order in which the code was executed

1. raw_nino3.4_sst # Code to construct 1870-2025 Niño 3.4 anomalies based on the 1981–2010 monthly climatology
2. StrongENSOyears (Table S1) # Defining moderate and strong ENSO events
3. Croplands # Modifying the resolution of GLAD cropland extent data
4. Crop_calendar # Identifying mean planting and harvesting dates for maize, rice, soybeans, and wheat
6. AEI2015 # Calculated grid-cell irrigated vs rainfed areas
7. detrend_std_anom # Calculated detrended and standardized ppt and tmax anomalies 
8. freq_bootstrap_significance_HD-risk-latest (Figure 1a, S2a, S3a, S4a) # Risk ratio maps, localized significance maps and field significance
9. freq_bootstrap_significance-HW-risk-latest (Figure 1b, S2b, S3b, S4b) # Risk ratio maps, localized significance maps and field significance
10. HD_freq_areas # % global cropland with significant HD frequency
11. HW_freq_areas # % global cropland with significant HW frequency
12. spatial_ext_crop_totalcropland (Figure 2a,c, S1, S5) # country-wise spatial extents of HD/HW
13. total_crop_areas_hd (Figure 2b & S5a (intext)) # relative and absolute differences in global cropland areas exposed to HD
14. total_crop_areas_hw (Figure 2d & S5b (intext)) # relative and absolute differences in global cropland areas exposed to HW
15. spatial_ext_by_crop (Figure 3a, 4a, S8) # data for total_crop_areas_hd, total_crop_areas_hw, areas_hd1-prim-seas, areas_hw1-sec-seas, areas_hd1-prim-sec-seas & areas_hw1-prim-sec-seas is generated in this code # country-wise exposure to multiseason co-occurring events (absolute and normalized)
16. areas_hd1-prim-seas, areas_hw1-sec-seas, areas_hd1-prim-sec-seas & areas_hw1-prim-sec-seas (Figure 3b-c, 4b-c S6-7) # crop-specific exposure during at least one season of the primary growing period




