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
  
# Powerful Slices  
A slice is an element of Python syntax that allows you to make a brand new copy of a list, or parts of a list.  
It actually copies the list's contents, not the list's name.  

Example:  
list_1 = [1]  
list_2 = list_1[:]  
list_1[0] = 2  
print(list_2)  

OUTPUT IS [1] //This inconspicuous part of the code described as [:] is able to produce a brand new list.This inconspicuous part of the code described as [:] is able to produce a brand new list.  