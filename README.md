Getting and Cleaning Data Course Project
============
Introduction
------------
This repository contains the first Project of the Getting and Cleaning Data, the third course of the Data Science specialization

Raw Data
------------
The features are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file.
The same holds for the training set.

Script and the tidy dataset
------------
The script called run_analysis.R will merge the test and training sets together. It will utilize for this script:

the UCI HAR Dataset must be extracted and the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

Code Book
------------
See CodeBook.md
