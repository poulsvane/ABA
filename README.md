# ABA
Repo for course project Advanced 
Disclaimer: Working with different file names may cause issues when running the scripts. Ensure your base files are named as stated below.

Running order is as follows:

1. Palo_alto_merging.ipynb --> merges and uniformly formats all data relevant to Palo Alto city
    The script has been tested with the following orginal files:
   New files from 2021-2023(+addition of new data with existing charger and a new fleet of flexpoint chargers)
   - CY21Q3 EV Charging Event Data.xlsx
   - CY23Q2 EV Charging Event Data.xlsx
   - CY21Q1 EV Charging Event Data.xlsx
   - CY23Q4 EV Charging Event Data.xlsx
   - CY21Q4 EV Charging Event Data.xlsx'
   - CY23Q1 EV Charging Event Data.xlsx
   - CY22Q4 EV Charging Event Data.xlsx
   - CY22Q3 EV Charging Event Data.xlsx
   - CY22Q1 EV Charging Event Data.xlsx
   - CY22Q2 EV Charging Event Data.xlsx
   - CY23Q3 EV Charging Event Data.xlsx
   - CY21Q2 EV Charging Event Data.xlsx'
  Older file from 2011-2021:
   - EVChargingStationUsage.csv

2. DUndee_merging.ipynb ---> merges all csv files from Dundee city and reformats data to Palo Alto dataset.
   The script has been tested with the following original files:
   - cpdata.csv
   - cp-data-dec-mar-2018.csv
   - cp-data-mar-may-2018.csv
   - cp-locations_enriched.csv
3. Graphs_map.ipynb --> plots the different charging ports on top of the shape file of a city(files shapes of palo alto and Dundee are yet to be added).

4. Exploratory.ipynb + project1.ipynb --> Data preproessing and Exploratory analysis 
