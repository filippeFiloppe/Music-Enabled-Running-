# Music-Enabled-Running
### A git repository for ADS Minor Project - Music Enabled Running - at Fontys University of Applied Sciences 
![Naamloos_ontwerp](https://user-images.githubusercontent.com/56435256/149590624-5f5041dd-30ee-4a3c-ab78-4a4f17dc9d84.png)
# Goal
The goal of this project is to find if there is a correlation between running performance and music. 

# Data
The datasets used during the music project consist of information gathered by two runners. The information was gathered with the help of footpods and the phones of the runners, which they took with them during each running session. The datasets contain data about the footpods, the music listened to by the runners, the music features, like energy and artist, phone locations, phone activity and the running sessions. During the project Olaf also delivered new data about gathered running sessions from the two runners, which was used to further help the progression of  the project. The first two datasets created for the project consisted of the information from the footpods, sessions and music data. This was done because it was not yet necessary to use the phone data for that part of the project.

The two cleaned datasets for the first and second test runner were made with the help of multiple CSV files that were given by Olaf. These CSV files, as explained earlier contain data about the footpods, music and phone data. The dataset for the first test runner consists of 29 columns and 59457 rows and mostly contains object, float64, int64 and bool data types. The dataset for the second test runner consists of 20 columns and 6381 rows and also contains the same data types as the dataset for the first test runner.

After creating the cleaned datasets during the exploratory data analysis, new data was received to work with by Olaf. This dataset was already cleaned and contained multiple columns about the foot pod data. The newly received datasets contained new columns for the footpod features, which had their symmetry angle calculated. Like the previous datasets used during the EDA, these datasets also contained  objects, float64, int 64 and bool data types. The dataset containing information about the first test runner contained 245,724 rows and 95 columns in total. The dataset containing information about the second test runner contained 17,840 rows and 95 columns in total.
# Repository Structure and Description of Files 
## Documentation
All the written reports (Business Proposal, 2-pager etc..) and used research articles.
## Data Cleaning & Preparation 
### KNN - Means - Final - All Sessions.ipynb 
Use of the KNN - means method as a way to filter bad data records. By removing outliers and smaller clusters from the main cluster. 
### TestPerson2 - Data Preparation
## Exploratory Data Analysis (EDA)
Exploring the data with the use of statistical analysis and correaltion matrices for both Test Runner I and II.
### TestPerson1 - EDA Music Enabled Running (FR Corp).ipynb
### TestPerson2 - EDA Music Enabled Running (FR Corp).ipynb
## Experiments 
Use of different Machine Learning methods and more in order to find and prove a correlation between Running and Music.
### Music - SOM [testing].ipynb 

