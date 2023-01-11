Multiclass SVM using mini-batch Stochastic Gradient Descent (mbSGD) solver.

The mathematical objective function for the soft margin SVM using parameters w and b is given by:

𝑚𝑖𝑛(1/2∗||𝑤||2+𝐶∗∑𝑛𝑖=1[𝑦(𝑖)∗𝑚𝑎𝑥(0,1−𝑤∗𝑥(𝑖)+𝑏)])
where C is the penalty term,
x(i) is the ith training data point,
y(i) is the corresponding label (1 or -1), and ||w|| is the norm of the weight vector w.

The function seeks to minimize the sum of the distance of the points from the decision boundary (measured by the norm of w)
and the penalty for misclassifications (measured by the max function).
