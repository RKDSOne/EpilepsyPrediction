# Predicting Epilepsy Diagnosis and Impact Using National Survey of Children's Health
### Harvard University Stat121a Introduction to Data Science Final Project 
### Jingyi Yu, Alexandra Ding, Ziao Lin

## Webpage: https://jy2014.github.io/EpilepsyPrediction/Home.html
<br>
</br>
## PLEASE READ THIS IF YOU ARE TRYING TO RUN THE CODE ##

Before attempting to run code, you need to **UNZIP THE DATA FILES!**

[We could not upload the CSV files without zipping because they are too large. ]
* NSCH_2007.zip
* NSCH_2007_droppedADP_codeLMN.csv.zip
* NSCH_2007_droppedADP_codeLMN_na.csv.zip
* imputed_PovertyLevel_RF.zip


### RELEVANT CODE FOR RUNNING THE MODELS:
* website_data_imputation.ipynb : performs missing data imputation; displays “Imputation” section of website
* website_diagnosis.ipynb : Runs classifiers to classify epilepsy status. Displays “Diagnosis” section of website
* website_QOL.ipynb: Runs classifiers to classify Quality of Life within epilepsy patients. Displays “QOL” section of website.

## List of files in this repository:
### Code:
* Website_data_source.ipynb: introduces data source, displays “Data Source” section of website
* website_data_imputation.ipynb : performs missing data imputation; displays “Imputation” section of website
* website_diagnosis.ipynb : Runs classifiers to classify epilepsy status. Displays “Diagnosis” section of website
* website_QOL.ipynb: Runs classifiers to classify Quality of Life within epilepsy patients. Displays “QOL” section of website.

### Datasets:
* NSCH_2007.zip: Raw (zipped) CSV downloaded from NSCH website. (https://www.cdc.gov/nchs/slaits/nsch.htm)
* NSCH_2007_droppedADP_codeLMN.csv.zip: NSCH 2007 with certain columns dropped, some indicators coded (intermediate step during data imputation)
* NSCH_2007_droppedADP_codeLMN_na.csv.zip: NSCH 2007 with certain columns dropped, some indicators coded as NaN values (intermediate step during data imputation)
* Categorical_Column_Names_wState.csv: List of categorical column names, including State. 
* variable_description.csv: CSV containing descriptions of variable names (scraped from PDF; code producing this CSV not included)
* Imputed_PovertyLevel_RF.zip: Dataset with imputed poverty level. This is the dataset we ultimately used in classification. 
* X_select39_epilepsy_for_QOL_non_encode.csv: 39 Selected predictors used in Quality of Life classifier, NOT one hot encoded
* X_select39_epilepsy_for_QOL_onehot.csv: 39 Selected predictors used in Quality of Life classifier, one hot encoded
* y_QOL_binary.csv: binary y values for Quality of life, with values 0 and 1 encoding good and bad.
* y_quality.txt: y values for Quality of Life, with values 0 to 3 encoding good to poor quality of life. 
