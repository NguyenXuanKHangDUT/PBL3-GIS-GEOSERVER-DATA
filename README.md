# GeoServer Data Directory for PBL3 GIS APP

This repository contains the GeoServer data directory used by the PBL3 GIS application.

Expected deployment structure:

/home/ubuntu/
├── traffic-gis/
└── geoserver_data_dir_unzip/
    └── GeoServer/

GeoServer must be started with:

```bash
export GEOSERVER_HOME=/opt/geoserver
export GEOSERVER_DATA_DIR=/home/ubuntu/geoserver_data_dir_unzip/GeoServer
