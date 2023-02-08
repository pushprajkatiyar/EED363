### **This repo have code belongs to Applied Machine Learning EED363**
This code solves following problem using python and notebook:
1. Consider the given data set (Dataset1_Assignment1.csv). The Data set contains 10000 samples
with two features x1 and x2 and four classes y ∈ {0,1,2,3}. The features are independent and
identically distributed (iid). The distributions are Gaussian with means (−1,−1) for class 0,
(−1,1) for class 1, (1,1) for class 2, and (1,1) for class 3, respectively and the variances are
(σ2 1 = 0.1, σ22 = 0.1) (i.e., P(x|i) = √12πexp(−(x1 −µ1)2)√12π
exp(−(x2 −µ2)2)). The prior probabilities of the classes are π(0) = 0.1, π(1) = 0.3, π(2) = 0.25, and π(3) = 0.35.
   

(a) Using the given information, design a Bayesian Classifier and get the probability of error.

(b) By using the first 5000 samples of the given data set, estimate the prior probabilities πˆ(i),i ∈
{0, 1, 2, 3} and the variances σˆ
2
j
, j ∈ {1,2}. For the second 5000 samples,

• obtain the probability of classification error using the Bayesian classifier of part(a)

• obtain the Bayesian classifier using the obtained πˆ(i), Pˆ(x|i) and σˆ
2
j
, and obtain the
probability of classification error using this classifier.