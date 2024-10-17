# Status page of seismic instruments at Ocean Networks Canada 

## Seismic instruments accessible in IRIS
 * Network code: **NV** - https://ds.iris.edu/mda/NV/
 * Network code: **OW**  - https://ds.iris.edu/mda/OW/

## Information on Ocean Networks Canada Wikipage
 * Seismometer: https://wiki.oceannetworks.ca/display/instruments/Seismometers 
 * Acceleromter: 
 * Tiltmeter: 

## How to access our instrument status page
1. To quickly *view* the status of our curently installed instruments:
  https://oceannetworkscanada.github.io/Seismic-instrument-status/
2. To *download* a JSON format file for your own analysis
  https://github.com/OceanNetworksCanada/Seismic-instrument-status/blob/main/SeismicInstruments.json 

## How to interpret the status page (JSON file)

| Keywork | Description |
| ----------- | ----------- |
| locationCode| instrument station code for ONC data base and IRIS |
| deviceCategoryCode| **BBS**: Broadband Seismometer; **SPS**: Short Period Seismometer; **ACCELEROMETER**; **TILTMTR**: Tiltmeter| 
| deviceCode| Indivdual name (code) of the Instrument in ONCs database | 
| deviceId | link to device page in ONC database |
| begin | start date of current instrument deployment |
| end | end date of current instrument deployment |
| lat | geographic latitude of deployed instrument | 
| lon | geographic longitude of deployed instrument |
| depth | depth (m) of deployed instrument|
| heading| azimuth of instrument relative to Geographic North |
| citation | ONC citation | 
| annotation| ONC annotation for instrument|
| annotation ID| |
| annotationSource| DMAS: ONC database entry |
| annotationSummary |"Data Quality"; "Commissioning": instrument data in validatioon phase after a deployment; "Compromised": instrument data quality affected; "Data Gap" ; ".start": ONC instrument driver was started; ".stop": ONC instrument driver was stopped  |
| createdBy | ONC internal user ID | 
| resourceId | ONC device ID to identify instrument on page |
| resourceName | ONC device Name | 
