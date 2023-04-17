### **Assignment 4**
1. For the classification algorithms used in the previous assignments, SVM and Decision Tree Algorithms, verify the learning bunds R(h). The R(h) for the Decision Tree and SVM are given as
follows:
R(h) ≤ Rˆ(h) + 
(n+1)log(d +3) +log(
2
δ
)
2m
!
1
2
(Decisson Tree)
R(h) ≤ Rˆ(h) +r
2log(d +1)
m
+s
log(
1
δ
)
m(SVM),
where n is the number of nodes in the tree, d is the number of features, δ = 0.1 is a constant, and
m is the number of sample observations. Also, compare these bounds with the probability of error
obtained via the training set and the testing set.
2. Consider the given dataset DataSet_4.csv, which has a conditional distribution of
Pr(x1, x2,..., xm|µ) =
m
∏
i=1
1
√
2π det(Λ)
exp
(xi − µ)
TΛ
−1
(xi − µ)
2

, (1)
where xi = [xi(1), xi(2)],i = 1,...,m, µ = [µ1, µ2], and Σ =

σ
2
1
0
0 σ
2
2

. Derive the estimate µˆ of
µ in MLE.
3. Suppose we have a sample of N pairs xi
, yi drawn i.i.d. from the distribution characterized as:
xi ∼ Uni f orm(0, 3)
yi = m0(xi) +εi
, m0(x) = 2sin(x) is the nonlinear regressor function
εi ∼ N (0,σ
2
), σ
2 = 0.25.
(2)
Estimate the regression function ˆm0(x) at x = [0, 0.35, 0.70, 1.05, 1.40, 1.75, 2.10, 2.45, 2.80, 3.14]
using K