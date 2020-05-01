# FYP
The code for my Final-Year Data Science Project

Download the data files from the google drive link: https://drive.google.com/open?id=1liMBYLFb5U26h5AsQ8xk4XolH17FOhiD

These files are the testing and training datasets for the classifier.

Once you download the files from the Google Drive link above. Download the 2 jupyter notebook files here. What they do is outlined in the sections below:

### Data Preprocessing Notebook

This notebook reads the "chicago.txt" file or the "las-vegas.txt" text file based on your selection when you run the notebook. You are prompted to decide if you want to read the las-vegas dataset or the chicago dataset. The files are the original dataset I was given for this project. The script will read the file and parse the data into a data frame. The data frame is then written to a file .csv file.

### Experiment Notebook
The file named "Experiment" will read from the file .csv file created by the previous notebook. The script will execute the experiment comparing the Mean Review helpfulness and the three different recommendation methods (Classification, Date and Random). Similarly, it will execute the experiment to get the results of the percentage of helpful reviews recommended by the recommender for each recommender. The results of the tests are printed as standard output in the notebook. 




