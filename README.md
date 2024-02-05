A cross-study analysis of wearable datasets and the generalizability of acute illness monitoring models
==============================

## Getting Started

### Installation
1. Clone this repo: `git clone https://github.com/chil-submission/wearable_generalizability`
2. cd into it:  `cd wearable_generalizability`

### Getting the data 
Data from publicly available sources are included in this repository and are stored under `/data`

#### COVID-RED
COVID-RED data was downloaded from: https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/FW9PO7


#### Corona-Datenspende 
Corona-Datenspende data was downloaded from: https://zenodo.org/records/8229284

#### Homekit2020
Data for the Homekit2020 study is available at https://www.synapse.org/#!Synapse:syn22803188/wiki/609492. You will need to be approved to access to the Homekit2020 dataset. Note that once you become a registered Synapse user it may take several business days for the Homekit2020 team to process your request. The example notebooks include the names of the files used in these analyses.

#### *All of Us*
Data from the *All of Us* study requires access to the *All of Us* researcher workbench. We inlcude aggregated data that can be used to reproduce figures in the analyses, however, data from individuals cannot be removed from the researcher workbench. We provide code that can be used in the researcher workbench to for calculating resting heart rate and performing multiple regresion. Researchers can gain access to *All of Us* at: https://www.researchallofus.org/register/

## Data means and multiple regression
A notebook demonstrating how the within-dataset and within-participant means were calculated are available in `time_series_and_multiple_regression.ipynb`

## All of Us data
A notebook demonstrating how we pulled minute level heart rate data and processed it into resting heart rate, along with the multiple regression and examples of minute of day means across demographics groups is shown in `all_of_us_analyses.ipynb`


## Tasks, models, training/testing, concept shift
A notebook with task definitions, models, dataset creation, training, and concept shift quantification are available in `model_generalizability.ipynb`
