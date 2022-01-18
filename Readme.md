
Getting and Cleaning Data - Coursera Project
________________________________________________________________________________

* This is the peer review project for the Coursera course: Getting and Cleaning Data.
* The R script, `run_analysis.R` will execute the following steps:


1. Download the original zip dataset from a given URL (if it does not already exist in the working directory).
2. Read the training and testing datasets and merge them into x(measurements), y(activity) and subject.
3a. Load the data(x) feature, activity info and extract columns named 'mean'(`-mean`) and 'standard'(`-std`).
3b. Modify column names to be descriptive. (`-mean` to `Mean`, `-std` to `Std`, and remove symbols like `-`, `(`, `)`)
4a. Extract data by selected columns (from step 3), and merge x, y(activity) and subject data.
4b. Replace y(activity) column to it's name by refering activity label (loaded step 3).
5. Generate a tidy dataset that consists of the mean of each variable for each subject and each activity.
