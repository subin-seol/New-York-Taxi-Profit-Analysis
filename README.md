# MAST30034 Project 1 README.md
- Name: Subin Seol
- Student ID: 1086852

**Research Goal:** My research goal is to maximise the profit of the yellow taxi drivers.

**Timeline:** The timeline for the research area is 2022 January, April, July and October.

Run the files in order:
1. `Preprocessing.ipynb`: This notebook details all preprocessing steps and outputs it to the `data/raw`, `data/landing`, and `data/curated` directory.
2. `Visualisation.ipynb`: This notebook is used to conduct visualisation of the curated data.
3. `Statistical Modelling.ipynb`: The notebook is used to run the model, Random Forest Classifier and Logistic Regression and evaluate them.

**Dataset:**
Taxi data is download through the given url, but taxi zone lookup, shapefiles and external data could not be download through urlretrieve. 
It is saved in the data folder, then moved to raw folder in the preprocessing notebook.

External Data: NOAA Weather Daily Summaries Data from 2022 January-October. (https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND)
