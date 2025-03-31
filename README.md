# Cat2
this is cat 2 file
# Java Programs Explanation
The programming concepts in this document are abstraction, method overloading, exception handling, and encapsulation.


## The cat Answers 
# Question 1A
### 1. Student.java
**Concepts:** This demonstrates Encapsulation, Getters, and Setters  
- defines a `Student` class with private attributes `name` and `grade`.  
- Uses **getters and setters** to control access to private attributes.  
- Ensures the grade value remains within a valid range (0-100).


## Question 1B
### 2. Main.java
**Concepts:** Method Overloading, Polymorphism (Method Overriding)  
- Contains a `MathOperations` class demonstrating **method overloading** with multiple `multiply()` methods.  
- Includes an `Animal` class with a `makeSound()` method, overridden in the `Dog` and `Cat` subclasses.  
- Demonstrates **runtime polymorphism** by calling overridden methods dynamically.
 
## Question 2A
### 3. TestAppliance.java
**Concepts:** Abstraction (Abstract Classes)  
- Implements an abstract class `Appliance` with an abstract method `turnOn()`.  
- Subclasses `Fan` and `TV` provide specific implementations of `turnOn()`.  
- Demonstrates **abstraction** by enforcing method implementation in child classes.
- 
## Question 2B
### 4. DivisionExample.java
**Concepts:** Exception Handling, User Input  
- This program takes two integers from the user and divides them.  
- It handles the `ArithmeticException` to prevent division by zero.  
- Uses a `Scanner` object to take user input.   

## How to Run the Programs
1. Compile the files using `javac <filename>.java`.  
2. Run the compiled class using `java <classname>`.  
3. Example:  
   ```sh
   javac Main.java
   java Main
