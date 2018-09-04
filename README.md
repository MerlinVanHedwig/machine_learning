# machine_learning
[Consistency_Functions4.rmd](https://github.com/GregMurray30/machine_learning/blob/master/Consistency_Functions4.Rmd) measures the variance of different algorithms using biased sampling (separated by loan lending agency) of loan approval data. This is accomplished by training a model for every lender and testing those models with the test data for all lender's except for the lender whose data trained the present model. The standard deviation of the estimated probabilities for each observation is the consistency score for that algorithm. This could be used to determine the accuracy-consistency tradeoff when regulators are assessing lenders.

[Similarity-Scoring-V2.rmd](https://github.com/GregMurray30/machine_learning/blob/master/Similarity_Scoring-V2.Rmd) determines the similarity of one lending agency to each other lending agency in the data set. This is accomplished by training a model for lender and testing those models with the agency of interest's data. The difference between the estimated probability of approval for the lender of interest and the other lender's estimated probability for the same observation determines the similarity score. This could be used as a means of assessing candidates for mergers and acquisitions.
