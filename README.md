# Machine Learning Projects Repository

In this repository I share 3 notebooks where I have practiced to solve supervised predictive modeling problems from end-to-end. Well we have learned that applied machine learning is an empirical skill. We cannot get better at it by watching videos, reading books and articles. We have to practice.

The three notebooks cover the following types of case study predictive modeling problems:
* Multiclass classification, 
* Regression, and
* Binary classification.

In the *classification* projects I go through the most most basic and oldest data to practice on, the *iris flowers*. This is the best small project to start with and it's well understood . 

The second project is on *regression*. Where we will investigate the *Boston House Price dataset*. Now, this project isn't as easy as the first one as it involves more steps to work through and probably more. Nevertheless, it's a lot of fun to do.

The third project is on *binary* classification. The focus of this project will be the *Sonar Mines vs Rocks dataset*. Where we will predict the metal or rock objects from sonar return data.

All the datasets used are available on this repository and they're also available from [UCI Machine Learning repository](https://goo.gl/mLmoIz).

# What's Machine learning?
Machine learning is a part of applied mathematics and computer science. 
It uses tools from mathematical disciplines such as probability, 
statistics, and optimization theory to extract patterns from data.

The main task of machine learning is learning from examples, which is, we take a dataset with examples, and a machine learning algorithm "learns" or trains from this dataset. This algorithms try to come up with a way to make predictions without the assistance of a human.

The problems that we solve in this repository are an example of *supervised learning*, where as we said, we provide the algorithm with examples. Where the example here is features and the target variable, and the algorithm figures out how to use these features to arrive at the target.

In short, we can express a supervised machine learning model 
mathematically as

$$
y \approx g(X)
$$
where
* $g$ is the function that we want to learn with machine learning.
* $X$ is the feature matrix in which rows are the feature vectors.
* $y$ is the target variable.

The goal of machine learning is to learn this function $g$ in such a way 
that when it gets the matrix $X$, the output is close to the vector $y$.

There are different types of supervised machine learning problems, and 
the types depends on the target variable $y$. These types are:
* Regression: here the target variable $y$ is numeric, such as *rands* or  *weight*.
* Classification: the target variable $y$ is categorical, such as *red*  or *blue* or *disease* and *no disease*. We can further split  classification into two subcategories: (1) *binary classification*, which has only two possible outcomes, such as spam or not spam, and (2) *multiclass classification*, which has more than two possible outcomes, such as a car make (BMW, Mercedes, Audi, etc.).
* Ranking: the target variable $y$ is an ordering of elements within a group, such as the order of pages in a search-result page. The problem of ranking often happens in areas like search and recommendations, which I plan to do the project on in future.

Many different algorithms are used to solve each supervised learning problem. Some popular examples of supervised machine learning algorithms are:
* Linear regression for regression problems.
* Random forest for classification and regression problems.
* Support vector machines for classification problems.

# Machine learning process
Selecting a model and the train it to mae predictions is a small step in the process.

The approach I indicate in these projects follows the framework of 
**CRISP-DM**, which stands for *Cross-Industry Standard Process for Data Mining*. According to this framework, the machine learning process has six steps:
* Business understanding (Defining problems)
* Data understanding
* Data preparation
* Modeling
* Evaluation
* Deployment

Each phase covers typical steps:
* In the business understanding step, we try to identify the problem, to understand how we can solve it, and to decide whether machine learning will be a useful tool for solving it.
* In the data understanding step, we analyse available datasets and decide whether we need to collect more data.
* In the data preparation step, we transform the data into a tabular form that we can use as input for a machine learning model.
* When the data is prepared, we move to the modeling step, in which we train a model.
* After the best model is identified, there’s the evaluation step, where we evaluate the model to see if it solves the original business problem and measure its success at doing that.
* Finally, in the deployment step, we deploy the model to the production environment.

In this repository unfortunately I don't cover the last step of deployment. In other projects I will.