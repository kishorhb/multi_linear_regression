# multi_linear_regression
Multiple Linear Regression is an extension of Simple Linear regression where the model depends on more than 1 independent variable for the prediction results. Our equation for the 

multiple linear regressors looks as follows:

y = b0 + b1 *x1 + b2 * x2 + .... + bn * xn

Here, y is dependent variable and x1, x2,..,xn are our independent variables that are used for predicting the value of y. Values such as b0,b1,…bn act as constants.


Steps to Build a Multiple Linear Regression Model

There are 5 steps we need to perform before building the model. These steps are explained below:

Step 1: Identify variables

Before you start building your model it is important that you understand the dependent and independent variables as these are the prime attributes that affect your results.

Without understanding the dependent variables, the model you build would be a waste, hence make sure you spend enough time to identify the variables correctly.

Step 2: Check the Cavet/Assumptions

It is very important to note that there are 5 assumptions to make for multiple linear regression. These are as follows:

Linearity
Homoscedasticity
Multivariate normality
Independence of errors
Lack of Multicollinearity

Step 3: Creating dummy variables

Suppose, I want to check the relation between dependent and independent variables, dummy variables come into picture.
We create dummy variables where there are categorical variables. For this, we will create a column with 0s and 1s. For example, we have names of few states and our dataset has just 2 namely New York and California. We will represent New York as 1 and California as 0. This 0 and 1 are our dummy variables.

Step 4: Avoiding the dummy variable trap

After you create the dummy variables, it is necessary to ensure that you do not reach into the scenario of a dummy trap.

The phenomenon where one or more variables in linear regression predict another is often referred to as multicollinearity. As a result of this, there may be scenarios where our model may fail to differentiate the effects of the dummy variables D1 and D2. This situation is a dummy variable trap.

The solution to this problem could be by omitting one of the dummy variables. In the above example of New York and California, instead of having 2 columns namely New York and California, we could denote it just as 0 and 1.

Step 5: Finally, building the model

We have many independent variables inputted to determine an output variable. But one policy we need to keep in mind, is garbage in- garbage out. This means that we must input only the necessary variables into the model and not all of them. Inputting all the variables may lead to error prone models.

Also, keep in mind, when you build a model it is necessary you present the model to the users. It is relatively difficult to explain too many variables.

There are 5 methods you can follow while building models. There are stepwise regression techniques:

All-in
Backward Elimination
Forward Selection
Bidirectional Elimination
Scope comparison
