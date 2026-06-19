# Station files not generated yet

This service is station-based, therefore the following GBFS files must be generated before publication:

- `station_information.json`
- `station_status.json`

They are already referenced by `bikesharing_historic_operator/gbfs.json`, but are intentionally not included in this skeleton because they must be generated from PostGIS/QGIS station-point tables.

Expected station source for this service:
- system_id: `milano_2050_bikesharing_historic`
- station network: historic/current bike-sharing station map

Recommended `station_id` prefixes:
- `BIKEFUT_ST_` for bikesharing_future_intersections
- `BIKEHIST_ST_` for bikesharing_historic_operator
- `KICK_ST_` for kickscooter_sharing_intersections
- `MOPED_ST_` for moped_sharing_intersections
