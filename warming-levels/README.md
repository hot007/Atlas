# Warming levels 

Time periods for which +1.5, +2, +3 and +4 degree Global Warming Levels (GWL) are reached (with respect to pre-industrial 1850-1900 mean value) are computed for CMIP5 and CMIP6 data using 20-year moving windows (for those datasets used in the 'ATLAS-inventory'. **Values correspond to the central year (n) of the 20-year window** where the warming is first reached (the GWL period is thus calculated as **[n-9, n+10]**). Cells with **'NA'** indicate that the GWL was not reached before (the central year) 2100. Cells with **'9999'** correspond to models with no available data for the particular scenario. The script provided for GWL calculation builds directly on the information available at 'aggregated-datasets', in particular using the global values in the last column of the files.

**CMIP5 and CMIP6 warming level results are shown in the files *CMIPx_Atlas_WarmingLevels.csv***

The use of a 20-year moving window is selected to be consistent with 20-year time slices typically used for future projections: the near-term (2021-2040), mid-term (2041-2060) and long-term (2081-2100). However, figures *CMIP5_WarmingLevels_spread_scenario.pdf* compares the results for 20-year and 30-year windows using the large CMIP5 ensemble. 

**Similar repositories***
A similar repository for GWL calculation is maintained by [Mathias Hauser](https://github.com/mathause/cmip_warming_levels) and provides similar information which allows double-checking the results. Inconsistencies (attributable to different versions) have been detected for 1.5_ssp126: FGOALS-g3_r1i1p1f1 (grid gr, 2020), GFDL-CM4_r1i1p1f1 (grid gr1, 2031).


