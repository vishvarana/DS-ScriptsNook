## **DECISION TREE REGRESSOR**

**INTRODUCTION**

Decision Tree is one of the efficient and highly used alorithm in machine learning.

We can use decision tree algorithm in two types as:

Decision Tree Classifier (for classification tasks)

Decision Tree Regressor (for regression tasks)

**PURPOSE**

The main prupose is to give a clear understanding on what basically Decision Tree Fegressor algorithm is all about, its working, usage, libaries used, advantages, disadvantages etc.

**DATASET**

For the dataset being used in this project [click here](https://www.kaggle.com/benroshan/factors-affecting-campus-placement)



**BRIEF EXPLANATION**
- Let's understand Decision Tree regressor algorithm with help of the poject 'Campus Placement Analysis & Prediction' 

Campus placement or campus recruiting is a program conducted within universities or other educational institutions to provide jobs to students nearing completion of their studies. In this type of program, the educational institutions partner with corporations who wish to recruit from the student population.


Here, in this project we will analyze various features that affect campus placements and then perform prediction using decision tree regressor algorithm.



**WORKING CONDITIONS**
1.  Data preprocessing and exploration to understand what kind of data will we working on.

- Here we work on preprocessing and exploring the data to understand what kind of data we are working on, it's shape, memory usage, columns, data types etc.

![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr1.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr2.jpg)

- Also, we need to check for any null or missing values, if found then replace or remove them accordingly.
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr3.jpg)

2.  Data visualization to draw insights and get better underdstanding on different columns present in the dataset.

![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr4.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr5.jpg)

 Insights drawn through data visualization & analysis:
*   64.65% candidate are males and rest 35.35 % are females.
*   Lowest SSC percentage among all candidates is 40.89% and highest is 89.4%.
*   53.95 % of candidates gave their SSC exams under Central Board and rest 46.05% were from other board.
*  Lowest HSC percentage among all candidates is 37.0% and highest is 97.7%.
*  Only 39.07 % of candidates gave their HSC exams under Central Board and rest 60.93% were from other board.
*  Among all the candidates 52.56% candidates are from commmerce stream, 42.33% candidates are from Science stream and rest 5.12% candidates are from Arts Stream.
*  Lowest Degree percentage among all candidates is 50.0% and highest is 91.0%.
*  Degree title of 67.44% candidates is Commerce & Management, for 27.44% candidates is Science & Technology and rest 5.12% have other degree title.
*  65.58 % candidates have no work experience and rest 34.42% have valid work experience.
*  Lowest Employability test percentage ( conducted by college) percentage among all candidates is 50.0% and highest is 98.0%.
*  Among all the candidates 55.81% candidates have Marketing & Finance Post Graduation(MBA)- Specialization and rest 44.19 % have Marketing & HR Post Graduation(MBA)- Specialization.
* Among all the candidates 68.84% candidates have been successfully placed and rest 31.16 % have not been placed.




3. Data training using train-test-split method from sklearn to split the data into training and testing data and then  Model creation using decision tree regressor algorithm, where we import the model, then initialize it and fit training data into it and lastly perform predictions on the test data.

![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr6.jpg)
![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr7.jpg)



5.  Checking performance by error and accuracy check to find how efficient algorithm performed for this project.

![](https://github.com/ayushi424/DS-ScriptsNook/blob/main/Machine%20Learning/Algorithms/Decision%20Tree%20Regressor/Images/dtr8.jpg)




**USAGE**
- It is basically used for REGRESSION TASKS.
- Various sectors as engineering, healthcare, education etc.

**USE CASES**
- Regression tasks.
- Mainly used for complex projects.
- Used in projects where there are more number of features.

**LIBRARIES USED**
- pandas
- matplotlib
- seaborn
- sklearn
- numpy

**ADVANTAGES**
- Requires little data preparation. Other techniques often require data normalisation, dummy variables need to be created and blank values to be removed. Note however that this module does not support missing values.
- Easy understand & interpret
- Good for Regression tasks


**DISADVANTAGES**
- Decision-tree learners can create over-complex trees that do not generalise the data well. This is called overfitting. Mechanisms such as pruning, setting the minimum number of samples required at a leaf node or setting the maximum depth of the tree are necessary to avoid this problem.
- Relationship between features should be well understood or else it might give low performance efficiency.
- Can give low accuracy if features are not identified properly.
- Cannot be used for classification projects.

**APPLICATIONS**

- Used in different various regression tasks.
- Decision trees are used for handling non-linear data sets effectively.
- The decision tree tool is used in real life in many areas such as engineering, healthcare, civil planning, law, and business.
- Can help in improving business plan by providing fruitful insights and prediction analysis.

**CONCLUSION**

*  Decision Tree Regressor is one of the most efficient classification algorithm which is highly used for classification tasks.

*  For this project i.e. 'Campus Placement Analysis & Prediction'  , accuracy of decision tree regressor is 1.00 i.e. 100%

*  It Can help in improving business plan by providing fruitful insights and prediction analysis.


**Some beginner friendly REFERENCES**

- https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html
- https://scikit-learn.org/stable/auto_examples/tree/plot_tree_regression.html
- https://www.geeksforgeeks.org/python-decision-tree-regression-using-sklearn/
- https://towardsdatascience.com/machine-learning-basics-decision-tree-regression-1d73ea003fda


**Author**

[Ayushi Shrivastava](https://github.com/ayushi424)

**Happy Learning :)**
