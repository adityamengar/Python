# INTEGERS
In Integers There are 2 addition conventions in Pthon that we havent seen  \
1st one is Octal representation And the second one is Hexadecimal Representation  \
FOR OCTAL WE PRECEED WITH PREFIX 0o or 0O (zero-o) then it will be treated as octal value \
For Eg OCTAL REPRESENTATION  \
if we print(0o123) \
we know that 123 is octal number and when we convert it into decimal number we multiply each digit with 8^(power) \
in this case 123  ->  1*8^(2) + 2*8^(1) + 3*8^(0)  =   83(Digit) \
therefore after running Print Function we will get 83 as an output \

For Eg HEXADECIMAL CONVERSION  \
In this it preceeds with prefix 0x or 0X (zero-x) \
print(0x123) \
in hexadecimal we multiply with power of 12 here -> 1 * 12^(2) + 2 * 12^(1) + 3 * 12^(0)  =  291(decimal output)


# FLOATS
for showing Float it is necessory to show the value with a point for eg. 4.0 is a float \
in float we can write for eg: \
speedoflight= 3x10^(8) \
so in python we can write this as 3E8 \
where E or e is exponent and in python it shows "phrase times ten to the power of"  \
so by using it we can write \
speedoflight = 3E8  \
one more eg: we can write 6.62607 x 10^(-34)  as  6.62607E-34  \

# STRINGS
In strings we know that we use quotes inside print function to show the string but there is a catch \
what if we wanna show Quotes inside strings  \
we can use '\' this is called backslash Adding \" forces Python to print an actual quotation mark on the screen instead of closing the string. \
eg: Show (I like "Monty Python") this as output give input  \
print("I like \"Monty Python\"")  \
or  \
print('I like "Monty Python"') <-- here we can add single quotes also  \
we can use \ to show the ' and " inside the apostrophes and quotes \

# BOOLEAN VALUES
they are the two constant objects True and False; \
where 1 is True and 0 is False