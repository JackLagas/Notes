# Question 1
$$
\text{Let M = }
\left [{\begin{array}{cc}
1 & -2 \\
-2 & 3 \\
\end{array}}\right]
$$
$$
M^{-1} = 
$$

## Solution:
$$
\left [{\begin{array}{cc}
1 & -2 \\
-2 & 3 \\
\end{array}}\right]
\times
\left [{\begin{array}{cc}
x_1 & x_2 \\
x_3 & x_4 \\
\end{array}}\right]
\text{ = }
\left [{\begin{array}{cc}
1 & 0 \\
0 & 1 \\
\end{array}}\right]
$$
$$
\begin{cases}
1x_{1} &- &2x_{3} &= &1\\
1x_{2} &- &2x_{4} &= &0 \\
-2x_{1} &+ &3x_{3} &= &0\\
-2x_{2} &+ &3x_{4} &= &1 \\
\end{cases}
$$
$$
\left [{\begin{array}{cc}
1 & 0 & -2 & 0 & 1 \\
0 & 1 & 0 & -2 & 0 \\
-2 & 0 & 3 & 0 & 0 \\
0 & -2 & 0 & 3 & 1 \\
\end{array}}\right]
$$
$$
\left [{\begin{array}{cc}
1 & 0 & -2 & 0 & 1 \\
0 & 1 & 0 & -2 & 0 \\
-2 & 0 & 3 & 0 & 0 \\
0 & -2 & 0 & 3 & 1 \\
\end{array}}\right]
R_{3}' = R_{3} + 2R_{1}
$$
$$
\left [{\begin{array}{cc}
1 & 0 & -2 & 0 & 1 \\
0 & 1 & 0 & -2 & 0 \\
0 & 0 & -1 & 0 & 2 \\
0 & -2 & 0 & 3 & 1 \\
\end{array}}\right]
R_{4}' = R_{4} + 2 R_{2}
$$
$$
\left [{\begin{array}{cc}
1 & 0 & -2 & 0 & 1 \\
0 & 1 & 0 & -2 & 0 \\
0 & 0 & -1 & 0 & 2 \\
0 & 0 & 0 & -1 & 1 \\
\end{array}}\right]
\begin{aligned}
R_{3}' = -R_{3} \\
R_{4}' = -R_{4} \\
\end{aligned}
$$
$$
\left [{\begin{array}{cc}
1 & 0 & -2 & 0 & 1 \\
0 & 1 & 0 & -2 & 0 \\
0 & 0 & 1 & 0 & -2 \\
0 & 0 & 0 & 1 & -1 \\
\end{array}}\right]
\begin{aligned}
R_{1}' = R_{1} + 2R_{3} \\
R_{2}' = R_{1} + 2R_{4} \\
\end{aligned}
$$
$$
\left [{\begin{array}{cc}
1 & 0 & 0 & 0 & -3 \\
0 & 1 & 0 & 0 & -2 \\
0 & 0 & 1 & 0 & -2 \\
0 & 0 & 0 & 1 & -1 \\
\end{array}}\right]
$$

## Answer:
$$
\left [{\begin{array}{cc}
-3 & -2 \\
-2 & -1 \\
\end{array}}\right]
$$
# Question 2
$$
\text{Let M = }
\left [{\begin{array}{cc}
-2 & 1 \\
1 & -1 \\
\end{array}}\right]
$$
$$
M^{-1} = 
$$

## Solution:
$$
\left [{\begin{array}{cc}
-2 & 1 \\
1 & -1 \\
\end{array}}\right]
\times
\left [{\begin{array}{cc}
x_1 & x_2 \\
x_3 & x_4 \\
\end{array}}\right]
\text{ = }
\left [{\begin{array}{cc}
1 & 0 \\
0 & 1 \\
\end{array}}\right]
$$
$$
\begin{cases}
-2x_{1} &+ &1x_{3} &= &1\\
-2x_{2} &+ &1x_{4} &= &0 \\
1x_{1} &- &1x_{3} &= &0\\
1x_{2} &- &1x_{4} &= &1 \\
\end{cases}
$$
$$
\left [{\begin{array}{cc}
-2 & 0 & 1 & 0 & 1 \\
0 & -2 & 0 & 1 & 0 \\
1 & 0 & -1 & 0 & 0 \\
0 & 1 & 0 & -1 & 1 \\
\end{array}}\right]
$$