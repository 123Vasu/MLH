# MLH
<br> 
<br>
# Importing the random module:
<br> 
This line of code imports the random module from the Python standard library. The random module provides various functions and methods for generating random numbers and working with randomness in Python.
<br>
# Defining the generate_random_number function:
<br>
This code snippet defines a function named generate_random_number. Inside the function, random.randint(1, 100) is used to generate a random integer between 1 and 100 (inclusive). The randint function takes two arguments: the lower bound (1 in this case) and the upper bound (100 in this case), and it returns a random integer within that range.
<br> 
# Executing the function and storing the result:
<br>
The if __name__ == "__main__": block is executed when the script is run as the main module. Inside this block, generate_random_number() is called, and the resulting random number is assigned to the variable random_number. The purpose of this block is to ensure that the code inside it is only executed when the script is run directly and not when it is imported as a module.
<br> 
# Printing the random number:
<br> 
Finally, the code uses the print() function to display the generated random number on the console. The string "Random Number:" is concatenated with the value of random_number using a comma to separate them in the print statement.
