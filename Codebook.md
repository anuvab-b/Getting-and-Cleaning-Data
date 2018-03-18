# Code Book
The code book describes the data used in this project and the steps undertaken to create the resulting tidy dataset.

## Description for files that were used from the ZIP Folder

* features.txt': List of all 561 features.

* activity_labels.txt': Links the class labels with their activity name.

* train/X_train.txt': Training set.

* train/y_train.txt': Training labels.

* test/X_test.txt': Test set.

* test/y_test.txt': Test labels.

# Steps used to get final tidy dataset:
*The textfiles were read using the read.table() function.
*Column headers were added.
*The dataframes were combined.
*All columns were removed that did not contain the exact string "mean()" or "std()".
*Created a second, independent tidy data set with the mean of each variable for each activity and each subject.
