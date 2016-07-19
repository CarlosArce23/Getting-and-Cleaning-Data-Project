# Getting-and-Cleaning-Data-Project
Instructions for project

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following.

    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement.
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive variable names.
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Tools used to produce this project

    This project is built by knirt package instllled on RStudio with RMD (R Markdown) format.

    The run_analysis.md and codebook.md files will be automatically produced by run_analysis.Rmd

Steps to produce this project

    Plsease see the details in run_analysis.md and codebook.md.

    Those files contain the instructions and steps with R code embedded to produce this project.

    The final tidy data is in tidydata.txt. It can be loaded by Data<-read.table("tidydata.txt", sep=" ", head=TRUE)

    The codebok is in codebook.md . It gives the descriptions of the variables in the data frame prouduced by this project.

Steps to reproduce this project

    Open Rstudio to open R Markdown file run_analysis.Rmd to build the Project , then run_analysis.md , codebook.md and tidydata.txt will be produced.

    Alterativley the R script run_analysis.r can be used to build the Project, but it only produces the final tidy dataset in tidydata.txt
