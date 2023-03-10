Multiclass SVM using mini-batch Gradient Descent (mbSGD) solver.

The mathematical objective function for the soft margin SVM using parameters w and b is given by:   

πππ(1/2β||π€||2+πΆββππ=1[π¦(π)βπππ₯(0,1βπ€βπ₯(π)+π)])      

where C is the penalty term,   
x(i) is the ith training data point,   
y(i) is the corresponding label (1 or -1), and ||w|| is the norm of the weight vector w.   

The function seeks to minimize the sum of the distance of the points from the decision boundary (measured by the norm of w) and the penalty for misclassifications (measured by the max function).
