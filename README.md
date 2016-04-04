# GettingAndCleaningData
This is an assignment project for the course "Getting And Cleaning Data" Coursera course. Below are the details of each file in this repository.
#1. Readme.md
=============
Thid file describes the purpose of the repository and the details of each file which includes the description of variables, files used, R programming file and the final tidy file.

#2. Codebook.md
===============
This code book summarizes the identifiers, measurements and activity labels along with the resulting fields in tidy.txt

#3.run_analysis.R
=================
This file has the R programming code which does the following.
 - download the file if it does not exist in the current working directory
 - load the activity and feature information
 - loads the training and test data sets
          - Keeps only the columns/variables that contain "mean" and "standard deviation"
          - Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names.
- Merges the two data sets
- creates a second, independent tidy data set with the average of each variable for each activity and each subject.
- 
#4. tidy.txt
============
Final data set in the txt format created with write.table() using row.name=FALSE
