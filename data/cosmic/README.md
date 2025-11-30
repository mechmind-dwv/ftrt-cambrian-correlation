# Cosmic Data

This directory contains raw and processed cosmic data used for the FTRT-Cambrian Correlation Project.

## Subdirectories

- `raw/`: Raw data from external sources (JPL Horizons, GEOMAGIA50, etc.)
- `processed/`: Processed data ready for analysis

## Data Sources

- **JPL Horizons**: Planetary ephemeris data
- **GEOMAGIA50**: Paleomagnetic field intensity records
- **NOAA**: Solar activity data
- **NASA**: Cosmic ray flux measurements

## File Naming Convention

- Raw files: `{source}_{dataset}_{date_range}.csv`
- Processed files: `{dataset}_{processing_date}.csv`
