# Assignment questions for Lab 4

# Q1:-
The dataset contains missing values, categorical variables requiring encoding, and numerical features with significantly different scales. 

# Q2:-
No missing values were found in any column. Therefore, no missing value handling strategy was applied. The dataset is complete and ready.

# Q3:-
The IQR method was applied to all numerical features to detect outliers. Outliers were mainly observed in Are and Prices due to the presence of very large or high-priced houses.

# Q4:-
Min-Max normalization scaled numerical features to a 0-1 range, ensuring all variables have comparable magnitudes. Z-score normalization standardized the features to have a mean of 0 and a standard deviation of 1.

# Q5:-
PCA was applied after standardizing the numerical features. The first principal component captured the largest proportion variance in the dataset. The variance indicated that most of the dataset's information could be retained using only a few principal components.
