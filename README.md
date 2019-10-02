# Logistic-Regression-Model

# Data Preprocessing:

1. Importing the required Libraries: Numpy is a Library which contains mathematical functions.
                                     Pandas is the library used to import and manage the data sets.

2. Importing the Data Set: Data sets are generally available in .csv format.


3. Handling the Missing Data: The data we get is rarely homogeneous. Data can be missing due to various reasons and needs
                              to be handled so that it does not reduce the performance of our machine learning model. We can
                              replace the missing data by the mean or the mean of the entire column. 
                              We use imputer class of sklearn.preprocessing for this task.




4. Encoding Categorial Data: Categorial data are variables that contain label values rather than numerical values. 
                             Example values such as Yes and No cannot be used in mathematical equations of the model
                             so we need to encode these variables into numbers. 
                             To achieve this we import LabelEncoder class from sklearn.preprocessing library.

5. Splitting the dataset into test set and training set: We make two partitions of data set one for training the model called the    training set and the other for testing the performance of the trained model called the test set. The split is generally 80/20.
We import train_test_split() method of sklearn.

6. Feature scaling: Most of the machine learning algorithms use the Euclidean distance between two data points in their computation,
                    features highly varying in magnitudes, units and range pose problems.
                    High magnitudes features will weigh more in the distance calculations than features with low magnitudes.
                    Done by Feature standardization or Z-score normalization. StandardScalar of sklearn.preprocessing is imported.
                    
                    
                    
                    
---------------------------------------------------------------------------





