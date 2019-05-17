# breast-cancer-classifier

Dataset - https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Prognostic%29 (Breast Cancer Wisconsin (Prognostic) Data Set)

I've added detailed comments in the notebook to showcase the reasoning.

Results:

1. 98.25% accuracy on blind test set with (96.1%,99.5%) range from cross validation set.
2. 97.67% precision as well as recall on Linear SVM.



Further Analysis:

1. Customise the loss function to penalise the False negative (real M but predicted B) cases compared to False postiive cases becasue false negatives can be life threatening in real setting while false postives are just an annoyance relaively speaking.
2. Deep dive into the cases that we predict wrong. This will help me understand what went wrong with the model and how (if possible) we can fix this problem.
3. Add Fuzziness in the system to direct difficult cases to human expert so that we avoid life-threstening situations.
4. Try Gaussian mixture models and probabilistic graphical models.
5. Visualise both categories using t-sne plots.
6. Deep dive into dimensionality reduction to choose just the optimal number of dimensions to save computaitonal power.
7. Compare the performance of neural networks, gradient boosting and knn on this data. 
8. Compare the model peformance by removing the correlated features and adding one feature(most important) at a time.
9. Effect of data size on the model performance.

