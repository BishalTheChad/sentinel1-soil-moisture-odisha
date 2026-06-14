# Sentinel-1 Soil Moisture Monitor — Odisha, India

A satellite-based soil moisture monitoring system for rice-farming 
districts in Odisha, built using Sentinel-1 SAR (Synthetic Aperture 
Radar) data processed in Google Earth Engine.

## The Problem
Rice farmers in Odisha lose yield every year from both over-irrigation 
and under-irrigation. Conventional soil sensors are expensive and cover 
only one field. Satellite data can monitor thousands of fields 
simultaneously — for free.

## What This Project Does
- Retrieves Sentinel-1 C-band SAR data (VV and VH polarization) 
  over Cuttack district
- Estimates surface and root-zone soil moisture at 10m resolution
- Compares moisture levels against crop water requirements by 
  growth stage
- Outputs an irrigation advisory: irrigate / monitor / no action needed

## Why SAR?
Optical satellites (like Sentinel-2) cannot see through clouds. 
Odisha receives 1400mm of rainfall mostly during the kharif season — 
exactly when farmers need irrigation guidance most. SAR sees through 
clouds day and night.

## Data Sources
- Sentinel-1 GRD (ESA Copernicus) — SAR backscatter
- SMAP Level 3 (NASA) — validation
- CHIRPS — rainfall
- ICAR crop water requirement tables

## Status
 Week 1 — Study area defined, first Sentinel-1 visualization complete

## Author
Bishal — Earth Science undergraduate, Odisha
Building toward an MSc in Geophysics.
