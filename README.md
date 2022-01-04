# Scientific Software Licensing
Investigating the impact of software licensing on the dissemination of peer-reviewed scientific research\\


## ScientificSoftwareLicensing.rmd 
Has four sections:\
### 1) Get Data

It downloads publication data from articles in PLOS (Public Library of Science, the first peer-reviewed Open-Science journal) that contain FOSS software license names (bsd, mit, ecl, Apache, mpl, lgpl, gpl) and as many randomly selected articles for the control group. \
It outputs the file "PLOSdataXXXXXX.csv". (XXXXXX = file version)\

### 2) Clean Data

It extracts and reorders data in "PLOSdataXXXXXX.csv".\
It outputs the file "PLOScleanDataXXXXXX.csv". (uploaded in the repo)\

### 3) Analyze Data

It runs some analyses on the clean dataset, e.g. summaries, tables, linear regression, chi-squared\

### 4) Draw Data

drawData.R draws histograms, box plots, mosaic plots\\


## PLOScleanDataXXXXXX.csv

PLOScleanDataXXXXXX.csv (XXXXXX = the version number i.e. the download date) is the clean dataset on which analyses are performed.\
For the reviewers' ease, this file can be used to run the analysis in step 3 and draw the data in step 4.
