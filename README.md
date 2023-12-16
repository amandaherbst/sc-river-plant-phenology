# Using NDVI calculations to investigate seasonality of different phenologies near the Santa Clara river.

A short workflow to visualize seasonal cycles of different vegetation productivity near the Santa Clara river

## Workflow Goals

- Investigate plant phenology by converting spectral reflectance into a measure of vegetation productivity (NDVI)
- Calulate NDVI throughout the year
- Summarize NDVI values within vegetation communities
- Visualize changes in NDVI within vegetation communities

## What's in this repo?
.
|
├── Outputs/                        # visualizations and tables that the workflow should output if working correctly
|  └── seasonal_productivity.png    # plot of the seasonal productivity for various vegetation near the Santa Clara river
|
├── R/                                # folder for code used in workflow
|  └── sc-river-ndvi.rmd        # a R markdown containing background and workflow
|  └── sc-river-ndvi.html    # R markdown knitted to html
|
├── README.md
├── .gitignore
└── sc-river-plant-phenology.Rproj

## Data Access

The Landsat data was downloaded, stored locally, and added to .gitignore. References to the data can be found in the .rmd.
