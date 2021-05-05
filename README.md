## NCHS-surveydata-sleep-prediction

we are going to use NHANES dataset from NHANES package. This is survey data collected by the US National Center for Health Statistics (NCHS) which has conducted a series of health and nutrition surveys since the early 1960s. Since 1999 approximately 5,000 individuals of all ages are interviewed in their homes every year and complete the health examination component of the survey. The health examination is conducted in a mobile examination centre (MEC). To learn mode about this dataset you can take a look at this link.

## Approach and Steps

1. Use the variables SleepHrsNight and Depressed in the NHANES data to build a classification tree to predict SleepTrouble.
2. Summarize the classification tree in part (a). Include the answer to the following questions in your summary: How the splits on the variables were selected; which nodes are terminal; and how a new observation would be predicted by this classifciation tree.
3. What proportion of subjects in the NHANES data have trouble sleeping?
4. Separate the NHANES data set uniformly at random into 75% training and 25% testing sets. Use the training set to build the classication tree using the variables in part (a). Use the test set to calculate the confusion matrix for two cut-points: 0.5 and proportion of subjects in the NHANES data that have trouble sleeping (use the value from part (c)). For each cut-point used the confusion matrix to calculate the following values: True positive rate (sensitivity), True negative rate (specificity), False positive rate, False negative rate, Accuracy. Which values change and which values are the same for diffierent cut-points? Explain.
5. Create an ROC curve of the classification tree that you developed in (b). Suggest a cutpoint to use for classifying a person as having sleep trouble. In one to two sentences, using complete English, explain why you chose this cutpoint. 
6. Use the training and testing sets that you created in part 4 to create a classification tree to predict SleepTrouble, but use all the variables in the NHANES training data. Plot the ROC curves for the Tree Classifier you developed in part (d) and the Tree Classifier you developed using all the variables on a single plot. What is the accuracy of the Tree Classifier using all the variables? Interpret the plot. Can you say which Tree Classifier has higher accuracy?
