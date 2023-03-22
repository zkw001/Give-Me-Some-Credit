# Give-Me-Some-Credit
The goal of this HW is to be familiar with the basic classifiers PML Ch 3.
For this HW, we will use Give Me Some Credit on Kaggle. You may download from Kaggle link or CMS.
Load cs-training.csv into a Pandas dataframe.
Fill-in the missing values (nan) with the column means. (Use pd.fillna() or See Ch 4 of PML)
Select the 2 most important features using LogisticRegression with L1 penalty. (Adjust C until you see 2 features)
Using the 2 selected features, apply LR / SVM / decision tree. Try your own hyperparameters (C, gamma, tree depth, etc) to maximize the prediction accuracy. (Just try several values. You don't need to show your answer is the maximum.)
Visualize your classifiers using the plot_decision_regions function from PML Ch. 3
Put your result in YOUR_GITHUB_ID/Give-Me-Some-Credit/code/Classifiers.ipynb
