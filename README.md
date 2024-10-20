# neural-network-challenge-2

*I am  tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so I am  also asked to predict the department that best fits each employee. These two columns will be predicted using a branched neural network. The steps used are divided into the following three parts:*


**Part 1: Preprocessing**
i. I imported the data and viewed the first five rows.
ii. I determined the number of unique values in each column.
iii. I created y_df with the attrition and department columns.
iv. I created a list of at least 10 column names to use as X data. 
v.I created X_df using my selected columns and showed the data types for X_df.
vi. I split the data into training and testing sets.
vii. I converted the X data to numeric data types. I then fitted any encoders to the training data, and then transformed both the training and testing data.
viii. I created a StandardScaler, fit the scaler to the training data, and then transformed both the training and testing data.
ix. I created a OneHotEncoder for the department column, then fitted the encoder to the training data and used it to transform both the training and testing data.
x. I created a OneHotEncoder for the attrition column, then fit the encoder to the training data and use it to transform both the training and testing data.


**Part 2: Create, Compile, and Train the Model**
i. I determined  the number of columns in the X training data.
ii. I created the input layer and at least two shared layers.
iii. I created a branch to predict the department target column, using one hidden layer and one output layer.
iv. I created a branch to predict the attrition target column, using one hidden layer and one output layer.
v. I created, compiled, and summarized the model.
vi. I then trained the model using the preprocessed data.
vii. I evaluated the model with the testing data.
viii. I then printed the accuracy for both department and attrition.


**Part 3: Summary**
**Briefly answer the following questions in the space provided:**

**Is accuracy the best metric to use on this data? Why or why not?**

**What activation functions did you choose for your output layers, and why?**

**Can you name a few ways that this model could be improved?**


