# Partial-Differential-Equation-Solver
The sympy library in Python is a powerful tool for symbolic mathematics. It allows for algebraic manipulations, calculus, solving equations, and working with mathematical expressions in a symbolic manner (using variables instead of specific numbers). When you import it as sp, you are simply giving the sympy library a shorter alias to make your code easier to read and write.
for example:
import sympy as sp

x = sp.symbols('x')
expr = x**2 + 2*x + 1
expanded_expr = sp.expand(expr)  # Expands the expression
solution = sp.solve(expr, x)     # Solves the equation for x
This makes it easier to perform symbolic computations in Python.
