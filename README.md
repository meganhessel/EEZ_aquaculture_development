
# EDS 223: EEZ Aquaculture Suitable Habitat

### PURPOSE

This repository 

By examining species' temperature and depth requirements, this repository determines which West Coast Exclusive Economic Zones (EEZ) is best suited for various marine aquaculture species. Specifically, we study oysters and Siliqua-patula (Pacific razor clam). 


### FILE STRUCTURE

``` text
.
├── README.md
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── deoth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
├── EEZ_aquaculture_development.Rproj
├── eez_aquaculture_development.html
├── eez_aquaculture_development.pdf
├── eez_aquaculture_development.qmd
└── eez_aquaculture_development
    ├── figure-html
    │   └── (rendered figures)
    └── libs
        └── (Quarto support files)
```

### DATA ACCESS

The data used for this project is West Coast Sea Surface Temperature (SST), bathymetry measurements, and Exclusive Economic Zones geometries. 

**Data information:**

-   For this research, all data was accessed on November 25, 2025.

-   SST data is from NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1, accessible at <https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php>.

-   Bathymetry data is from General Bathymetric Chart of the Oceans (GEBCO), accessible at <https://www.gebco.net/data-products/gridded-bathymetry-data#area>.

-   Exclusive Economic Zones geometries is from Marineregion.org, accessible at <https://www.marineregions.org/eez.php>.

.....

AUTHOR: Megan Hessel (MEDS 2026)

.....

REFERENCES:

Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M. Blue Frontiers: Managing the Environmental Costs of Aquaculture (The WorldFish Center, Penang, Malaysia, 2011).↩︎

Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. Nature Ecology & Evolution, 1, 1317-1324 (2017).↩︎

GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c)

.....

ACKNOWLEDGEMENTS: I would like to thank Dr. Annie Adams and Ale Vidal Meza for helping in the creation and development of this project.
