# LIST  
A list is a built-in, mutable, and ordered collection of items enclosed in square brackets []. It allows you to store multiple values in a single variable, maintain their insertion order, and mix different data types (like integers, strings, and booleans) within the same container.  
eg: numbers = [10, 5, 7, 2, 1]  
assigned no. =  0, 1, 2, 3, 4  
[ Python has adopted a convention stating that the elements in a list are always numbered starting from zero. This means that the item stored at the beginning of the list will have the number zero. Since there are five elements in our list, the last of them is assigned the number four. Don't forget this. ]  
  
# The len() function  
If you want to check the list's current length, you can use a function named len() (its name comes from length).  
  
# Removing elements from a list 'del'  
Any of the list's elements may be removed at any time ‒ this is done with an instruction named del (delete). Note: it's an instruction, not a function.  
  
# Negative indices are legal
An element with an index equal to -1 is the last one in the list  
eg:-   
numbers = [111, 7, 2, 1]  
print(numbers[-1])  
Output: 1  

Similarly, the element with an index equal to -2 is the one before last in the list  
numbers = [111, 7, 2, 1]  
print(numbers[-2])  
Output: 2  

# Adding Elements To A List: append() & insert()
append(): It takes its argument's value and puts it at the end of the list. -> list.append(value)

insert():  it can add a new element at any place in the list, not only at the end. -> list.insert(location, value)

## MAKING USE OF LISTS  
The for loop has a special variant that can process lists very effectively  
Eg:  
my_list = [10, 1, 8, 3, 5]  
total = 0  
 
for i in range(len(my_list)):  
    total += my_list[i]  

print(total)  

OUTPUT: 27  

## SECOND ASPECT OF THE 'for' Loop:  
my_list = [10, 1, 8, 3, 5]  
total = 0  

for i in my_list:  
    total += i  

print(total)  

OUTPUT: 27  
-> for i in my_list: goes through each item in the list.  
-> i stores one item at a time.  
-> The loop runs once for every item.  
-> No index is needed.  
-> len() is not required.  

## Python offers a more convenient way of doing the swap  
variable_1 = 1  
variable_2 = 2  
  
variable_1, variable_2 = variable_2, variable_1  

## We can easily swap the list's elements to reverse their order:

my_list = [10, 1, 8, 3, 5]
 
my_list[0], my_list[4] = my_list[4], my_list[0]
my_list[1], my_list[3] = my_list[3], my_list[1]
 
print(my_list)

OUTPUT: [5, 3, 8, 1, 10]

main