# Wildfire in Black Hills

## Project Overview
This project provides a spatial analysis of wildfires in Black Hills National Forest to assist Crazy Horse Memorial in making informed decisions regarding its development and contingency planning. The analysis examines the spatial distribution, frequency, causes, and severity of wildfires using point pattern analysis, density estimation, and statistical modeling.

## Dataset
- **Source:** United States Forest Service (USFS)
- **Timeframe:** 1970-2022 (last updated March 2023)
- **Attributes:**
  - `LONG`, `LAT`: Wildfire origin coordinates
  - `TOTALACRES`: Total acres burned
  - `FIREYEAR`, `FIREMONTH`: Date of fire occurrence
  - `STATCAUSE`: Cause of fire
  - `FIRENAME`: Name of the fire

## Key Analyses
- **Exploratory Data Analysis:** Trends over time, distribution of causes, and fire frequency.
- **Point Pattern Analysis:** Variance-mean ratio test, quadrat analysis, and kernel density estimation to assess clustering.
- **Nearest Neighbor & Clark-Evans Tests:** Quantification of clustering vs. random distribution.
- **Environmental Interaction:** Correlation between fire severity and factors like annual rainfall, temperature, and elevation.
- **Seasonal Interaction Analysis:** Examining how fire severity changes with different seasons.

## Requirements
This analysis was conducted using R with the following packages:
- `sf`, `tmap`, `spatstat` for spatial analysis
- `ggplot2`, `ggstatsplot` for visualization
- `lm` for regression modeling

## How to Use
### R Code Execution
1. Load the dataset in R.
2. Run the provided R scripts to generate maps and statistical outputs.
3. Adjust parameters to explore additional insights.

### HTML Report
- A polished HTML version of the analysis is available for interactive exploration.
- Open the HTML file in a web browser to view maps, graphs, and insights.

## Conclusion
The analysis reveals that while the Crazy Horse Memorial area experiences frequent wildfires, their burn area is relatively small. Clustering patterns suggest spatial dependencies, but annual rainfall shows little impact on fire severity. Further studies can explore additional environmental factors.

For any questions or further details, please refer to the full analysis in the HTML report.

