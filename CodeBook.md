Hi,
this repository contains the projectCleaning.R file that takes as input data measurements from two sources and creates a easier table to read.
The repository also contains a CodeBook where I briefly describe the variables, the data and data transformation that I performed to clean up the data.

CodeBook.md
Basically I performed the following operations:
1. download the project.zip file that contains four files (activity_labels, features_info, features and README txt files)
and two folders test and train with measurements for 15 training and 15 testing sets
2. create a dataset named train and test that contain each 98 variables, two of them being related with the
identity of the subject and measurement session, and 96 variables containing data measurements
3. combine train and test into a bigger table named alldata using rbind
4. Extracts only the measurements on the mean and standard deviation for each measurement.
first load activity labels and features
5. extract all mean and standard deviation data from the alldata db
give all the columns their proper names into a table named 'mean.std.alldata'
5. finally, tidy mean.std.alldata

