In the data directory we include the following:
- reviews/reviews.csv: contains all the reviews text with the high level (preclasses)
and low level (subclasses) categories as obtained through regular expressions
- reviews/golden_set.csv: contains all the reviews manually labeled with low level
classes (class1, class2, class3, class4 and class5) columns
- RQ_1/URR_Survey.csv contains the responses of the Research Question 1 Survey
- RQ_1/high and RQ_1/low: contains the results of the manual evaluation for each high and low
level category. For each review the PREDICTED_category column indicates the prediction of the 
URR classifier and CORRECT contains the results of the evaluators (1 if they consider the 
prediction correct, 0 if they consider wrong and 2 if they are unsure).
- RQ_2/linking_data: contains the oracle for linking reviews to source code
- RQ_2/linking_data-and-results.xls contains the results of the linking 
