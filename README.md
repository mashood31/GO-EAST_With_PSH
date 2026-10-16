# Required large data files

The following files are required but are not stored in GitHub because they exceed GitHub's file-size limit:

- Data/Gen/east2019_rawGensAvailableCap.csv
- Data/Gen/east2020_rawGensAvailableCap.csv
- Data/Gen/east2021_rawGensAvailableCap.csv
- Data/Gen/east2022_rawGensAvailableCap.csv
- Data/Raw_Data/PJM.xlsx

Please download them from: https://drive.google.com/file/d/1jTEbcc3enfroMV-z6oUM6UAiba9sPMYQ/view?usp=sharing

After downloading, place them under:

GO-EAST/Data/Gen/

GO-EAST/Data/Raw_Data/

Copy PSH_gen.csv and PSH_mat.csv to the Data/data_allocation folder after running reduced_network_data_allocation.py. 
To change the attributes of the PSH, make changes to the PSH_gen.csv file. 
The cycle time configurations used for this study are listed in PSH_Cycle_Time_Configurations.csv file. 
To change the PSH node, make changes to the PSH_mat.csv file.
