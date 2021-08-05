For ease of use all classifier cross validations have been turned into functions.

To run the cross validations I ran simply uncomment lines 515-518:

KNN cross validation: Line 515
DT cross validation: Line 516
NB cross validation: Line 517
RF cross validation: Line 518

To run your own cross validation go to the function and change the params 
dictionary and run the function.


To run my best final prediction uncomment  lines 523-538

To run your own final prediction create your own params dictionary options and change
the clf_type in the final_predict function call to the function you wish to run.

KNN - K Nearest Neighbors
DT - Decision Tree
NB - Naive Bayes
RF - Random Forest 
