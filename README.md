# Feature-Engineering-Outliers
## There are many ways to detect outliers
1) Z-Score
2) IQR
# Z-Score
One of the most commonly used tools in determining outliers is the Z-score. Z-score is just the number of standard deviations away from the mean that a certain data point is.
In your future data science life, Z-scores are gonna be a really useful way to think about how usual or how unusual a certain data point is. And that’s going to be really valuable once we start making inferences based on our data.

# IQR
Each dataset can be divided into quartiles. The first quartile point indicates that 25% of the data points are below that value whereas second quartile is considered as median point of the dataset. The inter quartile method finds the outliers on numerical datasets by following the procedure below
Find the first quartile, Q1.
Find the third quartile, Q3.
Calculate the IQR. IQR= Q3-Q1.
Define the normal data range with lower limit as Q1–1.5*IQR and upper limit as Q3+1.5*IQR.
Any data point outside this range is considered as outlier and should be removed for further analysis.
