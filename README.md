# Python--Order_Scheduling_Optimization
This is a small Python script based on Pandas and Numpy library. I have created this as a collaboration for an ongoing research project that predicts the number of orders from each destination and thus, schedules the pickup. The result of this data is used to solve practical transportation based optimation problem.

The input is an Excel file with orders from each destination and source. Output is Jaccardian Coefficent/Similarity index.
The Jaccard similarity index (sometimes called the Jaccard similarity coefficient) compares members for two sets to see which members are shared and which are distinct. It’s a measure of similarity for the two sets of data, with a range from 0% to 100%. The higher the percentage, the more similar the two populations. Although it’s easy to interpret, it is extremely sensitive to small samples sizes and may give erroneous results, especially with very small samples or data sets with missing observations.[https://www.statisticshowto.com/jaccard-index/]

The formula to find the Index is:

  Jaccard Index = (the number in both sets) / (the number in either set) * 100

The same formula in notation is:

  J(X,Y) = |X∩Y| / |X∪Y|
