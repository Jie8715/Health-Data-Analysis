# Health-Data-Analysis
Analyzed the health data from IMS intelligence to classify Patient-Level
Created a KNN classifier model to predict the pdc-80-flflag(Proportion of days covered, =1 if pdc ≥ 0.80; =0 otherwise) continuous features “total-los”, “num-op”, “num-er”, “numndc”, “pre-total-cost”, and “pre-CCI”.
Used 10-fold cross-validation to determine which value of K produces the most accurate result from the range k = 31 to 101 with a step size of 2.
Observed the best K is 33, and the lowest validation error is 0.39, which is smaller than the test error without cross-validation (0.41) 
