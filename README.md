# Getting and Cleaning Data (Project on Coursera.org)
Repository for Coursera's course on Getting and Cleaning Data

Instructions:
- The file run_analysis.R is a script written in R language.
- In order to run the script, please download and the dataset from the link "a" given at the end.
- You will first need to set the working directory (line 17) to the location where you have extracted the file.
- The code has been tested on R (64-bit) version 3.1.2. But should run on any version above 3.0.1.
- The script requires two packages "dplyr" and "tidyr" to be installed for execution.
- At the end of the script, a file should be written (if write permissions are set) to the working directory named "results.txt"

Objectives:
run_analysis.R script does the following:
1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set.

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

a. https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
