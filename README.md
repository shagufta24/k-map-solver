# Karnaugh Map Solver

**Introduction:**

A Karnaugh map (K-map) is a pictorial method used to minimize Boolean expressions without having to use Boolean algebra theorems and equation manipulations.Using a K-map, expressions with two to four variables are easily minimized. Expressions with five to six variables are more difficult but achievable.

In many digital circuits and practical problems, there is a need to simplify booleam expressions. The K-map can take two forms: Sum of Products (SOP) and Product of Sums (POS) expressions and simplify them.

#

**Aim:**

A program to simplify a minterm (SOP) or maxterm (POS) boolean expression with 2, 3 or 4 variables using the Karnaugh Map method.

The number of variables, variable names and minterm (or maxterm) numbers are taken as input from the user. The program generates a pictorial representation of the corresponding k-map and displays the simplified expression.

#

**How to run:**

Run: >> python kmap.py

SAMPLE OUTPUT:

Enter number of inputs (2, 3 or 4): 3
Enter 'SOP' for Minterms form or 'POS' for Maxterms form: SOP
Enter Minterms: 2 4 5 7

Enter variables with single space (eg:A B C): x y z

The K-Map plotted:

0 0 0 1

1 1 1 0

Simplified boolean expression: xy' + xz + x'yz'

Enter 'y' to try again or 'n' to exit: n
