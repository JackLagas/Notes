## Question 1
Solve the following system of equations
$$
    \begin{cases}
	 & x - 2y  = 3 \\ \\
     & 4x + 3y = 23 
    \end{cases}       
$$
### Solution:
$$
  \left[ {\begin{array}{cc}
    1 & -2 & 3 \\
    4 & 3 & 23 \\
  \end{array} } \right]
$$
$$
  \left[ {\begin{array}{cc}
    1 & -2 & 3 \\
    4 & 3 & 23 \\
  \end{array} } \right] R_{2}' = R_{2} - 4R_{1}
$$
$$
  \left[ {\begin{array}{cc}
    1 & -2 & 3 \\
    0 & 11 & 11 \\
  \end{array} } \right] R_{2}' = \frac{R_2}{11}
$$
$$
  \left[ {\begin{array}{cc}
    1 & -2 & 3 \\
    0 & 1 & 1 \\
  \end{array} } \right]\ R_{1}' = R_{1} + 2R_{2}
$$
$$
  \left[ {\begin{array}{cc}
    1 & 0 & 5 \\
    0 & 1 & 1 \\
  \end{array} } \right]
$$
### Answer: 
$$
\begin{cases} 
 & x = 5 \\
 & y =1
\end{cases}
$$

## Question 2
Consider the following system of equations and its graph:

$$
    \begin{cases}
	 & 4x - 3y  = -3 \\ \\
     & 2x + y = -9 
    \end{cases}       
$$
![[TicketInTheDoor1Graph.png]]

## A
What is the solution to the system?
### Solution:
$$
\left [ {\begin{array}{cc}
4 & -3 & -3 \\
2 & 1 & -9 \\
\end{array}} \right]
$$
$$
\left [ {\begin{array}{cc}
4 & -3 & -3 \\
2 & 1 & -9 \\
\end{array}} \right]
R_{1}'= \frac{1}{4}R_{1}
$$
$$
\left [ {\begin{array}{cc}
1 & -\frac{3}{4} & -\frac{3}{4} \\
2 & 1 & -9 \\
\end{array}} \right]
R_{2}' = R_{2} - 2R_{1}
$$
$$
\left [ {\begin{array}{cc}
1 & -\frac{3}{4} & -\frac{3}{4} \\
0 & \frac{5}{2} & -\frac{15}{2} \\
\end{array}} \right]
R_{2}'=\frac{2}{5}R_{2}
$$
$$
\left [ {\begin{array}{cc}
1 & -\frac{3}{4} & -\frac{3}{4} \\
0 & 1 & -3 \\
\end{array}} \right]
R_{1}'=R_{1}+\frac{3}{4}R_{2}
$$
$$
\left [ {\begin{array}{cc}
1 & 0 & -3 \\
0 & 1 & -3 \\
\end{array}} \right]
$$
### Answer:
$$
\begin{cases}
& x = -3 \\
& y = -3 \\
\end{cases}
$$
## B
Identify which of the equations below represents graph A and which equation represents graph B.

### Solution:
$$
4x-3y=-3 
$$
$$
4x+4 = 3y
$$
$$
y = \frac{4}{3}x+1
$$
The slope of this equation is positive therefore it must be the graph of line A

### Answer:
$$
\begin{cases}
& A: && 4x-3y=-3 \\
& B: && 2x + y = -9
\end{cases}
$$

## Question 3
Solve the system. If the system has an infinite number of solutions, parameterize them by letting z  = t.
### Solution:
$$
\begin{cases}
& 7x &+ &2y &- &20z &= &8 \\
& 9x &+ &5y &- &33z &= &20 \\
& -3x &- &y &+ &9z &= &-4
\end{cases}
$$
$$
\left[{ \begin{array}{cc}
7 & 2 & -20 & 8 \\  
9 & 5 & -33 & 20 \\
-3 & -1 & 9 & -4 \\
\end{array} }\right]
$$
$$
\left[{ \begin{array}{cc}
7 & 2 & -20 & 8 \\  
9 & 5 & -33 & 20 \\
-3 & -1 & 9 & -4 \\
\end{array} }\right]
R_{3} <-> R_{1}
$$
$$
\left[{ \begin{array}{cc}
-3 & -1 & 9 & -4 \\
9 & 5 & -33 & 20 \\
7 & 2 & -20 & 8 \\  
\end{array} }\right]
R_{2}' = R_{2} + 3R_{1}
$$
$$
\left[{ \begin{array}{cc}
-3 & -1 & 9 & -4 \\
0 & 2 & -6 & 8 \\
7 & 2 & -20 & 8 \\  
\end{array} }\right]
R_{3}' = R_{3} + \frac{7}{3}R_{1}
$$
$$
\left[{ \begin{array}{cc}
-3 & -1 & 9 & -4 \\
0 & 2 & -6 & 8 \\
0 &  -\frac{1}{3} & 1 & -\frac{4}{3} \\  
\end{array} }\right]
R_{2}'=\frac{R_{2}}{2}
$$
$$
\left[{ \begin{array}{cc}
-3 & -1 & 9 & -4 \\
0 & 1 & -3 & 4 \\
0 &  -\frac{1}{3} & 1 & -\frac{4}{3} \\  
\end{array} }\right]
R'_{1} = R_{1} + R_{2}
$$
$$
\left[{ \begin{array}{cc}
-3 & 0 & 6 & 0 \\
0 & 1 & -3 & 4 \\
0 &  -\frac{1}{3} & 1 & -\frac{4}{3} \\  
\end{array} }\right]
R_{3}'=R_{3}+ \frac{1}{3}R_{2}
$$
$$
\left[{ \begin{array}{cc}
-3 & 0 & 6 & 0 \\
0 & 1 & -3 & 4 \\
0 &  0 & 0 & 0 \\  
\end{array} }\right]
R_{1}' = -\frac{1}{3}R_{1}
$$
$$
\left[{ \begin{array}{cc}
1 & 0 & -2 & 0 \\
0 & 1 & -3 & 4 \\
0 &  0 & 0 & 0 \\  
\end{array} }\right]
$$

### Answer:
$$
\begin{cases}
& x = 2t \\
& y = 4+3t \\
& z = t \\
\end{cases}
$$