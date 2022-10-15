# Predictive-Analytics
A Predictive ML project to analyze and predict CO2 emissions from country-specific parameters such as population, energy use, land use, etc.

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

## 3. Summary of all project stages
The highlights of all project stages are briefly introduces in the following:

### Stage 1: Data cleaning and preparation

* Global data overview
* Definition of the initial project goals
* Data cleaning
    - dealing with missing values
    - transformation of the columns into a numerical data type
    - renaming of features
    - removing empty columns and rows
* Data frame transformation
    - melting of the data for each variable
    - integration of the data into a suitable data frame format
* Removal of missing values
    - detection of missing values
    - removal of missing values by filtering the columns and rows, so that minimal amount of features and rows are lost
* Export the clean data frame to a file

### Stage 2: Data exploration and visualization

* Feature/column abbreviations and units
* Definition of the hypothesis to be tested
* Feature engineering
    - features overview
    - derivation of additional important features
    - removal of unnecessary features
* Prepare the visualization
* Create plots
	- a global look onto all relationships and detailed plots of chosen dependencies
    - correlation matrix heatmaps
    - scatterplots, histograms
    - detection of outliers
    - discussion of dependencies and trends
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

## 4. How to open

* Just download and view the HTML files (exported from and identical with the Jupyter Notebooks) in an internet browser. These are located in the */HTML* folder

or

* download the Jupyter Notebooks (.ipynb files in the */Jupyter_Notebooks* folder), open Jupyter Notebooks, browse to the downloaded files and open them.

***

