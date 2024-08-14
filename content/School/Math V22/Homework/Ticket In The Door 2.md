# Question 1
Write the augmented coefficient matrix corresponding to the system:
$$
\begin{cases}
& -8x + 10 = -5y \\
& -5x -9y = -8 \\
& -x + 10 = 0 \\
\end{cases}
$$
### Answer:
$$
\left[{ \begin{array}{cc}
-8 & 5 & -10 \\
-5 & -9 & -8 \\
-1 & 0 & -10
\end{array}} \right]
$$

# Question 2
$$
\text{Let M} = \left[{\begin{array}{cc}
8 & -9 & 9 & -5 \\
0 & -1 & 5 & 3 \\ 
-10 & 7 & -6 & -4
\end{array}} \right]
$$
## A 
What are the dimensions of this matrix?
### Answer:
3x4 Matrix

## B
What is M<sub>14</sub>
### Answer:
M<sub>14</sub> refers to the fourth column of the first row of matrix M.
In this case it is -5.

# Question 3
Suppose the row echelon form of a system of equations is 
$$
\begin{cases}
& x &+ &4y &+ &7z &= &7 \\
&   &  &y &+ &3z &= &-3 \\ 
\end{cases}
$$

## Solution:
$$
\left[{\begin{array}{cc}
1 & 4 & 7 & 7 \\
0 & 1 & 3 & -3 \\
\end{array}} \right]
$$

$$
\left[{\begin{array}{cc}
1 & 4 & 7 & 7 \\
0 & 1 & 3 & -3 \\
\end{array}} \right]
R_{1}' = R_{1} - 4R_{2}
$$
$$
\left[{\begin{array}{cc}
1 & 0 & -5 & 19 \\
0 & 1 & 3 & -3 \\
\end{array}} \right]
$$

$$
\begin{cases}
& x & & &- &5z &= &19 \\
& & &y &+ &3z &= &-3
\end{cases}
$$
$$
\begin{cases}
& x =  19 + 5z\\
& y = -3-3z \\
\end{cases}
$$
$$
z = t
$$
## Answer:
$$
\begin{cases}
& x = 19 + 5t \\
& y = -3 - 3z \\
& z = t \\
\end{cases}
$$

# Question 4
Fill in the blanks.

By definition, a matrix is in row echelon form if:
A. If a row does not consist entirely of zeros, then the first nonzero number in the row is a \_\_\_\_.
B. If there are any rows that consist entirely of zeros, then they are grouped together at the \_\_\_\_\_\_\_\_\_\_ of the matrix.  
C. In any two successive rows that do not consist entirely of zeros, the leading 1 in the lower row occurs \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ than the leading 1 in the higher row.

## A
One
## B
Bottom
## C
Further right

# Question 5
Which of the following matrices are in row echelon form?

$$
\text{Let A =}
\left [{\begin{array}{cc}
0 & 4 & -8 \\
4 & 7 & 3 \\
0 & 0 & 4 \\
\end{array}}\right]
$$
$$
\text{Let B =}
\left [{\begin{array}{cc}
1 & -3 & 9 & -2 \\
0 & 1 & -4 & -2 \\
\end{array}}\right]
$$
$$
\text{Let C =}
\left [{\begin{array}{cc}
1 & 0 & 4 \\
0 & 1 & -2 \\
0 & 0 & 0 \\
\end{array}}\right]
$$
$$
\text{Let D =}
\left [{\begin{array}{cc}
0 & 1 & -2 & 0 & 1 \\
0 & 0 & 0 & 1 & 3 \\
0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
\end{array}}\right]
$$
$$
\text{Let E =}
\left [{\begin{array}{cc}
2 & 4 & 6 \\
0 & 1 & 3 \\
0 & 0 & 0 \\
\end{array}}\right]
$$

## Answer:
B, C, & D are in Row-Echelon Form.


# Question 6
$$
\text{Let M = }
\left [{\begin{array}{cc}
4 & 2 & 3 \\
-4 & -2 & -5 \\
\end{array}}\right]
$$
Enter the matrix formed by performing the row operation 2R<sub>1</sub> + R<sub>2</sub> -> R<sub>2</sub>

## Answer:
$$
\left [{\begin{array}{cc}
4 & 2 & 3 \\
4 & 2 & 1 \\
\end{array}}\right]
$$

# Question 7
Which of the following is NOT an elementary row operation?  
- A) Delete a row of negative numbers  
- B) Multiply a row by a nonzero constant  
- C) Interchange (swap) two rows  
- D) Add a multiple of one row to another row
## Answer:
A, you cannot delete rows.

# Question 8
According to a definition, which of the following is NOT a condition for a matrix to be in reduced row echelon form
- A) The matrix is in row echelon form  
- B) The leading entry in each nonzero row is the number 0  
- C) The leading entry in each nonzero row is the number 1  
- D) The leading entry in each nonzero row is the only nonzero entry in its column

## Answer:
B, the leading entry must be nonzero by definition.

# Question 9
$$
\text{Let M = }
\left[{\begin{array}{cc}
1 & -3 & -5 \\
4 & 3 & -4 \\
\end{array}}\right]
$$
Find the row echelon form.
Hint: Do not make the pivots equal to 1.

## Solution:
$$
\left[{\begin{array}{cc}
1 & -3 & -5 \\
4 & 3 & -4 \\
\end{array}}\right]
R_{2}' = R_{2} - 4R_{1}
$$
$$
\left[{\begin{array}{cc}
1 & -3 & -5 \\
0 & 15 & 16 \\
\end{array}}\right]
$$

## Answer:
$$
\left[{\begin{array}{cc}
1 & -3 & -5 \\
0 & 15 & 16 \\
\end{array}}\right]
$$

# Question 10
Solve the system of equation
$$
\begin{cases}
& x &= -2 - 3z - 2y \\
& 5x - 4y &= 4 \\
\end{cases}
$$
Enter your solution in parameterized form, using t to parameterize the free variable.

## Solution:
$$
\begin{cases}
& x &+ &2y &+ &3z &= &-2 \\
& 5x &- &4y & & &= &4
\end{cases}
$$
$$
\left[{\begin{array}{cc}
1 & 2 & 3 & -2 \\
5 & -4 & 0 & 4 \\
\end{array}}\right]
R_{2}' = R_{2} - 5R_{1}
$$
$$
\left[{\begin{array}{cc}
1 & 2 & 3 & -2 \\
0 & -14 & -15 & 14 \\
\end{array}}\right]
R_{1}'=R_{1} + \frac{1}{7}R_{2}
$$
$$
\left[{\begin{array}{cc}
1 & 0 & 3 & 0 \\
0 & -14 & -15 & 14 \\
\end{array}}\right]
$$