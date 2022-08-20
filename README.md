# MAST30034 Project 1 README.md
- Name: Ziyi Li
- Student ID: 1073869

## README example
This is an example `README.md` for students to use. **Please change this to your requirements**.

**Research Goal:** My research goal is earning analysis for yellow taxi drivers

**Timeline:** The timeline for the research area is 2020.1 - 2022.3

To run the pipeline, please visit the `notebooks` directory and run the files in order:


1. `data_initialising.ipynb`: This downloads the raw data into the `data/raw` directory and save some geopanda data. (Please note that in this notebook, the zip file of taxi zones cannot be downloaded and unziped automatically, the download link is in the appropriate mark down grid before using, apologize for that)
2. `data_preprocessing.ipynb`: This notebook details many preprocessing steps and outputs it to the `data/curated` directory.
3. `feature_engineering.ipynb`: This notebook applys the feature engineering and merged data with the external dataset.(Please note that the external data set also couldn't download directly, I have put the csv file in to the file 'data/' just in case you do not want to grab the data your self.)
3. `data_analysing.ipynb`: This notebook is used to conduct analysis on the curated data.
4. `model_analysis.ipynb`: This is used to run the model and also analysing and discussing the model.
