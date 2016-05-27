# bird_audio_classification

This repository contains work which scrapes the website Xeno-Canto for 'A' rating audio recordings of bird songs, performs audio analysis and feature extraction, and creates a supervised classifier with ~70% accuracy. The birds included in this project are:
* Dusky Antbird
* Great Antshrike
* Northern Cardinal
* Barred Antshrike
* American Robin
* House Finch

All of the work is done in three ipython notebooks - the data file contains the web scraping, the exploratory analysis contains the raw audio processing and feature creation, and the modeling notebook contains SVM and Random Forest models on those features.
