# Identification and Prioritisation of Underground Hydrogen Storage Sites in Nigeria
## Overview

This project presents a GIS-based Multi-Criteria Decision Analysis (MCDA) framework for identifying and prioritising suitable underground hydrogen storage (UHS) locations across Nigeria.

Underground hydrogen storage is considered a critical technology for enabling large-scale renewable energy integration by providing long-duration energy storage capabilities. This project investigates Nigeria's geological and infrastructural potential for UHS deployment by integrating multiple spatial datasets and decision-support techniques.

The analysis combines Geographic Information Systems (GIS), Analytical Hierarchy Process (AHP), and Weighted Linear Combination techniques to generate suitability maps for potential hydrogen storage development.

# Project Objectives

The main objectives of this study were to:

- Identify key geological, technical, infrastructural, and environmental factors influencing underground hydrogen storage suitability.
- Develop a GIS-based MCDA framework for spatial site assessment.
- Apply AHP to determine relative importance weights of evaluation criteria.
- Generate suitability maps identifying priority areas for future hydrogen storage investigation.


# Methodology

The workflow consisted of five major stages:

## 1. Data Collection

Multiple spatial datasets were collected, including:

- Geological data
- Lithology
- Hydrogeological characteristics
- Fault density
- Pipeline infrastructure
- Energy hubs
- Road networks
- Digital Elevation Models (DEM)
- Land Use/Land Cover (LULC)
- Protected areas

---

## 2. Data Processing and Harmonisation

Spatial datasets were processed using:

- Coordinate system standardisation
- Raster conversion
- Spatial interpolation
- Distance analysis
- Terrain analysis
- Reclassification

All datasets were harmonised using WGS 84 UTM Zone 32N at a 100 m spatial resolution.

---

## 3. Multi-Criteria Decision Analysis

Nine suitability criteria were evaluated:

| Category | Criteria |
|---|---|
| Geological | Geology, Lithology, Hydrogeology |
| Structural | Fault Density |
| Infrastructure | Pipelines, Energy Hubs, Roads |
| Terrain | Slope |
| Environmental | Land Use/Land Cover |

The Analytical Hierarchy Process (AHP) was applied to assign criterion weights.

The consistency ratio achieved was 0.012, demonstrating acceptable consistency in the weighting process.

---

## 4. Suitability Modelling

A weighted linear combination approach was used to combine the reclassified spatial layers.

Suitability classes were generated:

- Unsuitable
- Very Low Suitability
- Low Suitability
- Moderate Suitability
- High Suitability
- Very High Suitability

Protected areas were applied as exclusion constraints.

---

# Key Findings

The analysis identified significant underground hydrogen storage potential across Nigeria.

Key findings include:

- High suitability areas covered approximately 206,307 km² (23.1%).
- Very High suitability areas covered approximately 70,885 km² (8.0%).
- Combined High and Very High suitability zones represented approximately 277,192 km² (31.1%) of Nigeria's analysed land area.

Priority regions identified include:

- Niger Delta Basin
- Anambra Basin
- Upper Benue Trough
- Selected areas within the Chad Basin

The Niger Delta emerged as the highest priority region due to favourable geology, existing energy infrastructure, and proximity to industrial hubs.

---

# Tools and Technologies

## GIS & Spatial Analysis

- ArcGIS Pro 3.5
- Spatial Analyst Extension
- Raster Analysis
- Weighted Overlay Analysis
- Suitability Mapping

## Data Analysis

- Microsoft Excel
- Analytical Hierarchy Process (AHP)

## Data Sources

Datasets were obtained from:

- World Bank
- British Geological Survey
- UNEP-WCMC
- Global Lithological Map (GLiM)
- World Food Programme
- Oil and Gas Infrastructure Mapping (OGIM)
- ESRI Sentinel-2 Land Cover Dataset

---

# Repository Structure

