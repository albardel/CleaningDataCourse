# Getting and Cleaning Data - Course Project

The R script run_analysis.R does:

1. Unzips the file 
2. Load the activity and feature info
3. Loads training and test datasets just the mean or standard deviation
4. Loads the activity and subject data for each dataset 
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists with the average of each variable for each activity and each subject.