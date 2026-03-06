# Predicting-Republican-Democrat-Tweets

The aim of this project is to build a deep learning model to predict whether a tweet has been written by a republicain or a democrat. 

### Files and Folders in the Git (more details at the beggining of the files): 
- **historical-users-filtered.json** : the json file containing information on the users who wrote the tweets of the dataset used. I did not upload the rest of the dataset as it was very big, but it is the folder data of the github : https://github.com/alexlitel/congresstweets. Many thanks to alexlitel for creating this dataset !
- **Data_collecting_and_cleaning.ipynb** : the code used to merge the data of Alexlittle into a single parquet file and clean them to made them usable to train the model. I created 2 files with this code : "congress_tweets_dataset.parquet" and "congress_tweets_dataset_cleaned.parquet". I used the second one with my models. The files are too big to be uploaded on github, so I uploaded the second one (the only one I used) here : https://drive.google.com/file/d/18A7Scl1Ms0QNaBXB2o15Q7a21iZjQWKU/view?usp=drive_link
- **Data_analysis.ipynb** : a code to analyse the distribution of the data and plot histograms 
- **Baseline_model.ipynb** : an SVM model which acts as a baseline model for the project 
- **Main_model.ipynb** : the deep learning model
- **Pictures** : pictures of some outputs of the code used in the report
- **Models** : the models tested so far
