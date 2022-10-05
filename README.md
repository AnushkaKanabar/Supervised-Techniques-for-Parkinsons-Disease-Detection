Step 1: Load the dataset
Step 2: Eye-ball raw data to get a feel of the data in terms of number of records, structure of the file, number of attributes, types of attributes and a general idea of likely challenges in the dataset. Mention a few comments in this regard
We find that the 24 columns have following datatypes:
•	name- Qualitative Datatype (Object). It has completely unique values, hence has no predictive power.
•	MDVP: Fo(Hz)- Continuous Numerical Datatype (float64)
•	MDVP: Fhi(Hz)- Continuous Numerical Datatype (float64)
•	MDVP: Flo (Hz)- Continuous Numerical Datatype (float64)
•	MDVP: Jitter (%)- Continuous Numerical Datatype (float64)
•	MDVP: Jitter (Abs)- Continuous Numerical Datatype (float64)
•	MDVP: RAP- Continuous Numerical Datatype (float64)
•	MDVP: PPQ- Continuous Numerical Datatype (float64)
•	Jitter: DDP- Continuous Numerical Datatype (float64)
•	MDVP: Shimmer- Continuous Numerical Datatype (float64)
•	MDVP: Shimmer(dB)- Continuous Numerical Datatype (float64)
•	Shimmer: APQ3- Continuous Numerical Datatype (float64)
•	Shimmer: APQ5- Continuous Numerical Datatype (float64)
•	MDVP: APQ- Continuous Numerical Datatype (float64)
•	Shimmer: DDA - Continuous Numerical Datatype (float64)
•	NHR - Continuous Numerical Datatype (float64)
•	HNR - Continuous Numerical Datatype (float64)
•	status - Discrete Numerical Datatype (int64)
•	RPDE- Continuous Numerical Datatype (float64)
•	DFA - Continuous Numerical Datatype (float64)
•	spread1 - Continuous Numerical Datatype (float64)
•	spread2- Continuous Numerical Datatype (float64)
•	D2 - Continuous Numerical Datatype (float64)
•	PPE - Continuous Numerical Datatype (float64)
Likely Challenges in Data:
1) We checked that there is no null value in data.
2) The Continuous Numeric variables are on different scales- 3-digit numbers, Decimals, also Negative numbers. We will have to do appropriate scaling of data to bring all values in a uniform scale.
3) Name col has completely primary values. Since it has no predictive power, we can drop this column.
Step 3: Using univariate & bivariate analysis to check the individual attributes for their basic statistics such as central values, spread, tails, relationships between variables etc. Mention your observations
Pair plot for Bivariate Analysis
Correlation between all features
Step 4: Split the dataset into training and test set in the ratio of 70:30
Step 5: Prepare the data for training - Scale the data, if necessary, get rid of missing values
Step 6: Train at least 3 standard classification algorithms - Logistic Regression, Naive Bayes’, SVM, KNN etc, and note down their accuracies on the test data
Step 7: Train a meta-classifier and note the accuracy on test data
Step 8: Train at least one standard Ensemble model - Random Forest, Bagging, Boosting etc, and note the accuracy
Step 9: Compare all the models (minimum 5) and pick the best one among them
