# coursera-getting-and-cleaning-data
##Getting and Cleaning Data: Course Project

###Introduction

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization. What follows first are my notes on the original data.

The dataset being used is: Human Activity Recognition Using Smartphones

###About the script and the neat dataset

I created a script called run_analysis.R which will merge the test and training sets together. Prerequisites for this script:

the UCI HAR Dataset must be extracted.
the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a neat data set containing the means of all the columns per test subject and per activity. This neat dataset will be written to a tab-delimited file called neat.txt, which can also be found in this repository.

###About the Code Book

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

The output of the 5th step is called neat.txt, and uploaded in the course project's form.