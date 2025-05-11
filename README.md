![image](https://github.com/user-attachments/assets/87deab56-c3be-4881-9df3-22b6fe6b729a)![image](https://github.com/user-attachments/assets/1a91f585-4c07-4848-9724-a0f3c302f5b1)# ML_project1

1. Facebook Live Sellers Dataset

The source is UCI Machine Learning Repository and data format stored as CSV- (comma separated values) file. 
Number of instances and attributes : 7,050 rows, each representing a unique Facebook status post from Thai fashion and cosmetics retail sellers, with 14 attributes 
Attribute overview: 
   - status_id: Unique identifier for each status post.
   - status_published: Date and time when the status post was published.
   - status_type: Nature of the status post (e.g., video, photo, status, link).
   - num_reactions: Number of reactions (e.g., likes, loves, wow, haha, sad, angry) received on       the status post.
   - num_comments: Number of comments received on the status post.
   - num_shares: Number of shares received on the status post.
   - Additional numerical and categorical attributes related to engagement metrics and status post features.
 Missing Values: The dataset may contain missing values, which need to be handled during data preprocessing.

Concepts used: 

Data Preprocessing – 
This process mainly involves cleaning and transforming raw data into a format that models can understand and learn from effectively.

Data Cleaning involves: 
Handle Missing Values:
Removing rows or columns and filling them with mean, median, or mode
Remove Duplicates:
Drop identical rows
Fix Errors or Outliers

Data Transformation involves:
Normalisation or Scaling: This involves bringing all numerical features to the same scale using - 
Min-Max Scaling
Standardisation (Z-score)
Encoding Categorical Data: Process of converting non-numeric values to numbers - 
One-Hot Encoding
Label Encoding

Feature Selection
This step involves selecting important features and creating new features from existing ones

Data Splitting-
Divide the dataset into:
Training set
Testing set
Validation set

2. K Means: 
K-Means is an unsupervised machine learning algorithm used to group similar data points into K clusters based on feature similarity.
You need to choose the number of clusters, denoted as k. Then, k centroids are randomly initialised in the feature space. Each data point in the dataset is then assigned to the nearest centroid. Once all points are assigned, the centroids are recalculated by taking the mean position of all points within each cluster. This process of assigning points and updating centroids is repeated iteratively until the centroids no longer moves significantly, indicating that the algorithm has converged.

3. Mean Squared Error (MSE) – 

MSE is a method used to measure the average squared difference between actual and predicted values to evaluate clustering performance. 

4. Correlation – 
 
Correlation measures the relationship between two variables, how one variable changes in response to another.

For strength: 0–0.3: Weak, 0.3–0.7: Moderate, 0.7–1.0: Strong 
For direction: Positive values = As one metric increases, the other tends to increase, Negative values = As one metric increases, the other tends to decrease. 
0 means no correlation, +1 means perfect positive correlation, -1 means perfect negative correlation 

5. Elbow Method –
 Elbow Method is a technique used to find the optimal number of clusters (k) in KMeans clustering. This method avoids overfitting and underfitting. 


////////////////////////////////////////////////////


2. Sales Prediction dataset 

The dataset provided contains information about the advertising expenditures of a company on various platforms (TV, Radio, newspapers) and the corresponding sales of a product. The dataset includes:

1. TV: This column represents the amount of money spent on advertising the product on television. TV advertising is a traditional and widely used medium for reaching a broad audience.
2. Radio: This column indicates the advertising expenditure on radio. Radio advertising is known for its ability to target specific demographics and local audiences.
3. Newspaper: This column shows the advertising cost spent on newspaper advertising. Newspaper advertising is often used for targeting specific geographic regions or demographics.
4. Sales: This column represents the number of units sold corresponding to the advertising expenditures on TV, Radio, and newspapers.

Concepts used:

Data Preprocessing – 
This process involves cleaning and transforming raw data into a format models can understand and learn from effectively.

Data Cleaning involves: 
Handle Missing Values:
Removing rows or columns, filling them with mean, median or mode
Remove Duplicates:
Drop identical rows
Fix Errors or Outliers

Data Transformation involves:
Normalisation or Scaling: This involves bringing all numerical features to the same scale using -
Min-Max Scaling
Standardisation (Z-score)
Encoding Categorical Data: Process of converting non-numeric values to numbers - 
One-Hot Encoding
Label Encoding

Feature Selection
This involves selecting important features and creating new features from existing ones

Data Splitting
Divide the dataset into:
Training set
Testing set
Validation set

2. K Means: 

 K-Means is an unsupervised machine learning algorithm used to group similar data points into K clusters based on feature similarity.
You need to choose the number of clusters, denoted as k. Then, k centroids are randomly initialised in the feature space. Each data point in the dataset is then assigned to the nearest centroid. Once all points are assigned, the centroids are recalculated by taking the mean position of all points within each cluster. This process of assigning points and updating centroids is repeated iteratively until the centroids no longer moves significantly, indicating that the algorithm has converged.

3. Mean Squared Error (MSE) – 

MSE is a method used to measure the average squared difference between actual and predicted values to evaluate clustering performance. 

4. Correlation – 
 
Correlation measures the relationship between two variables, how one variable changes in response to another.

For strength: 0–0.3: Weak, 0.3–0.7: Moderate, 0.7–1.0: Strong 
For direction: Positive values = As one metric increases, the other tends to increase,
Negative values = As one metric increases, the other tends to decrease. 
0 means no correlation, +1 means perfect positive correlation, -1 means perfect negative correlation

5. Linear Regression

Linear Regression is a supervised learning algorithm used to predict a continuous output based on one or more input features. It is used to find the best-fitting straight line ( regression line) through the data that minimises the error between the predicted and actual values. It is commonly evaluated using Mean Squared Error or R2 score








