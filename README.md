In this notebook we will go through machine learning project with a goal of predicting the sale price of Bulldozers.

________________________________________________________________________________________________________________________________________________________________________________
1. Problem Definition How well can we predict future sales price of a bulldozer given characteristics and previous examples of bulldozers sales price?  
________________________________________________________________________________________________________________________________________________________________________________
2. Data Data is downloaded from Kaggle :https://www.kaggle.com/c/bluebook-for-bulldozers/data  

  3 main datasets: 
        -Train.csv is the training set, which contains data through the end of 2011.
        -Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition.            Your score on this set is used to create the public leaderboard.  
        -Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set            determines your final rank for the competition.  
       _______________________________________________________________________________________________________________________________________________________________________________
3. Evaluation The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.  For more on evaluation on this project, check : https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation 
________________________________________________________________________________________________________________________________________________________________________________

4. Features Kaggle has provided Data Dictionary that has details of all the features.
________________________________________________________________________________________________________________________________________________________________________________
