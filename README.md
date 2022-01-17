# Music-Enabled-Running
### A git repository for ADS Minor Project - Music Enabled Running - at Fontys University of Applied Sciences 
![Naamloos_ontwerp](https://user-images.githubusercontent.com/56435256/149590624-5f5041dd-30ee-4a3c-ab78-4a4f17dc9d84.png)
# Goal
The goal of this project is to find if there is a correlation between running performance and music. 

# Data
The data is gathered by two recreational runners, wearing RunScribe Pro footpods and dedicated waist-worn iPhone 11 smartphones, which they took with them during their usual outdoor running sessions. The datasets contain stride and foot placement data from the footpods, the music listened to by the runners, the music features, like energy and artist as supplied by the Spotify API, phone location, phone activity, and general session information. During the project, additional new data was supplied, which was used to further progress the project. The first two datasets consisted of the footpod, sessions and music data. The phone data was not yet for that part of the project. 

The two cleaned datasets for the first and second test runner were made with the help of multiple supplied CSV files. The dataset for the first test runner consists of 29 columns and 59,457 rows and mostly contains object, float64, int64 and bool data types. The dataset for the second test runner consists of 20 columns and only 6,381 rows. 

After creating the cleaned datasets during the exploratory data analysis, new data was supplied. This dataset was already cleaned and contained additional columns about the foot pod data, such as computed symmetry angles. The new dataset for the first test runner contained 245,724 rows and 95 columns. The dataset for the second test runner contained 17,840 rows.
# Repository Structure and Description of Files 
## Documentation
All the written reports (Business Proposal, 2-pager etc..) and used research articles.
## Data Cleaning & Preparation 
### KNN - Means - Final - All Sessions
Use of the KNN - means method as a way to filter bad data records. By removing outliers and smaller clusters from the main cluster. 
### TestPerson2 - Data Preparation
### Correlation Analysis
Analysis in order to prove a correletion between the symetry movement and music features. Data sets used subject_1_pod_symmetry_per_step.csv , subject_2_pod_symmetry_per_step.csv  
## Exploratory Data Analysis (EDA)
Exploring the data with the use of statistical analysis and correaltion matrices for both Test Runner I and II.
### TestPerson1 - EDA Music Enabled Running (FR Corp).ipynb
### TestPerson2 - EDA Music Enabled Running (FR Corp).ipynb
### Outliers cleaning 
Use of several outlier techqniques and a box plot, in order to remove outliers and clean the data. Data sets used subject_1_pod_symmetry_per_step.csv, subject_2_pod_symmetry_per_step.csv  
## Experiments & Modeling
Use of different Machine Learning methods and more in order to find and prove a correlation between Running and Music.
### XGB - Music
Model that can try to predict impact symmetry using music features. Also used to prove a correlation between impact_sa and music features with the use of RSME & r2.Data sets used subject_1_pod_symmetry_per_step.csv, subject_2_pod_symmetry_per_step.csv   
### Modeling Experiments - Music Version & Modeling Experiments - Pods Version
Experimenting with SOM (Self Organizing Maps) in order to prove a correlation between running data and music data. Data sets used sub_1_pod_symmetry_per_song.csv,
music_features_tracks.csv, combined_v3.csv
## General 
Conference Poster Graphics - the overall summary of the project in graphics.  

