# LEIS-2024-collaborative-project

Prior: https://github.com/INmais/LEIS-2001-collaborative-project

Copy prior example with FB data

https://colab.research.google.com/github/INmais/LEIS-2001-collaborative-project/blob/main/Mobility/Mobility_geospatial_data.ipynb


Meta: Movement Distribution Maps (2 samples PT)
Info: https://dataforgood.facebook.com/dfg/tools/movement-distribution-maps

Mapbox Movement
(sample, google drive)

Cell IDD

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
