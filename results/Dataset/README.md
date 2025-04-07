## Swiss data quality: augmenting CAMELS-CH with isotopes, water quality, agricultural and atmospheric chemistry data 
> April 2025

Authors: Thiago V. M. do Nascimento, Ursula Schönenberger, Sandra Pool, Rosi Siber, Martina Kauzlaric, Pascal Horton, Marvin Höge, Marius G. Floriancic, Maria Staudinger, Florian Storck, Päivi Rinta, Jan Seibert and Fabrizio Fenicia  

Contact: thiago.nascimento@eawag.ch

### Folders and content
- **catchment_aggregated_data/**: contains `three` subfolders. Each is organized containing `one` csv-file per catchment, `115` files in total. The files are organized by time series (rows) and attribute variables (columns).
	- **atmospheric_deposition/**:
		- CAMELS_CH_Chem_atm_{basin_id}.csv
	- **agricultural_data/**:
		- CAMELS_CH_Chem_crops{basin_id}.csv
	- **livestock_data/**:
		- CAMELS_CH_Chem_livestock_{basin_id}.csv

- **shapefiles:** Contains `three` subfolders. 
	- **camels_ch_del/**: contains two `shapefiles`. `One` shapefile includes the derived catchment boundaries associated with each gauge, and the other shapefile marks their location. Both files are referenced in in the Swiss coordinate system LV95 (sometimes also referred to as CH1903+), and were copied from the original CAMELS-CH. 
		- camels_ch_chem_catchment_boundaries.{cpg,dbf,prj,shp,shx}
	- **nawa_trend_del/**: provides the alternative delineation shapefile for the NAWA TREND catchments. 
		- camels_ch_chem_catchment_boundaries_nawat.{cpg,dbf,prj,shp,shx}
	- **nawa_fracht_del/**: like the anterior, but for NAWA FRACHT catchments.
		- camels_ch_chem_catchment_boundaries_nawaf.{cpg,dbf,prj,shp,shx}

- **gauges_medatada/**: contains `one` csv-file covering all the metadata associated with each of the `115` gauging stations.
	- camels_ch_chem_gauges_metadata.csv

- **stream_water_chemistry/**: contains `two` subfolders.  
	- **timeseries/**: contains `two` nested sub-sub folders for respectively daily and hourly time steps. The csv-files in both are organized by time series (rows) and attribute variables (columns), and each column represents one of the water quality variable. Both nested subfolders contain `86` files. 
		- **daily/**:
			- CAMELS_CH_Chem_daily_{basin_id}.csv
		- **hourly/**:
			- CAMELS_CH_Chem_hourly_{basin_id}.csv
	- **interval_samples/**: contains `three` nested sub-subfolders. 
		- **nawa_fracht/**: contains one csv-file per catchment covered (`24` files). The rows represent the dates, and each column represents one of the water quality variables.
			- CAMELS_CH_Chem_nawafracht_{basin_id}.csv
		- **nawa_trend/**: contains one csv-file per catchment covered (`76 files`) presents a similar structure as the anterior, but for NAWA TREND data.
			- CAMELS_CH_Chem_nawatrend_{basin_id}.csv

- **water_isotopes:** Contains `two` subfolders. Each is organized containing one csv-file per catchment with any isotopes data. The rows represent the dates, and each column represents either deuterium or oxygen-18 data. 
	- **isot/**: contains `nine` files in total. 
		- CAMELS_CH_Chem_isot_{basin_id}.csv
	- **ch_irp/**: contains `xx` files in total. 
		- CAMELS_CH_Chem_chirp_{basin_id}.csv

- **appendix/**: XX
	- XX.txt
	- XX.txt
	- XX.txt
	- XX.txt

## References
Currently CAMELS-CH-Chem covers `115` rivers catchments within Swiss territory. Please refer to the [CAMELS-CH-Chem preprint](XX), for a detailed description of the current dataset, including their respective variables units. For the codes used to derive the current dataset, users can refer to the [CAMELS-CH-Chem GitHub](XX). 

## How to cite
Medeiros do Nascimento, T. V., Schönenberger, U., Pool, S., Siber, R., Kauzlaric, M., Horton, P., Höge, M., Günter Floriancic, M., Staudinger, M., Storck, F., Rinta, P., Seibert, J., & Fenicia, F. (2025). Swiss data quality: augmenting CAMELS-CH with data on isotopes, water quality, agricultural data and atmospheric chemistry (0.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.14980027