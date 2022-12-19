# Titanic-Survival-Prediction
A task on kaggle focusing on basics of machine learning.

The main goal is binary classification if the passagner survived or no. 

We are provided with a simple data.

Competition:

https://www.kaggle.com/competitions/titanic

# What's inside the code?
The link to the solution is here:

https://www.kaggle.com/code/szymonsmg/titanicprediction

1. Cleaning data and converting from categorical to numerical values.
2. Splitting into train and test data.
3. Deleting inconsistant fields.
4. Training few models, picking the best one.
5. Testing.

# Models trained:
1. Logistic Regression.
2. Decision Trees.
3. Random Forest.
4. Native Bayes.
5. K-Nearest Neighbors.

# Descriptions of algorithms:
1. Logistic regression:

Logistic regression is a statistical analysis method to predict a binary outcome, (yes or no) according to observations on dataset. 

Variables must be independent from one another! There could be a situation when we spend some amount of time considering if variables are correlated or no.
Raw data should be independent and unrepeated. Logistic regression also requires a significant sample size. This can be as small as 10 examples of each variable in a model. 
 A special trick is required to represent categories with more than two classes. For example, you might transform one category with three age ranges into three separate variables, where each specifies whether an individual is in that age range or not.

Logistic regression vs. Linear regression
In logistic regression, the outcome, or dependent variable, has only two possible values. However, in linear regression, the outcome is continuous, which means that it can have any one of an infinite number of possible values.
Logistic regression is used when the response variable is categorical, such as yes/no, true/false and pass/fail. Linear regression is used when the response variable is continuous, such as hours, height and weight.

For example if there are 100 people in the distribution and 30 of them are coded 1, then the mean of the distribution is .30, which is the proportion of 1s. The mean of the distribution is also the probability of drawing a person labeled as 1 at random from the distribution. That is, if we grab a person at random from our sample of 100 that I just described, the probability that the person will be a 1 is .30. Therefore, proportion and probability of 1 are the same in such cases. The mean of a binary distribution so coded is denoted as P, the proportion of 1s. The proportion of zeros is (1-P), which is sometimes denoted as Q. The variance of such a distribution is PQ, and the standard deviation is Sqrt(PQ). (http://faculty.cas.usf.edu/mbrannick/regression/Logistic.html)

Suppose we want to predict whether someone is male or female (DV, M=1, F=0) using height in inches (IV). We could plot the relations between the two variables as we customarily do in regression. The plot might look something like this:

