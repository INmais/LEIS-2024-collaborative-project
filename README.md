# LEIS-2024-collaborative-project

Prior: https://github.com/INmais/LEIS-2001-collaborative-project

Copy the prior example with FB data

https://colab.research.google.com/github/INmais/LEIS-2001-collaborative-project/blob/main/Mobility/Mobility_geospatial_data.ipynb

# Meta 
Info: 
- `movement-distribution-maps`: https://dataforgood.facebook.com/dfg/tools/movement-distribution-maps (2 samples PT), reading drive (more than 25MB)
- `commuting-zones`: https://dataforgood.facebook.com/dfg/tools/commuting-zones
- `travel-patterns`: https://dataforgood.facebook.com/dfg/tools/travel-patterns
- `colocation-maps`: https://dataforgood.facebook.com/dfg/tools/colocation-maps

# OpenCelliD
OpenCelliD: https://www.opencellid.org/#zoom=16&lat=37.77889&lon=-122.41942

Columns present in database:

| **Parameter**     | **Description**                                                                                                                                                  |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Radio**          | The generation of broadband cellular network technology (e.g., LTE, GSM).                                                                                       |
| **MCC**            | Mobile country code. This information is publicly shared by the International Telecommunication Union (link).                                                   |
| **MNC**            | Mobile network code. This information is publicly shared by the International Telecommunication Union (link).                                                   |
| **LAC/TAC/NID**    | Location Area Code or equivalent.                                                                                                                               |
| **CID**            | A unique number used to identify each Base Transceiver Station (BTS) or sector of BTS.                                                                          |
| **Longitude**      | A geographic coordinate specifying the east-west position of a point on the Earth's surface.                                                                    |
| **Latitude**       | A geographic coordinate specifying the north-south position of a point on the Earth's surface.                                                                  |
| **Range**          | Approximate area within which the cell could be (in meters).                                                                                                   |
| **Samples**        | Number of measures processed to get a particular data point.                                                                                                    |
| **Changeable=1**   | Indicates that the location is determined by processing samples.                                                                                                |
| **Changeable=0**   | Indicates that the location is directly obtained from the telecom firm.                                                                                         |
| **Created**        | When a particular cell was first added to the database (UNIX timestamp).                                                                                        |
| **Updated**        | When a particular cell was last seen (UNIX timestamp).                                                                                                          |
| **AverageSignal**  | The average signal strength of measurements processed from data contributors. Most values are 0 due to missing signal strength information.                      |

https://wiki.opencellid.org/wiki/Menu_map_view#database

# Mobility Database

GTFS Schedules
https://mobilitydatabase.org/feeds/mdb-1036

## Requested
- Mapbox Movement (sample, google drive)
- Waze

Ask: https://insights.sustainability.google/labs?hl=en-US 

Copernicus (not sure if this does the trick)
- Sentinel-1 Level 1 Ground Range Detected (GRD) traffic  https://hda.central.data.destination-earth.eu/ui/dataset/EO.ESA.DAT.SENTINEL-1.L1_GRD
