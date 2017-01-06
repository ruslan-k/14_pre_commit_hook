# Quadratic Equations Solver

Script finds roots of quadratic equations.

# Usage

    quadratic_equation import get_roots
    get_roots(a, b, c)

Where a, b,c - coefficients of equation ```ax^2+bx+c=0```.

# Pre-commit hook

Pre-commit hook allows to run unit tests in tests.py file when you try to commit. If one or more tests fails it will not allow to commit and show you appropriate error.
Copy ```pre-commit``` file in ```.git/hooks/``` directory where project resides, give it execution permission ```chmod +x pre-commit```.

# Requirement

    python 3.5

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
