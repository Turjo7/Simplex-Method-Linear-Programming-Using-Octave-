# Simplex-Method-Linear-Programming-Using-Octave-
Simplex Method Problem Solving using Octave
Octave Programming
● Octave has built-in function glpk to solve linear 
programming problems in the form:
 min Cx subject to Ax = b, x≥0
or similar.
● Syntax:
[XOPT, FMIN, ERRNUM, EXTRA] 
= glpk (C, A, b, lb, ub, CTYPE, VARTYPE, 
SENSE, PARAM)


Octave Programming
● C : A column array containing the objective function 
coefficients.
● A : A matrix containing the constraints coefficients.
● B : A column array containing the right-hand side value 
for each constraint in the constraint matrix.
● LB : An array containing the lower bound on each of the 
variables. If lb is not supplied, the default lower bound for 
the variables is zero.
● UB : An array containing the upper bound on each of 
the variables. If ub is not supplied, the default upper 
bound is assumed to be infinite.


CTYPE : An array of characters containing the sense of each constraint 
in the constraint matrix. Each element of the array may be one of the 
following values. 
– U : Ax <= b
– L : Ax >= b
– S : Ax = b
● VARTYPE : A column array containing the types of the variables. 
– C : continuous variables
– I : integer variables
● Sense : 1 for minimization (default) and -1 for maximization
● Refer to this link for more detail:
● https://octave.org/doc/v4.4.1/Linear-Programming.html


Exercise (Q1)
● Given that f(x) = 4x1
 – 3x2
 – 2x3
 – x4
. Find the 
max of the function subject to the following 
constraints:
 x1
 + x2
 + x3
 + x4
≤ 20
 2x2
 – 2x3
 – x4
 ≥ –10 
 x1
 , x2
 , x3
 , x4
 ≥ 0
● Check your answer using Octave 
programming.


Exercise (Q2)
● Given that f(x) = 2x1
 + 6x2
 + 10x3
. Find the min of 
the function subject to the following constraints:
 x1
 + x2
 – 4x3
 = 4
 4x1
 – 3x2
 + 2x3
 ≥ -1 
 3x1
 – x2
 + 6x3
≤ 8 
 x1
 , x2
 , x3
 ≥ 0
● Check your answer using Octave programming.

Exercise (Q2)
● Given that f(x) = 2x1
 + 6x2
 + 10x3
. Find the min of 
the function subject to the following constraints:
 x1
 + x2
 – 4x3
 = 4
 4x1
 – 3x2
 + 2x3
 ≥ -1 
 3x1
 – x2
 + 6x3
≤ 8 
 x1
 , x2
 , x3
 ≥ 0
● Check your answer using Octave programming.

