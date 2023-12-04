For this homework I worked with Paula, Rayta and Sarah but at the end i discussed the data processing with Miles. So the four of us actually spend a good time on how to clean up the data with all those -999.000 values, Paula and i deleted 10 features with most -999.000 values and cleaned up some rows to retain as much data as possible, while Sarah decided to get rid of all 11 columns. While Miles did it differently.

 This homework was based on a dataset from kaggle, Higgs Boson search, where we had to classify the signal from background using Random Forest and Gradient Boosting trees method, there were two tasks using classifiers and regressors and then check the scores. But from the results i got it seemed pretty clear that regressors just don't work well with this type of data set. Later we did find 4 important highest features using features importance and found best parameters and run the random forest classifier again and plotted the ROC curve and find area under the curve to see how well the classifiers work to classify the labels as the sognal and background.

 The easy part of the homework was to interpret the confusion matrices and visualising and understanding the data.

 The hard part was to actually decide on how to clean up the data to get rid of maximum -999.000 values while retaining most of the features and data points.

The new thing i learned was how to get data from kaggle and upload it on drive, then work with sklearn it's always easy and fun to see how long tentative lines of functions we write can be just replacd by sklearn classesa and inbuilt functions. Also how the Random Forest and Gradient Boosting trees work, though i am not entirely sure, I still need to learn and practice more to get complete command on the decision trees.
