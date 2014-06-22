cleanse_proj
============

This Readme.md explains the basics / logic of how the data is cleansed / decorated and modified into the tidy data

1. First step includes downloading the zip file and unzipping all of the necessary files into the working directory

2. Once the input files are avialble in the owrking directory, setwd() and check to make sure that is valid via getwd() command

3.  Read the features into a Data frame called features (Column V2)
4.  Read the Activity labels into a Data frame called activity_lables
5.  From the features data frame, indetify the column indices with names containing mean or std by using the grep command..  Store these indices into an int vector called indices_of_means_and_stds
6.  Change the working directory to train
7. Read the X_train data and name the columns using features column V2
8.  Read the Y_train data and name the column "labels"
9.  Read the Subject_train data and name the column "subjects"
10.  Change the subdirectiory to test and repeat steps 7-9 for all of the test data as well.
11.  Now you have read in all of the test data and train data and provided them with column names.
12.  
