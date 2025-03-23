# Optimal Agrivoltaic Locations in Greece

## Project Description

This project aims to identify optimal locations in Greece for agrivoltaic systems by conducting a comprehensive analysis of geopolitical and environmental factors. The goal is to maximize the effectiveness of land use for both agriculture and solar energy generation, while considering policy constraints, energy infrastructure, and local economic conditions.

## Requirements

This project requires the following geospatial data:

- Shapefile of Greece (for base map and regional analysis).
- EuroDEM TIFF file (for elevation and terrain analysis).
- TIFF file of suitable slope data for Greece (for slope suitability analysis).
- SGDB_PTR shapefile of Greece (for grid infrastructure analysis).

## Why Agrivoltaics?

- **Increased land productivity:** Combined use of land for solar energy and agriculture.
- **Potential for higher crop yields:** Certain crops benefit from the shade and microclimate provided by solar panels.
- **Water conservation and evaporation reduction:** Shade from solar panels can reduce water evaporation.
- **Improved solar panel efficiency:** Evapotranspiration from crops can cool solar panels, increasing their efficiency.
- **Diversified income streams for farmers:** Additional revenue from solar energy generation.

## Data Collection

- **Geopolitical Data:**
  - Greece's Ministry of Environment and Energy: Land-use policies, grid infrastructure, and zoning regulations.
- **Solar Radiation Data:**
  - NASA’s Solar Resource Database.
  - European Commission's Photovoltaic Geographical Information System (PVGIS).
- **Agricultural Data:**
  - Regional crop yield data from the Hellenic Statistical Authority.
- **Geospatial Data:**
  - Shapefile of Greece.
  - EuroDEM TIFF file.
  - TIFF file of suitable slope data for Greece.
  - SGDB_PTR shapefile of Greece.

## Data Cleaning

- Preprocessing of geospatial and tabular datasets.
- Ensuring consistency in units, timeframes, and geographic boundaries.

## Geospatial Analysis

- Use of GIS tools to map and analyze solar potential, land use, and infrastructure proximity.
- Creation of overlays to visualize regions with high agrivoltaic potential.
- Identification of key scoring criteria:
  - Solar potential (e.g., kWh/m²)
  - Crop yield (e.g., tons/hectare)
  - Infrastructure proximity (e.g., distance to grid)
  - Policy support (e.g., incentives, regulations)
  - Slope suitability.
  - Elevation.

## Solar Analysis

- **Solar Irradiance:**
  - Focus on Global Horizontal Irradiance (GHI) as the primary parameter for calculating electricity yield of solar photovoltaic (PV) systems.
  - Analysis of average GHI over a random day for each month from the past year.
  - If possible, inclusion of data on existing solar panels in Greece to benchmark potential locations.
- **Infrastructure Proximity:**
  - Assessment of the distance to existing grid infrastructure (using SGDB_PTR).
  - Determination of feasibility and cost of grid connection.
- **Policy Support:**
  - Investigation of incentives and regulations promoting agrivoltaic systems.
  - Focus on specific regions with supportive policies.

## Agriculture Analysis

- **Land Availability:**
  - Identification of agriculturally available land across Greece suitable for agrivoltaic projects.
- **Soil Health & Fertility:**
  - Assessment of soil fertility and soil health to determine areas where agrivoltaics could improve agricultural productivity.
- **Water Availability & Drought Patterns:**
  - Evaluation of water availability and usage, focusing on regions with irrigation needs.
  - Analysis of drought frequency and rainfall patterns to optimize crop selection and irrigation strategies.
- **Historical Crop Yields:**
  - Review of historical crop yield data to identify regions where agrivoltaic systems might enhance productivity.
- **Environmental & Biodiversity Considerations:**
  - Identification of protected areas to avoid conflicts with conservation efforts.
  - Inclusion of a biodiversity index to assess the potential environmental impact of agrivoltaic installations.
- **Slope and Elevation:**
  - Analysis of slope using the slope TIFF file to exclude areas with extreme slopes.
  - Analysis of elevation using EuroDEM tiff file to exclude areas with extreme elevation.
