Stores Clustering
The DUNGAREE dataset shows the number of pairs of four various types of dungarees sold at stores over a specific time period. 
Each row represents an individual store. 
There are six columns in the data set. 
One column is the store identification number, and the remaining columns has the number of pairs of each type of jeans sold.

Name	Model Role	Data Type	Description
STOREID	Ident	Numeric	Identification number of the store
FASHION	Input	Numeric	Number of pairs of fashion jeans sold at the store
LEISURE	Input	Numeric	Number of pairs of leisure jeans sold at the store
STRETCH	Input	Numeric	Number of pairs of stretch jeans sold at the store
ORIGINAL	Input	Numeric	Number of pairs of original jeans sold at the store
SALESTOT	Ignore	Numeric	Total number of pairs of jeans sold (the sum of FASHION, LEISURE, STRETCH, and ORIGINAL)


1.	Examine the input variables.  Answer the following with explanations.
a.	Are there any unusual data values?
b.	Are there missing values that should be replaced?
c.	Check the data for outliers.
2.	Run k-means clustering using a seed = 42, and choose k = 10. 
3.	Based on the results, does k=10 clusters seem appropriate?  Why or why not?
4.	Use the wssplot() command to create a plot of the within cluster sum of squares. Based on this plot, what are your observations with respect to the number of clusters chosen?
5.	In the next run, specify a maximum of six clusters, and run the k-Means clustering algorithm again.  
6.	Using the output, interpret the characteristics of each cluster as it relates to types of jeans sold at stores.  Describe these clusters, and their similarities and differences in words.
7.	Which clustering approach provides greater differentiation between clusters and interpretability? 
