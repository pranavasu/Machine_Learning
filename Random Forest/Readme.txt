This is the project to create Random forest Ensemble technique from decision trees algorithm
Here I have created 30 Decision Trees base models and bootstrapping has been done on both column and rows. While bootstrapping for individual base models 60% of the rows and atleast 24% of the columns(i.e atleast 3 out of 13) have been choosen.
At first performance metrics like MSE and OOB score is calculated by running the algorithm once then Random Forest algorithm has been run 35 times to get enough number of MSE and OOB score samples.
Finally Confidence Interval has been calculated for both MSE and OOB and concluded that observed MSE and OOB values lies within 95% confidence interval.
