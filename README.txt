1) The code first creates a directory for the file if it doesn't exist. It then downloads the zipped files and unzips them. 

2) Next, the program reads in three pairs of files that will later be combined together. The files are Y_test, Y_train, subject_train, subject_test, X_test and X_train.

3) The program then combines each of the pairs of files. Activity test and train are merged; as are subject test and train and features test and train.

4) The program sets the variable names in order to then merge the three merged data sets together into a single data set, Data.

5) The program then Extracts the measurements on the mean and standard deviation for each measurement.

6) The code uses descriptive activity names to name the activities in the data set. 

7) The code appropriately labels the data set with descriptive variable names.

8) Finally, the code creates a second,independent tidy data set and ouput it

