# FYP
The code for my Final-Year Data Science Project

Download the data files from the google drive link: https://drive.google.com/open?id=1liMBYLFb5U26h5AsQ8xk4XolH17FOhiD

These files are the testing and training datasets for the classifier.

Once you download the files from the Google Drive link above. Download the 2 jupyter notebook files here. What they do is outlined in the sections below:

### Data Preprocessing Notebook

This notebook reads the "chicago.txt" file or the "las-vegas.txt" text file based on your selection when you run the notebook. You are prompted to decide if you want to read the las-vegas dataset or the chicago dataset. The files are the original dataset I was given for this project. The script will read the file and parse the data into a data frame. The data frame is then written to a file .csv file.

### Experiment Notebook
The file named "Experiment" will read from the file .csv file created by the previous notebook. The script will execute the experiment comparing the Mean Review helpfulness and the three different recommendation methods (Classification, Date and Random). Similarly, it will execute the experiment to get the results of the percentage of helpful reviews recommended by the recommender for each recommender. The results of the tests are printed as standard output in the notebook. 


### las-vegas_vals_df.csv

This file contains the helpfulness score for the every row of the data frame. I used this file to store this while I did the classification of the reviews. The random classifier does not accept float numbers for training so I had to use integers. I used this file however to hold the scores while I was using the standard 1 or 0 for classification.

### vals_df.csv

The same as above applies for this file. This file is the helpfulness scores of the Chicago dataset whereas the las-vegas_vals_df.csv is the helpfulness scores for the Las-Vegas dataset.

### reviews_file_chicago.txt and reviews_file_las-vegas.txt 

This is a list of all the reviews as strings. I used the reviews a few times to do different calculations so I found it easier to just write them to a file than parsing the large chicago.txt and las-vegas.txt files for the reviews as strings of text every time I wanted to do some small computations.

