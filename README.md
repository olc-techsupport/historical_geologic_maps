# Pine Ridge Indian Reservation - Historical Geologic Map Project

## Project Overview
This notebooks displays historical geologic quad and other maps relevant to producing a comprehensive geologic map for the Pine Ridge Indian Reservation

## Data Sources

### **USGS NWIS (Hydrology)**
- **Source**: USGS National Water Information System
- **URL**: https://waterservices.usgs.gov/
- **Data Type**: Streamflow, groundwater levels, water quality
- **Temporal Coverage**: 2010-present
- **Format**: Parquet (time series), GeoJSON (site locations)

### **PRISM (Climate)**
- **Source**: PRISM Climate Group, Oregon State University
- **URL**: https://prism.oregonstate.edu/
- **Data Type**: Precipitation, temperature (min/max/mean)
- **Resolution**: 4km (~800m)
- **Temporal**: Monthly/Daily
- **Format**: NetCDF, Zarr

### **Daymet (Climate)**
- **Source**: Oak Ridge National Laboratory DAAC
- **URL**: https://daymet.ornl.gov/
- **Data Type**: Daily surface weather data
- **Resolution**: 1km
- **Temporal**: Daily (1980-present)
- **Format**: NetCDF, Zarr

### **CDL - Cropland Data Layer**
- **Source**: USDA National Agricultural Statistics Service
- **URL**: https://nassgeodata.gmu.edu/CropScape/
- **Data Type**: Crop type classification
- **Resolution**: 30m
- **Temporal**: Annual (2008-present)
- **Format**: GeoTIFF, NetCDF

### 5. **SMAP (Soil Moisture)**
- **Source**: NASA Soil Moisture Active Passive Mission
- **URL**: https://nsidc.org/data/smap
- **Data Type**: Soil moisture (0-5cm depth)
