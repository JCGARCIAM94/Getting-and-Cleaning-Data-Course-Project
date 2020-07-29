# Getting-and-Cleaning-Data-Course-Project
Repository for the final task of 'Getting and cleaning data' course.


In the R script 'run_analysis.R' we have made the following tasks:

First, we have read the data for the correspondent URL and unzipped the Data sets.
Then, we have merged the training and the test sets to create one data set.

After that, we have read feature vector and activity labels and trainings and testing tables.

The next step was assingning column names. Then, we finally merged the data in the data frame 'Oneset'.

The second task was extracting only the measurements on the mean and standard deviation for each measurement.
The result was stored in the set 'setForMeanAndStd'

Third task was fixing descriptive activity names to name the activities in the data set

Finally, we computed a second tidy data set. 
