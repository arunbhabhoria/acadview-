#Q.1 - Create a numpy array with 10 elements of the shape(10,1) using np.random and find out the mean of the elements using basic numpy functions.
#Sol:-
import numpy as np
arr=np.array([[1],[4],[3],[5],[6],[2],[9],[11],[8],[0]])
print("Shape of Array:",arr.shape)
print("Mean of Elements:",np.mean(arr))

#OR Using np.random

import numpy as np
arr=np.random.rand(10,1)
print("Shape of Array:",arr.shape)
print("Mean of Elements:",np.mean(arr))


#Q.2 - Create a numpy array with 20 elements of the shape(20,1) using np.random find the variance and standard deviation of the elements.
#Sol:-
import numpy as np
arr=np.random.rand(20,1)
print("variance:",np.var(arr))
print("standard deviation:",np.std(arr))

#Q.3 - Create a numpy array A of shape(10,20) and B of shape (20,25) using np.random. Print the matrix which is the matrix multiplication of A and B.The shape of the new matrix should be (10,25).Using basic numpy math functions only find the sum of all the elements of the new matrix.
#Sol:-
import numpy as np
x1=np.random.rand(10,20)
x2=np.random.rand(20,25)
new=np.dot(x1,x2)
print("Multiplication of Array A and B:",new)
print("shape of the New Matrix:",np.shape(new))
print("Sum Of the New Matirx:",np.sum(new))


