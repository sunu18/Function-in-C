# Function-in-C

In C programming, a function is a block of code that performs a specific task. Functions are essential in breaking down large programs into smaller, more manageable code units that can be reused in different parts of the program.

To define a function in C, we use the syntax: returnType functionName(parameter1, parameter2, ...) {function body}. Here, returnType is the data type of the value that the function returns, functionName is the name of the function, and parameter1, parameter2, etc. are input parameters of the function.

The function body, enclosed in curly braces {}, contains the code that performs the function's task, and the return statement at the end of the function returns the function's result to the calling program.

As an example, consider a function that calculates the square of an integer input parameter. This function can be defined as follows:

![image](https://user-images.githubusercontent.com/91204160/230775937-f7b9a5aa-3f71-4e3d-bbfd-b0c7ebc41bb6.png)

The function takes an integer num as input, calculates its square, and returns the result as an integer.

To use a function in C, we call it by its name and pass the required parameters. For instance, if x is an integer, then we can call the square() function to calculate its square and assign the result to a variable y like this:

![image](https://user-images.githubusercontent.com/91204160/230775964-e585fe19-1a62-47c7-bea5-982dfdf46b93.png)

Here, square() is called with the integer parameter x, and its return value is assigned to the integer variable y.
