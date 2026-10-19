# Neighbourhood plan outputs

This repository summarises public data for a selected Parish Council and outputs the results as an excel file and html. 

## Notebooks
1.  clipping_analysis : Clips data listed in file_info_gdb.json to each Parish council and outputs as csv for each dataset
2.  data prep : Creates a rank comparing Parish councils for each dataset
3.  export_excel : Exports Excel document specific to selected Parish Council
4.  export_html : Exports html document specific to selected Parish Council

Run notebook 1 and 2 first to prepare data. 

## Json files
The json files contain information about the data to be imported. These need to be updated if the datasets have changed. 
1. file_info.json : Original json which takes complete datasets from original filepath. Not currently used but retained for future. 
2. file_info_gdb.json [default] : Updated json which takes data from neighbourhood plan geodatabase, where datasets have been clipped to Wilts. 