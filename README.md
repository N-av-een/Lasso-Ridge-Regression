# Lasso-Ridge-Regression
# Introduction
In this blog, we will see the techniques used to overcome overfitting for a lasso regression model. Regularization is one of the methods widely used to make your model more generalized.

# What is Lasso Regression?
Lasso regression is a regularization technique. It is used over regression methods for a more accurate prediction. This model uses shrinkage. Shrinkage is where data values are shrunk towards a central point as the mean. The lasso procedure encourages simple, sparse models (i.e. models with fewer parameters). This particular type of regression is well-suited for models showing high levels of multicollinearity or when you want to automate certain parts of model selection, like variable selection/parameter elimination.

Lasso Regression uses L1 regularization technique (will be discussed later in this article). It is used when we have more features because it automatically performs feature selection.

# Lasso Meaning
The word “LASSO” stands for Least Absolute Shrinkage and Selection Operator. It is a statistical formula for the regularisation of data models and feature selection.

# Regularization
Regularization is an important concept that is used to avoid overfitting of the data, especially when the trained and test data are much varying.

Regularization is implemented by adding a “penalty” term to the best fit derived from the trained data, to achieve a lesser variance with the tested data and also restricts the influence of predictor variables over the output variable by compressing their coefficients.

In regularization, what we do is normally we keep the same number of features but reduce the magnitude of the coefficients. We can reduce the magnitude of the coefficients by using different types of regression techniques which uses regularization to overcome this problem. So, let us discuss them. Before we move further, you can also upskill with the help of online courses on Linear Regression in Python and enhance your skills.

Lasso Regularization Techniques
There are two main regularization techniques, namely Ridge Regression and Lasso Regression. They both differ in the way they assign a penalty to the coefficients. In this blog, we will try to understand more about Lasso Regularization technique.

L1 Regularization
If a regression model uses the L1 Regularization technique, then it is called Lasso Regression. If it used the L2 regularization technique, it’s called Ridge Regression. We will study more about these in the later sections.

L1 regularization adds a penalty that is equal to the absolute value of the magnitude of the coefficient. This regularization type can result in sparse models with few coefficients. Some coefficients might become zero and get eliminated from the model. Larger penalties result in coefficient values that are closer to zero (ideal for producing simpler models). On the other hand, L2 regularization does not result in any elimination of sparse models or coefficients. Thus, Lasso Regression is easier to interpret as compared to the Ridge. While there are ample resources available online to help you understand the subject, there’s nothing quite like a certificate. Check out Great Learning’s PG program in Artificial Intelligence to upskill in the domain. This course will help you learn from a top-ranking global school to build job-ready AIML skills. This 12-month program offers a hands-on learning experience with top faculty and mentors. On completion, you will receive a Certificate from The University of Texas at Austin, and Great Lakes Executive Learning.

Also Read: Python Tutorial for Beginners

Mathematical equation of Lasso Regression
Residual Sum of Squares + λ * (Sum of the absolute value of the magnitude of coefficients)

Where,

λ denotes the amount of shrinkage.
λ = 0 implies all features are considered and it is equivalent to the linear regression where only the residual sum of squares is considered to build a predictive model
λ = ∞ implies no feature is considered i.e, as λ closes to infinity it eliminates more and more features
The bias increases with increase in λ
variance increases with decrease in λ
