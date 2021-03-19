# Excercise 18

Java OOPS..
- Understand Polymorphism and also understand what are the type of polymorphism.
- Here we are going to solve a problem on method overriding.
- First understand the difference between overloading vs overriding.
- Understand what is Compile time polymorphism and Runtime polymorphism and how it differs.
- Understand what is dynamic dispatch.
- Also understand how access specifier used in this context of method overriding and its implications. 
- Understand Boxing and Autoboxing concepts.

## Some basic definitions in OOPS world:

* Methods - Functions inside the class
* Members or data members - Variables inside the class

## Problem definition:

    
### Note
- Feel free use the previous exercise code with modifications.
- The Implementation should be multilevel inheritance problem in a particular order:
- - Multiply =>(Implements)ScalarMultiply => (Extends)VectorMultiply => (Extends)MatrixMultiply
- Override the methods process() and display()

### Interface(Multiply)
- Create a interface called Multiply with following methods declared:
- - Object process(Object,Object)
- - void display(Object)

### Class(ScalarMultiply)
- Create class named ScalarMultiply with below methods overrided from Multiply
- Object process(Object,Object) - For scalar multiplication.
- void display(Object)
- - Example output(Separated by tab or \t) => [ 3 ]

### Class(VectorMultiply)
- Create class named VectorMultiply with below methods overrided from ScalarMultiply
- Object process(Object,Object) - For vector multiplication use <a href="https://ml-cheatsheet.readthedocs.io/en/latest/linear_algebra.html#hadamard-product">Hadamard product or element wise multiplication</a>.Important note check if dimensions are same for the two input and process else raise UserDefined exception.
- void display(Object)
- - Example output(Separated by tab or \t) => [ 1 2 3 ]

### Class(MatrixMultiply)
- Create class named MatrixMultiply with below methods overrided from VectorMultiply
- Object process(Object,Oject) - For matrix multiplication use <a href="https://ml-cheatsheet.readthedocs.io/en/latest/linear_algebra.html#id6">Hadamard product or element wise multiplication</a>. Important note check if dimensions are same for the two input and process else raise UserDefined exception.
- void display(Object)
- - Example output(Separated by tab or \t) =>
- - [ [ 1 2 3 ]
- - [ 4 5 6 ]
- - [ 7 8 9 ] ]

## Note
Fill the array or list using random number generator function between range of 1 to 100 from random number generator package


