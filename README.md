Getting and Cleaning Data - Course Project
==========================================
## Introduction
This is my submission for Peer Graded Assignment: Getting and Cleaning Data Course Project. This repository hosts the R code and
documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera.

## Data Source
Data for this project was obtain from the Coursera assignment instructions. Data represent data collected from the accelerometers from the
Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: [Human Activity Recognition Using
Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files

The code takes for granted all the data is present in the same folder, un-compressed and without names altered.

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing
the file. The run_analysis.R can be run as long as setting your working directory to the UCI HAR Dataset folder. Dplyr or plyr package was
required to run this script.

Analysis will read all the test data and train data merge them into one data set. Each variables were names accordingly based on the
features listed in the features.txt file.

Using the combined data set, independent tidy data set with the average of each variable for each activity and each subject was created
and written into averages_data.txt file.

The output of the 5th step, `averages_data.txt` is uploaded in the course project's form.
