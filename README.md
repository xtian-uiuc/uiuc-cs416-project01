# UIUC CS 416 Data Visualization - Project 01 & Project 02

This repository contains Jupyter Notebooks which are being used inside of the project for data cleaning. 

Due to various limitation of Tableau Public, multiple data cleaning methods have been used in order to limit the Tableau data source number (Tableau Public limits the max number of records can operate <= 15,000,000) of records and accelerate the performance (avoid operations take longer then 1 minute).

For Project 02, since it's a webpage-based project, additional data clean up has been performed in order to maintain data file size within a limitation in order to avoid long downloading time.

## 1. Prerequisite 

Please download following public datasets and put them into designated folders.

### 1.1 COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University

URL: [https://github.com/CSSEGISandData/COVID-19](https://github.com/CSSEGISandData/COVID-19)

Folder: `./data/jh_covid19`

### 1.2 World Development Indicators

URL: [https://datatopics.worldbank.org/world-development-indicators/](https://datatopics.worldbank.org/world-development-indicators/)

Folder: `./data/world_bank`

### 1.3 WHO COVID-19 Vaccination Data

URL: [https://covid19.who.int/data](https://covid19.who.int/data)

Folder: `./data/who`

## 2. Dependencies

Please make sure install the following Python libraries before execute notebooks:

- numpy (>= 1.20.2)
- pandas (>= 1.2.5)

## 3. Running Order

Please follow the list to run nodebooks in order:

- `01_data_processing.ipynb`
- `02_calculate_delta.ipynb`
- `03_join_tables.ipynb`
- `04_data_processing_part2.ipynb`
- `05_additional_data.ipynb`
- `06_country_data.ipynb`

Use file `covid_data_v4.csv` in the output folder as the data source in Tableau for Project 01. Or:

Copy files `country_data_v2.csv`, `covid_data_v5.csv`, and `wdi_data_v1.csv` in the output folder to the `./data/` folder in Project 02 to use them as data source. 


