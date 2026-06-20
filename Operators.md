# Basic Operators
An operator is a symbol of the programming language, which is able to operate on the values.
Mostly used Arithmetic Operators Are :
+
-
*
/
//
%
**

Remember: It's possible to formulate the following rules based on this result:

when both ** arguments are integers, the result is an integer, too;
when at least one ** argument is a float, the result is a float, too.
eg: 
print(2 ** 3)
print(2 ** 3.)
Output:
8
8.0
(SAME EXAMPLE IS APPLICABLE TO MULTIPLICATION(*) ALSO)

# DIVISION
The result produced by the division operator is always a float for (/)

Integer Division
A // (double slash) sign is an integer division operator.
integer and float rule is applicable here as we did for ** & *

In this rounding always goes to the lesser integer.
eg: print(-6 // 4)
print(6. // -4)
Output: -2
-2.0 (actual answer when solving comes -1.5 but it rounds off to less integer value i.e. -2 & -2.0)

# Modulo % Operator
The result of the operator is a remainder left after the integer division. eg:
print(14 % 4)
-> 2
print(12 % 4.5)
-> 3.0

Python follows the fundamental rules of BODMAS
Some operators act before others - the hierarchy of priorities:

the ** operator (exponentiation) has the highest priority;
then the unary + and - (note: a unary operator to the right of the exponentiation operator binds more strongly, for example 4 ** -1 equals 0.25)
then: *, /, and %,
and finally, the lowest priority: binary + and -.
