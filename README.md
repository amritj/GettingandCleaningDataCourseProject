This repository contains the files for the course project for the Getting and Cleaning Data Coursera course. The primary file is the run_analysis.R which is the R script performing the following steps:

Downloads the dataset if it does not already exist in the working directory
Unzips the downloaded dataset
Reads the data from the activity, subject and features files into the designated variables
Using the variables defined above, merges the training and the test data sets for subjects, activities and features
Names the variables in the merged datasets
Merges the three data types (subjects, activities and features) by columns to get a master combined data sets
Calculates the mean and standard deviation of variables for which these exist
Labels the rows in the data with descriptive activity names such as Standing, walking, etc.
Creates another independent tidy data set and outputs it
The end result is shown in the file tidy.txt
