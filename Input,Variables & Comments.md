# VARIABLE    
A variable is a named location reserved to store values in the memory. A variable is created or initialized automatically when you assign a value to it for the first time. (2.1.4.1)    
    
Each variable must have a unique name ‒ an identifier. A legal identifier name must be a non-empty sequence of characters, must begin with the underscore(_), or a letter, and it cannot be a Python keyword. The first character may be followed by underscores, letters, and digits. Identifiers in Python are case-sensitive.    
    
Python is a dynamically-typed language, which means you don't need to declare variables in it. (2.1.4.3) To assign values to variables, you can use a simple assignment operator in the form of the equal (=) sign, i.e., var = 1.    
    
You can also use compound assignment operators (shortcut operators) to modify values assigned to variables, for example: var += 1, or var /= 5 * 2.    
    
You can assign new values to already existing variables using the assignment operator or one of the compound operators, for example:    
    
# COMMENTS    
-> Comments can be used to leave additional information in code. They are omitted at runtime. The information left in the source code is addressed to human readers. In Python, a comment is a piece of text that begins with #. The comment extends to the end of the line.    
    
-> Whenever possible and justified, you should give self-commenting names to variables, e.g., if you're using two variables to store the length and width of something, the variable names length and width may be a better choice than myvar1 and myvar2    
  
# INPUT(INTERACTION WITH USER)  
  
 The print() function sends data to the console, while the input() function gets data from the console.  
  
 The input() function comes with an optional parameter: the prompt string. It allows you to write a message before the user input, e.g.:  
  
  
name = input("Enter your name: ")  
print("Hello, " + name + ". Nice to meet you!")  
   
When the input() function is called, the program's flow is stopped, the prompt symbol keeps blinking (it prompts the user to take action when the console is switched to input mode) until the user has entered an input and/or pressed the Enter key.  
  
  Note    
You can test the functionality of the input() function in its full scope locally on your machine. For resource optimization reasons, we have limited the maximum program execution time in Edube to a few seconds. Go to the Sandbox, copy-paste the above snippet, run the program, and do nothing ‒ just wait a few seconds to see what happens. Your program should be stopped automatically after a short moment. Now open IDLE, and run the same program there ‒ can you see the difference?  
  
Tip: the above-mentioned feature of the input() function can be used to prompt the user to end a program. Look at the code below:  
  
  
name = input("Enter your name: ")  
print("Hello, " + name + ". Nice to meet you!")  
   
print("\nPress Enter to end the program.")  
input()  
print("THE END.")  
   
The result of the input() function is a string. You can add strings to each other using the concatenation (+) operator. Check out this code:  
  
  
num_1 = input("Enter the first number: ") # Enter 12  
num_2 = input("Enter the second number: ") # Enter 21  
   
print(num_1 + num_2) # the program returns 1221  
   
You can also multiply (* ‒ replication) strings, e.g.:  
  
  
my_input = input("Enter something: ") # Example input: hello  
print(my_input * 3) # Expected output: hellohellohello  