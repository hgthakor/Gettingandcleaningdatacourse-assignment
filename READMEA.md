Data Analysis of UCI HAR Dataset for the Getting and Cleaning Data Course Assignment submission
For the assignment submission this repo is created. As first step the purpose of this repo is discussed. This repo contains the R scripts that can be used for analysis of the given data set of  UCI HAR Dataset and convert it into a tidy data set as per the instructions.
This is done for the submission of assignment as the course project for the "Getting and Cleaning Data" course in Coursera which is part of the "Data Science" specialization track.
The Requirements as per instructions:
Create a R script that does the following
•	Merges the training and the test sets to create one data set.
•	Extracts only the measurements on the mean and standard deviation for each measurement.
•	Uses descriptive activity names to name the activities in the data set
•	Appropriately labels the data set with descriptive variable names.
•	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
R code
The R code that is used for analysis is given in the Run_analysis.R file.
Source the file in R using the following command and it will automatically download the dataset, perform the transformation, tidy the data and save it in the file tidy_data.txt.

source("Run_analysis.R")
The tidy data set can be loaded back into R using the following command
tidy_data <- read.table("tidy_data.txt")

Data CodeBook
The codebook  for the given data is available in this repo which describes the variables, the data, the transformations that are done and the cleanup that was performed on the data.

