# Automated-Drought-Detection-using-Vegetation-and-Temperature-Indices
This project utilizes remote sensing data and Google Earth Engine to analyze crop drought conditions by calculating Vegetation Condition Index (VCI), Temperature Condition Index (TCI), and Vegetation Health Index (VHI). These indices are valuable for understanding the impact of drought on agriculture, allowing for proactive intervention in drought-prone regions.
## Table of Contents
- [Project Overview](#project-overview)
- [Motivation](#motivation)
- [Features](#features)
- [Use Cases](#use-cases)
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Acknowledgments](#acknowledgments)
- [License](#license)
## Project Overview
This project analyzes crop drought by leveraging satellite-based remote sensing data and processing it on the Google Earth Engine platform. The core of the analysis focuses on the computation of drought indices (VCI, TCI, and VHI) to visualize and quantify the extent of drought stress on crop vegetation. This project provides key insights for agricultural management, enabling decision-makers to detect early signs of drought stress and implement timely interventions.

## Motivation
With increased frequency of droughts due to climate change, it is critical to monitor crop health and prevent large-scale agricultural losses. Remote sensing data allows for real-time, large-scale monitoring of vegetation health, offering a reliable tool for detecting and mitigating the impact of drought on crop productivity. This project aims to support data-driven agricultural management through accessible and reliable drought monitoring techniques.

## Features
- **Data Acquisition**: Automated retrieval of Landsat 8 images using Google Earth Engine, allowing for large-scale data processing.
- **Drought Indices Calculation**: Computes Vegetation Condition Index (VCI), Temperature Condition Index (TCI), and Vegetation Health Index (VHI).
- **Interactive Map Visualization**: Generates map visualizations of VCI, TCI, and VHI to highlight affected areas.
- **Export Functionality**: Exports GeoTIFF files of drought indices for further use or integration into GIS applications.
- **Region of Interest Selection**: Allows users to define specific areas for targeted drought analysis.

## Use Cases
- **Agricultural Monitoring**: Identifying drought-stressed regions in agricultural land for early intervention.
- **Drought Assessment**: Provides critical data to aid in governmental and NGO drought relief efforts.
- **Climate Research**: Analyzes the correlation between climate change and drought severity across different regions.

## Technologies Used
- **Google Earth Engine**: For satellite data processing and geospatial analysis.
- **Geemap**: Python package to interact with Google Earth Engine and visualize map outputs.
- **Python**: Core programming language used for data processing and model computation.
- **Landsat 8**: Source of high-resolution spectral data for vegetation and temperature analysis.

## Data Description
This project relies on the following data sources:
- **Landsat 8 Surface Reflectance**: Provides spectral bands used for calculating NDVI.
- **Landsat 8 Thermal Infrared**: Supplies the thermal data needed to compute the Temperature Condition Index.

## Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/YourUsername/Crop-Drought-Analysis.git
