# Predictive-Analytics
A Predictive ML project to analyze and predict CO2 emissions from country-specific parameters such as population, energy use, land use, etc.

***

## 1. Project description

### Context and goals
A country's emissions of greenhouse gases like CO2 over a year could depend on certain country-specific aspects and the available data can be useful to analyze the development of climate change trends. 

### Dataset information

The dataset used is the Climate Change Data provided by the World Bank Group available at https://datacatalog.worldbank.org/dataset/climate-change-data, which includes parameters such as:
* country: the vast majority of countries worldwide
* year: ranging from 1990 to 2011
* emissions of greenhouse gases such as CO2, CH4, N2O, others
* population-specific parameters: population count, urban population, population growth, etc.
* country economic indicators: GDP, GNI, Foreign Direct Investment, etc.
* land-related parameters: cereal yield, agricultural land, Nationally terrestrial protected areas, etc.
* climate data: precipitations, national disasters, etc.
* energy use
* counts of certain types of medical personnel
* etc.

### Project structure

* Stage 1: Data cleaning and preparation 
* Stage 2: Data exploration and visualization 
* Stage 3: Predictive analysis with the Random Forest machine learning algorithm 

***

## 2. Summary of all project stages

### Stage 1: Data cleaning and preparation

* Data overview
* Data cleaning
    - dealing with missing values
    - renaming of features
    - removing empty columns and rows
* Data frame transformation
    - integration of the data into a suitable data frame format
* Removal of missing values
    - detection of missing values
    - removal of missing values by filtering the columns and rows, so that minimal amount of features and rows are lost
* Export the clean data frame to a file

### Stage 2: Data exploration and visualization

* Data overview
* Feature engineering
    - features overview
    - derivation of additional important features
    - removal of unnecessary features
* Visualization
* Conclusions

### Stage 3: Predictive analysis with the Random Forest machine learning algorithm

* Selection of dependent and independent variables
* Dataset splitting into training and test subsets
* Feature selection with recursive feature elimination and cross-validation
* Hyperparameter tuning of a random forest model with cross-validation
* Training and evaluation of the model with the best hyperparameters on the training data with cross-validation
* Validation of the model on the test subset (previously unseen data)
* Conclusions

***
