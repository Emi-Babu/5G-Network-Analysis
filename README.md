# Ten most Suitable counties for Mobile Broadband Technology in the U.S

The purpouse of this project is to analyze in which US county areas it would be worth investing in Mobile Internet Technology.

## Requierements

### Install Census and US
pip install census
pip install us

### Installing jupyter-gmaps with pip

- Make sure that you have enabled ipywidgets widgets extensions:
$ jupyter nbextension enable --py --sys-prefix widgetsnbextension
You can then install gmaps with:

- Then tell Jupyter to load the extension with:
$ jupyter nbextension enable --py --sys-prefix gmaps

In order to run the following Jupyter Notebooks you need to add your keys for each service:
- 1_final_attempt\1_census - api_key for census
- 1_final_attempt\3_coordinates - gkey for google API geocode - Warning: Looping through 3,219 rows takes about 15 minutes
- 1_final_attempt\4_heatmap - - gkey for gmaps

## Contents of the Folders
### 0_First_attempt
Contains the first attempt to get information from different sources and its cleanning process
### 1_final_attempt
- Contains the retrival of information, cleaning process and resulting graphs
- Every folder depends on results obtained by the previous one to run properly
