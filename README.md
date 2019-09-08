# PennApps2019Hack
DeepODIN: Using Deep Learning to predict opioid overdose fatalities

## Goal
Using data from the PA state Overdose Information Network Data (ODIN) dataset in conjunction with publicly available US Census information, this project attepts to predict factors indicating risk of fatal overdoses without considering basic demographic and socioeconomic factors.


## CensusData_2012-17.csv
Collects data from the American FactFinder website to compile county-level information about PA through the years 2012-2017.  Data features include Public/Private Health Insurance enrollment, school enrollment across several age groups, and proportion of the county population which has disabilities of any kind.

## Exploration.ipynb
Initial collection of ODIN data and exploartory data analysis to understand important factors in predicting death by overdose.

## Overdose_info_update.json
Collected data set combinging information from US Census and PA ODIN databases

## Test_Dataset_training.ipynb
Jupyter notebook showing dataset preparation and preprocessing, fully-connected neural network architectures, and training procedure.

Our best results show an accuracy of ~70% for predict overdose fatalities.
