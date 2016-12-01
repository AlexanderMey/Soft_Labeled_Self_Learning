# Soft_Labeled_Self_Learning

The Zipfile Soft_Labeled_Self_Learning.zip contains two folders: Nearest Mean, Least Squares

In those folder you find the matlab codes NearestMeanSS.mat and LeastSquaresSS.mat
as well as the Datasets on that we tested the Method on. In each Dataset we saved all settings which we used in the test phase, as well as the expected results.

To reproduce my results:
1. Load a Dataset (or easier, load the files "All_Sets_LS" for the least squares and "All_Sets_NM" to load all Dataset at once)
2. Compile NearestMeansSS.mat or LeastSquaresSS.mat, depending on the datasets you loaded.

In "All_Sets_LS" and "All_Sets_NM" we saved the table that you expect to see as "Table1". The results for the single datasets are saved in "table1" and "table2" in each Dataset.

NOTE: Unfortunatly we did'nt save the random seeds of the runs used in the paper. So we can only get comparable results. Nevertheless, the results obtained should be exact to what is saved in "Table1".
