# Partial-Differential-Equation-Solver
Symbolic PDE Solver using SymPy
This project demonstrates how to solve Partial Differential Equations (PDEs) symbolically using Python's SymPy library.

Overview
This script defines and solves a partial differential equation (PDE) symbolically using SymPy. It leverages SymPy's powerful features for symbolic mathematics, such as defining symbolic variables, functions, and solving differential equations.

Solution:
Using SymPy's pdsolve method, we solve the PDE symbolically and extract the solution.

Requirements
Python 3.x
SymPy library

The sympy library in Python is a powerful tool for symbolic mathematics. It allows for algebraic manipulations, calculus, solving equations, and working with mathematical expressions in a symbolic manner (using variables instead of specific numbers). When you import it as sp, you are simply giving the sympy library a shorter alias to make your code easier to read and write.

for example:
import sympy as sp

x = sp.symbols('x')
expr = x**2 + 2*x + 1
expanded_expr = sp.expand(expr)  # Expands the expression
solution = sp.solve(expr, x)     # Solves the equation for x
This makes it easier to perform symbolic computations in Python.
