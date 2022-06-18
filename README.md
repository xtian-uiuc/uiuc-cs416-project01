# UIUC CS 416 Data Visualization - Project 01

This repository contains Jupyter Notebooks which are being used inside of the project for data cleaning. 

Due to various limitation of Tableau Public, multiple data cleaning methods have been used in order to limit the Tableau data source number (Tableau Public limits the max number of records can operate <= 15,000,000) of records and accelerate the performance (avoid operations take longer then 1 minute).

## 1. Prerequisite 

Please download following public datasets and put them into designated folders.

### 1.1 COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University

URL: [https://github.com/CSSEGISandData/COVID-19](https://github.com/CSSEGISandData/COVID-19)

Folder: `./data/jh_covid19`

### 1.2 World Development Indicators

URL: [https://datatopics.worldbank.org/world-development-indicators/](https://datatopics.worldbank.org/world-development-indicators/)

Folder: `./data/world_bank`

## 2. Dependencies

Please make sure install the following Python libraries before execute notebooks:

- numpy (>= 1.20.2)
- pandas (>= 1.2.5)

## 3. Running Order

Please follow the list to run nodebooks in order:

- `01_data_processing.ipynb`
- `02_calculate_delta.ipynb`
- `03_join_tables.ipynb`

Use file `covid_data_v4.csv` in the output folder as the data source in Tableau.


