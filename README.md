The course project for "Getting and Cleaning Data" requires reading in the "Human Activity Recognition Using Smartphones" data set, performing an analysis on the data set, and outputting a tidy data set.

Here are the steps that must be performed before running the R script:

Download the zip file from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.
Unzip the file.
Move ALL of the following files to the SAME DIRECTORY as the R script:
features.txt
subject_train.txt
subject_test.txt
X_train.txt
X_test.txt
y_train.txt
y_test.txt

Run the R script (run_analysis.R). Note that it requires the reshape2 package, which can be downloaded from CRAN.

The output of the R script is a tidy data set called tidy.csv.

You can read more information about the data and the analysis in the code book.