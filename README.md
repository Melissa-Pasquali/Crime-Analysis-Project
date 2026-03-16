UK Police Crime Data Analysis 


1 Project Overview

This project analyses UK police street crime data using Python. The aim of the project is to clean, preprocess, and explore the dataset to identify patterns and trends in crime across different locations, crime types, and police forces.

The project uses Python and Jupyter Notebooks to perform data preprocessing and exploratory data analysis (EDA). The workflow includes loading the raw datasets, cleaning and preparing the data for analysis, and producing visualisations to better understand crime patterns.

2 Folder Structure

Crime Analysis Project
│
├── data
│   ├── raw               
│   └── processed          
├── notebooks
│   ├── data_preprocessing.ipynb   
│   └── eda_analysis.ipynb         
│
├── README.md              
└── .gitignore             

3 Data Source

The dataset used in this project is UK Police Street Crime Data, which contains publicly available crime data recorded by police forces in England and Wales.

The dataset can be downloaded from:

https://data.police.uk/data/

Download the dates January 2024 - January 2025 from the police forces: Nottinghamshire Police, Leicestershire Police, Surrey Police, City of London Police, and Gloucestershire Constabulary. 

Due to the large size of the dataset, the raw data files are not included in this GitHub repository.

Then place the downloaded files inside the "raw" folder found inside the "data" folder

4 How to run the scripts

1. Clone the repository link and open with Jupyter Notebook
2. Download the dataset from link above, and place in in the files data/raw
3. Run the data_preprocessing.ipynb notebook (found inside notebook folder). The notebook cleans the raw data and will export a new clean dataframe which will be saved in data/processed/clean_street_analysis.csv
4. Run the eda_analysis.ipynb notebook that will create the data visualistation regarding crime trends and patterns

5 Tools and libraries used

Python, Pandas, Numpy, Matplotlib, Seaborn, Jupyter notebook, glob, os

6 Extra documents included in submission

In the submission folder for the project, you will find the documentation for the preprocessing, including a flowchart and Trello board link, a statement of work, and a final report

