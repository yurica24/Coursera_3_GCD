Getting and Cleaning Data Course Project by Yuri Castro
=======================================================

This is a CodeBook or so for Course Project on Coursera for the Johns
Hopkins Getting and Cleaning Data course.

The original data source can be found on
<a href="http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones" class="uri">http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones</a>

### What about this data:

*Human Activity Recognition database built from the recordings of 30
subjects performing activities of daily living (ADL) while carrying a
waist-mounted smartphone with embedded inertial sensors.*

Steps
-----

1.  First get the local path with getwd()
2.  Load the labels on activityLabels to do the merge
3.  featuresWanted add Standard deviation and mean
4.  replace measurements with features wanted
5.  work with the train data, doing the calculation
6.  Same with test data
7.  Use rbind function combines vector, matrix or data frame by rows.
8.  Create a new file with fwrite
