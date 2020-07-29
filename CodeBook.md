We have transformed the original data by following these steps:

1. We have merged the training and the test sets to create one data set (named 'Oneset').
2. We have extracted only the measurements on the mean and standard deviation for each measurement.
3. We renamed the activities in the data set with descriptive names, and labelled the data with it.
4. We have created a second, independent tidy data set with the average of each variable for each activity and each subject.

Variables description:

x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in
