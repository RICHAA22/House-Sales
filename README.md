# House-Sales
DA Project
Data Analytics Project
Explanation of models used

1.) Linear Regression: Linear regression is a linear approach to modelling
the relationship between a scalar response and one or more explanatory
variables (also known as dependent and independent variables). In this
case we have used it to make a comparison between that particular
variable which has a positive correlation with the house price.

2.) Multiple Linear Regression: Multiple linear regression attempts to
model the relationship between two or more explanatory variables and
a response variable by fitting a linear equation to observed data. Every
value of the independent variable x is associated with a value of the
dependent variable y. AN example of this in our research could be how
the price of the house changes with the increase of number of rooms
and location. Ideally the more populated locations will have smaller
houses but will still be more expensive and this is where multiple linear
regression will help with exact pinpointing of how these three variables
are related thereby helping us to find the ideal price using the location
and size of the house.
3.) LASSO REGRESSION: Lasso regression is one of the techniquesused to
reduce model complexity and prevent over-fitting which may result from
simple linear regression. For example regarding the dataset used, lets
say we have shortlisted a few houses already based on our requirements
and we need to shrink the said set of houses based on certain
parameters, that’s where lasso regression can help us in the “shrinking”
of the set of houses.

Hypothesis:

We are making an null hypothesis that house prices increase with the
increase in the sq.ft area.
For this we will make use of the mean of the house prices which turns
out to be 2070 sq.ft.
We are setting our confidence level to be 0.05.
We will assume that any house area with larger than 2060 sq.ft tend to
have large prices.
After the results of the p-tail value test our p value turns out to be
0.00072 which is very much lesser than our confidence level.
It implies for the rejection our null hypothesis.So the house price does
not solely dependent on the sq.ft.The price also depends on the other
factors like place,trend,latitude and longitude.
We can easily tell that a house with the 800 sq.ft area in Mumbai has
more price than a 1000 Sq.ft house in some random village.

These are the models that have been used in our study and a brief explanation
of what they are and how they work.
