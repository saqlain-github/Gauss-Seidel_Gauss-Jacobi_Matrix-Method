# Gauss-Seidel_Gauss-Jacobi_Matrix-Method
Gauss-Seidel_Gauss-Jacobi_Matrix-Method


Consider the normalized system Ax = b

Write A = I + L + U, where 
I is an identity matrix 
L is lower triangular matrix with diagonal entries 0 
U is upper triangular matrix with diagonal entries 0
  Ax = (I + L + U)x = b

xk+1 = -Lxk – Uxk + b (Gauss Jacobi)

xk+1 = -(I + L)-1Uxk +(I + L)-1b (Gauss Seidel)

Converges if ![image](https://user-images.githubusercontent.com/93789482/164529593-5a13ed7b-2fbe-4a8d-9e4f-6e05ea00b765.png)< 1


Do not conclude that strict diagonal dominance is a necessary condition for convergence of the Gauss Jacobi or Gauss- Seidel methods. For instance, the coefficient matrix of the system

![image](https://user-images.githubusercontent.com/93789482/164530230-b86ed317-9500-4a7f-9c77-98d4c91e60b7.png)


is not a strictly diagonally dominant matrix, and yet both methods converge to the solution x1 = 1 and x2 = 1 when you use an initial approximation of 
(x1, x2) = (0,0).
