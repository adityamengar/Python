Lists (and many other complex Python entities) are stored in different ways than ordinary (scalar) variables.

-> the name of an ordinary variable is the name of its content;
-> the name of a list is the name of a memory location where the list is stored.

e.g. -
list_1 = [1]
list_2 = list_1
list_1[0] = 2
print(list_2)

Output:
[2]