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
Parameter	Description
Radio	The generation of broadband cellular network technology (Eg. LTE, GSM)
MCC	Mobile country code. This info is publicly shared by International Telecommunication Union (link)
MNC	Mobile network code. This info is publicly shared by International Telecommunication Union (link)
LAC/TAC/NID	Location Area Code
CID	This is a unique number used to identify each Base transceiver station or sector of BTS
Longitude	Longitude, is a geographic coordinate that specifies the east-west position of a point on the Earth's surface
Longitude	Latitude is a geographic coordinate that specifies the north–south position of a point on the Earth's surface.
Range	Approximate area within which the cell could be. (In meters)
Samples	Number of measures processed to get a particular data point
Changeable=1	The location is determined by processing samples
Changeable=0	The location is directly obtained from the telecom firm
Created	When a particular cell was first added to database (UNIX timestamp)
Updated	When a particular cell was last seen (UNIX timestamp)
AverageSignal	To get the positions of cells, OpenCelliD processes measurements from data contributors. Each measurement includes GPS location of device + Scanned cell identifier (MCC-MNC-LAC-CID) + Other device properties (Signal strength). In this process, signal strength of the device is averaged. Most ‘averageSignal’ values are 0 because OpenCelliD simply didn’t receive signal strength values.

https://wiki.opencellid.org/wiki/Menu_map_view#database
