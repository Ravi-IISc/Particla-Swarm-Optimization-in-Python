# Particle-Swarm-Optimization-in-Python (PSO) without constraints 
Minimization Problem - 
PSO or Particle Swarm Optimization is a new method to find the optimum solution of a given function. It is a non gradient based algorithm. 
PSO was originally given by Kennedy, Eberhart and shi (1995). For details vist https://ieeexplore.ieee.org/document/488968

Algorithm - 
1. As mentioned above, this algorithm does not require gradient or hessian of the objective function. It starts with placing the points(particles or swarms) arbitrary in a n-dimensional space. Assume x1, x2, x3,...., xn are the independent variables and there are N points (Swarm Size). SO location of the swarms in the n-dimensional space will be - 
(x1,x2,...,xn)-first particle
(x1,x2,...,xn)-second particle
.
.
(x1,x2,...,xn)-Nth particle

2. Compute objective function value at all the points (given ablove).

3. Then find the minimum value among all the calculated values and point associated with that minimum value is G-Best (Global best). Check this condition in every iteration.

4. To find the P-Best (Personal Best) and update the posotion of the each particle. 
5. Stop the iteration when desired tolerence reached for objective function. 

