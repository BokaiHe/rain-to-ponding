# Data sources and published methods

Original data and scientific methods are credited to their providers and authors. This project distributes processed display/model assets; it does not claim ownership of the source datasets. Provider terms apply to third-party data independently of the project-rights notice.

| Source | Role |
|---|---|
| [NOAA 2017 NYC topobathy hydro-enforced DEM](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/) | Terrain |
| [NYC Open Data](https://opendata.cityofnewyork.us/) | Borough, building, street and park geometry |
| [NYC hydrography](https://data.cityofnewyork.us/Environment/NYC-Planimetric-Database-Hydrography/pjs3-c3z5) | Permanent water bodies |
| [Iowa Environmental Mesonet](https://mesonet.agron.iastate.edu/request/download.phtml) | Historical station rainfall |
| [FloodNet flood events](https://data.cityofnewyork.us/Environment/FloodNet-Flood-Events/aq7i-eu5q) and [sensor deployments](https://data.cityofnewyork.us/resource/kb2e-tjy3.json) | Independent point observations |
| [NYC official stormwater map](https://www.arcgis.com/home/item.html?id=bb0e97a624424d3287d8445f573127ce) | Modeled scenario extent, not observed inundation |
| [Barnes, Callaghan & Wickert (2020)](https://esurf.copernicus.org/articles/8/431/2020/) | Depression hierarchy method |
| [Barnes, Callaghan & Wickert (2021)](https://esurf.copernicus.org/articles/9/105/2021/) | Fill–Spill–Merge method |

The packaged data/manifest.json retains acquisition metadata and exact source requests. Paths referring to raw or archived inputs are provenance records, not files included in this repository. Some catalog entries document investigations rather than runtime evidence; the interface distinguishes unavailable observations.

## Recorded acquisition URLs

- [data-raw/vector/boroughs.json](https://data.cityofnewyork.us/resource/gthc-hcne.json)
- [data-raw/vector/buildings-1.json](https://data.cityofnewyork.us/resource/5zhs-2jue.json)
- [data-raw/vector/style-streets.json](https://data.cityofnewyork.us/resource/inkn-q76z.json)
- [data-raw/vector/style-parks.json](https://data.cityofnewyork.us/resource/enfh-gkve.json)
- [data-raw/dem/be_NYC_025.tif](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/be_NYC_025.tif)
- [data-raw/dem/be_NYC_020.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_020.json)
- [data-raw/dem/be_NYC_025.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_025.json)
- [data-raw/dem/be_NYC_026.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_026.json)
- [data-raw/dem/be_NYC_029.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_029.json)
- [data-raw/dem/be_NYC_030.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_030.json)
- [data-raw/dem/be_NYC_033.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_033.json)
- [data-raw/dem/be_NYC_034.json](https://noaa-nos-coastal-lidar-pds.s3.amazonaws.com/dem/NYC_topobathy_hydroEnforced_DEM_2017_9310/stac/be_NYC_034.json)
- [data-raw/subway/metadata.json](https://data.ny.gov/api/views/i9wp-a4ja.json)
- [data-raw/subway/entrances.json](https://data.ny.gov/resource/i9wp-a4ja.json?$limit=10000)
- [data-raw/rain/ida-hourly.csv](https://mesonet.agron.iastate.edu/cgi-bin/request/hourlyprecip.py?station=NYC&network=NY_ASOS&sts=2021-09-01T00:00:00Z&ets=2021-09-03T00:00:00Z&tz=UTC&lalo=1)
- [data-raw/rain/oct30-hourly.csv](https://mesonet.agron.iastate.edu/cgi-bin/request/hourlyprecip.py?station=NYC%2CLGA%2CJFK&network=NY_ASOS&sts=2025-10-29T00%3A00%3A00Z&ets=2025-11-01T00%3A00%3A00Z&tz=UTC&lalo=1)
- [data-raw/floodnet/deployments.json](https://data.cityofnewyork.us/resource/kb2e-tjy3.json?$limit=5000)
- [data-raw/floodnet/oct30-events.json](https://data.cityofnewyork.us/resource/aq7i-eu5q.json)
- [data-raw/floodnet/floodnet-flood-sensor-sep-2021.csv](https://zenodo.org/records/10211443)
