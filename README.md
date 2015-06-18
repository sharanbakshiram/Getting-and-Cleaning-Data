# Getting-and-Cleaning-Data
getting_and_cleansing_data
Unzip the source into a folder on your local drive, say C:\Users\E050705\Desktop\r_training\getdata-projectfiles-UCI HAR Dataset

Put run_analysis.R into C:\Users\E050705\Desktop\r_training\getdata-projectfiles-UCI HAR Dataset

Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
