# Predictive-Equipment-Failures
Predict downhole equipment failures using sensor data [ Datathon ]

#File descriptions
equip_failures_training_set.csv - The training set.

equip_failures_test_set.csv - The test set.

sample_submission.csv - A sample submission file in the correct format. Please note that your submission MUST be a csv file with a header row and then 16001 rows that have filled in id and target values for each row.

Data fields
id - This is a column that is a row identifier for each row in the training and test data sets.

target - This column is only in the training data set to provide a label for downhole equipment failures. In the test data set, the target 

column is not to provided you. You must predict the target values with a predictive model of your creation.


There are two types of sensor columns in these data sets :

measure columns - These columns are a single measurement for the sensor.

histogram bin columns - These columns are set of 10 columns that are different bins of a sensor that show its distribution over time.
