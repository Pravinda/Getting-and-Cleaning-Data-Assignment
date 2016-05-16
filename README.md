##Coursera Course Assignment : Getting and Cleaning Data
This repository contains R code for DATA SCIENCE's Assigment "Getting and Cleaning Data" in which data is collected , work with, and clean a data set to prepare prepare tidy data.

---------------------------------------------------------------------------------


The following points explain the process on how the tidy_data.txt file is obtained by running run_analysis() function :

* If Dependency packages "data.table" and "reshape2" are not installed then install it.
* Downloads data from link https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unzip.
* Load activity labels file
* Load data column names 
* Extract only the measurements on the mean and standard deviation for each measurement.
* Load and then process X_test & y_test data text files
* Extract only the measurements on the mean and standard deviation for each measurement.
* Load activity labels
* Bind data
* Load and process X_train & y_train data.
* Extract only the measurements on the mean and standard deviation for each measurement.
* Load activity data
* Bind the data together
* Merge test and train data
* Apply mean function to dataset using dcast function
* create independent tidy data set "tidydata.txt"

---------------------------------------------------------------------------------   
   
> Assignment Submission Files


`README.md`

`CodeBook.md`

`run_analysis.R`

`tidy_data.txt`   