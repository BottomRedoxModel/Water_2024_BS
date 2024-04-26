# Water_2024_BS (under submission)
2DBP+BROM configuration data for "Model-based analysis of the oxygen budget in the Black Sea water column" article in MDPI Water journal.

## Coupled model setup
- The [2DBP source code](https://github.com/BottomRedoxModel/2DBP)
- The [BROM source code](https://github.com/BottomRedoxModel/BROM)
- The [FABM source code](https://github.com/limash/fabm-omp)

## Input data
Copernicus Marine Service (CMEMS) [Black Sea Physics Reanalysis dataset](https://data.marine.copernicus.eu/product/BLKSEA_MULTIYEAR_PHY_007_004)

## [How to build](https://github.com/BottomRedoxModel/Wiki/wiki)

## Article cases
In "whithout increased sinking velocity" case set the **WMn** variable in **fabm.yaml** to 0.0.
In "with increased sinking velocity" case set the **WMn** variable in **fabm.yaml** to -15.0.
