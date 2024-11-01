                                                                        Root Finding with Bisection Method
This Python script finds the root of the function f(x) = x^3 - x^2 + 2 within a specified interval using

Description of the Bisection Method:
The Bisection Method is a root-finding method for continuous functions where the values at two
points have opposite signs, indicating a root in between.
It divides the interval in half, selecting the subinterval containing the root, and repeats this process
until reaching the desired tolerance level.

Steps:
1. Calculate the midpoint, c = (a + b) / 2.
2. If f(c) == 0, c is the root.
3. If f(a) * f(c) < 0, the root is between a and c; update b = c.
4. If f(b) * f(c) < 0, the root is between b and c; update a = c.
5. Repeat until the interval size is within the specified tolerance.

Example I/O:
Input:
-200
300
0.01
Output:
-1.0025
