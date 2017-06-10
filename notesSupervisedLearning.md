
Notes taken

What is Machine Learning -

Even among machine learning practitioners there isn't a well accepted definition of what is and what isn't machine learning. But let me show you a couple of examples of the ways that people have tried to define it. Here's the definition of what is machine learning does to Arthur Samuel. He defined machine learning as the field of study that gives computers the ability to learn without being explicitly programmed.

Tom Mitchell defines machine learning by saying that, a well posed learning problem is defined as follows. He says, a computer program is said to learn from experience E, with respect to some task T, and some performance measure P, if its performance on T as measured by P improves with experience E.

I'm going to spend a lot of the time teaching you those sorts of best practices in machine learning and AI and how to get this stuff to work and how we do it, how the best people do it in Silicon Valley and around the world. I hope to make you one of the best people in knowing how to design and build serious machine learning and AI systems. 

In general, any machine learning problem can be assigned to one of two broad classifications:

Supervised learning and Unsupervised learning.

_______________________________________________________________________________________________________________________________

Improving your posts

Upvote

“I would love to understand what others think.”
_______________________________________________________________________________________________________________________________

Supervosed Learning

Regression problem = "predict a continuous value output"

classification problem

Support Vector Machine, a neat mathematical trick that will allow a computer to deal with an infinite number of features


in supervised learning, in every example in our data set, we are told what is the "correct answer" that we would have quite liked the algorithms have predicted on that example. Such as the price of the house, or whether a tumor is malignant or benign. We also talked about the regression problem. And by regression, that means that our goal is to predict a continuous valued output. And we talked about the classification problem, where the goal is to predict a discrete value output.

Supervised Learning

In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

Supervised learning problems are categorized into "regression" and "classification" problems. In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

Example 1:

Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.

We could turn this example into a classification problem by instead making our output about whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.

Example 2:

(a) Regression - Given a picture of a person, we have to predict their age on the basis of the given picture

(b) Classification - Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.
