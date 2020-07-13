# Sparkify - Music App Log Data


## Table of Contents

1. [Installation](#installation)
2. [Project Description](#description)
3. [Files in the repository](#files)
4. [Results](#results)
5. [Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Alongside standard python libraries like pandas, numpy, matplotlib and datetime, other libraries such as Pyspark SQL and Pyspark ML are needed to execute the program. The code was written using Python 3. 


## Project Description <a name="description"></a>

The objective of this project is to predict churn customers using their log data on the music app. The data contains fields like:

* artist 
* auth
* firstName
* gender 
* itemInSession
* lastName
* length
* level 
* location
* method
* page
* registration:
* sessionId
* song
* status
* ts
* userAgent
* userId

Using above fileds the churn can be defined and features can be extracted to build a machine learning model. 
The project is build only on a subset (128MB) of the full data (12GB). 


## Files in the repository <a name="files"></a>

The following are the files available in this repository:

* `Sparkify.ipynb` - a Jupyter notebook containing initial data exploration, feature extraction and modelling to predict churn users. 
* `Sparkify.html`- html document exported from Jupyter notebook above.


## Results <a name="results"></a>

In the project few machine learning methods are tested. All models are evaluated based on F1 Score and time component. The winning model is determined based on test accuracy. More information and the winning model can be found here:
https://medium.com/@aleksandrarojek/churn-analysis-on-music-app-data-473371484f7d


## Acknowledgements <a name="licensing"></a>

Thank you to Udacity for providing the project and the dataset.
