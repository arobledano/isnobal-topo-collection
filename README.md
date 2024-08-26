# isnobal-topo-collection
Database of basin's topography files required as input to run the iSnobal model. 

For every basin and spatial resolution, it should be provided: the native DEM file that contains the watershed domain (polys folder), the Landfire params file, the configuration file (.ini) and the eventually generated topo.nc:

```bash
└── basin_resolution
    ├── basin_CRS_resolution.tif
    ├── config_resolution.ini
    ├── landfire_veg_param.csv
    ├── polys
    │   ├── basin_outline_HUCXX_CRS.cpg
    │   ├── basin_outline_HUCXX_CRS.dbf
    │   ├── basin_outline_HUCXX_CRS.prj
    │   ├── basin_outline_HUCXX_CRS.shp
    │   └── basin_outline_HUCXX_CRS.shx
    └── topo.nc
```


