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

SUBTEMA 1.9 Inquérito às Condições de Vida, Origens e Trajetórias da População
Residente - ICOT
https://www.ine.pt/ngt_server/attachfileu.jsp?look_parentBoui=653723577&att_display=n&att_download=y (data center) but  mobilidade casatrabalho/escola (meio de transporte usado nas principais deslocações)

E00261_rec	Meio de transporte - a pé	"  1  Sim
  2  Não
  8  Prefere não responder"
E00262_rec	Meio de transporte - automóvel particular	"  1  Sim
  2  Não
  8  Prefere não responder"
E00263_rec	Meio de transporte - motociclo/ciclomotor	"  1  Sim
  2  Não
  8  Prefere não responder"
E00264_rec	Meio de transporte - bicicleta/trotineta	"  1  Sim
  2  Não
  8  Prefere não responder"
E00265_rec	Meio de transporte - transporte escolar/da empresa	"  1  Sim
  2  Não
  8  Prefere não responder"
E00266_rec	Meio de transporte - autocarro/camioneta de transporte público	"  1  Sim
  2  Não
  8  Prefere não responder"
E00267_rec	Meio de transporte - eléctrico	"  1  Sim
  2  Não
  8  Prefere não responder"
E00268_rec	Meio de transporte - metro/metropolitano	"  1  Sim
  2  Não
  8  Prefere não responder"
E00269_rec	Meio de transporte - comboio	"  1  Sim
  2  Não
  8  Prefere não responder"
E002610_rec	Meio de transporte - barco ou ferry	"  1  Sim
  2  Não
  8  Prefere não responder"
E002611_rec	Meio de transporte - taxi/veículo ligeiro de plataforma tecnológica	"  1  Sim
  2  Não
  8  Prefere não responder"
E002612_rec	Meio de transporte - outro meio de transporte motorizado	"  1  Sim
  2  Não
  8  Prefere não responder"
E002613_rec	Meio de transporte - outro meio de transporte não motorizado	"  1  Sim
  2  Não
  8  Prefere não responder"
E002697_rec	Meio de transporte - não se aplica (não se desloca)	"  1  Sim
  2  Não
  8  Prefere não responder"
tempo_desloc	Duração da deslocação casa-escola/trabalho recodificada	"  1  Menos de meia hora
  2  Mais de meia hora e até uma hora
  3  Mais de uma hora
  4  NS/NR"
E0028	Tem automóvel próprio	"  1  Sim
  2  Não
  8  Prefere não responder
  9  Não sabe"![image](https://github.com/user-attachments/assets/64216780-cc2c-4426-ae3b-6edf050143a0)


Copernicus (not sure if this does the trick)
- Sentinel-1 Level 1 Ground Range Detected (GRD) traffic  https://hda.central.data.destination-earth.eu/ui/dataset/EO.ESA.DAT.SENTINEL-1.L1_GRD

https://colab.research.google.com/github/INmais/LEIS-2001-collaborative-project/blob/main/Mobility/Mobility_geospatial_data.ipynb



