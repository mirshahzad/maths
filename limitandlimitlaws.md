In mathematics, limits and limit laws are fundamental concepts in calculus that are used to describe the behavior of functions as their input values approach a certain point. The limit of a function at a particular point is the value that the function approaches as the input values get arbitrarily close to that point. Limit laws are a set of rules and properties that allow mathematicians to evaluate limits of functions more easily. Some of the basic limit laws include:
•	Sum law for limits: The limit of the sum of two functions equals the sum of the limits of the two functions.
•	Difference law for limits: The limit of the difference of two functions equals the difference of the limits of the two functions.
•	Constant multiple law for limits: The limit of a constant multiple of a function equals the product of the constant with the limit of the function.
•	Product law for limits: The limit of a product of functions equals the product of the limits of each function.
•	Quotient law for limits: The limit of a quotient of functions equals the quotient of the limit of each function.
•	Power law for limits: The limit of the nth power of a function equals the nth power of the limit of the function.
•	Root law for limits: The limit of the nth root of a function equals the nth root of the limit of the function.

These laws are used to simplify the process of evaluating limits of functions, especially for polynomials and rational functions. They provide a systematic way to analyze the behavior of functions as they approach specific values, and are essential tools in calculus for understanding continuity, derivatives, and integrals. By applying these laws, mathematicians can efficiently determine the behavior of functions without having to go through step-by-step processes each time.

Some examples of limit laws and their solutions:
•	Constant Law: The limit of a constant function is equal to the constant. For example, $\lim_{x\to 3} 5 = 5$.
•	Identity Law: The limit of the identity function is equal to the limit point. For example, $\lim_{x\to 4} x = 4$.
•	Sum Law: The limit of the sum of two functions is equal to the sum of the limits of the two functions. For example, $\lim_{x\to -7} (x + 5) = \lim_{x\to -7} x + \lim_{x\to -7} 5 = (-7) + 5 = -2$.
•	Constant Coefficient Law: The limit of a constant times a function is equal to the constant times the limit of the function. For example, $\lim_{x\to 3} (8x) = 8\,\lim_{x\to 3} x = 8(3) = 24$.
•	Product Law: The limit of the product of two functions is equal to the product of the limits of the two functions. For example, $\lim_{x\to 2} (x^2 + 3x) = \lim_{x\to 2} x^2 \cdot \lim_{x\to 2} (3x) = (2^2) \cdot (3 \cdot 2) = 24$.
•	Quotient Law: The limit of the quotient of two functions is equal to the quotient of the limits of the two functions, provided the limit of the denominator is not zero. For example, $\lim_{x\to 1} \frac{x^2 - 1}{x - 1} = \lim_{x\to 1} \frac{(x + 1)(x - 1)}{x - 1} = \lim_{x\to 1} (x + 1) = 2$.
•	Power Law: The limit of a function raised to a power is equal to the limit of the function raised to that power. For example, $\lim_{x\to 2} (x^3) = (\lim_{x\to 2} x)^3 = 2^3 = 8$.
•	Root Law: The limit of the nth root of a function is equal to the nth root of the limit of the function. For example, $\lim_{x\to 4} \sqrt{x} = \sqrt{\lim_{x\to 4} x} = \sqrt{4} = 2$.

These laws are used to simplify the process of evaluating limits of functions, especially for polynomials and rational functions. They provide a systematic way to analyze the behavior of functions as they approach specific values, and are essential tools in calculus for understanding continuity, derivatives, and integrals.
Chain rule to evaluate limits:
The chain rule is a fundamental concept in calculus that allows for the evaluation of limits of composite functions. By following these steps, one can systematically determine the limit of a composite function as the independent variable approaches a specific value. This process is essential for understanding the behavior of complex functions and is widely used in various fields of mathematics and science.

Chain Rule evaluation steps:
i.	Set the Inner Function: Given a function $f(g(x))$, set the inner function equal to $g(x)$ and find the limit, $b$, as $x$ approaches $a$.
ii.	Replace the Inner Function: Replace $g(x)$ in $f(g(x))$ with $u$ to get $f(u).
iii.	Find the Limit of the Inner Function: Find the limit, $B$, of $g(x)$ as $x$ approaches $a$.
iv.	Find the Limit of the Outer Function: Find the limit, $L$, of $f(u)$ as $u$ approaches $B.
v.	Final Result: The limit of $f(g(x))$ as $x$ approaches $a$ is equal to $L$.
