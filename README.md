
Getting and Cleaning Data Course Project
========================================

Author: Amit Kumar Gupta

Introduction
------------
This repo is for my submission of project of coursera course "Getting and Cleaning Data" (getdata-008). The details of this project are as follows:


Project Description
--------------------
The goal of this project is to prepare tidy data that can be used for later analysis. Currently, analysing the data generated by wearable computing is more exciting in data science field. Provided data along with this project are collected from the accelerometers from the Samsung Galaxy S smartphone.

Data link:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 


Need to write R code (run_analysis.R) to perform following operation over the above data:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

About Code
-----------
run_analysis.R script consists of code that perform all the operation required in this project. But before running these operation it itself get data from link if not exists.

Steps to run this script:

- Clone this project to your computer.
- Set working directory to the "code" folder in this repository.
- Create "data" and "output" folder in main repository path.
- Then run the code by "source(run_analysis.R)".


