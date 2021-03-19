# Excercise 17

Java OOPS..
- Understand Polymorphism and also understand what are the type of polymorphism.
- Here we are going to solve a problem on method overloading.

## Some basic definitions in OOPS world:

* Methods - Functions inside the class
* Members or data members - Variables inside the class

## Problem definition:

- Create a class called Multiply

- Overload the method in the name process()
- Integer process(Integer,Integer) - For scalar multiplication.
- Integer[] process(Integer[],Integer[]) - For vector multiplication use <a href="https://ml-cheatsheet.readthedocs.io/en/latest/linear_algebra.html#hadamard-product">Hadamard product or element wise multiplication</a>.Important note check if dimensions are same for the two input and process else raise UserDefined exception.
- Integer[][] process(Integer[][],Integer[][]) - For matrix multiplication use <a href="https://ml-cheatsheet.readthedocs.io/en/latest/linear_algebra.html#id6">Hadamard product or element wise multiplication</a>. Important note check if dimensions are same for the two input and process else raise UserDefined exception.
- Same way print the result using overload method in the name display()
- void display(Integer) 
- - Example output(Separated by tab or \t) => [ 3 ] 
- void display(Integer [])
- - Example output(Separated by tab or \t) => [ 1 2 3 ]
- void display(Integer[][])
- - Example output(Separated by tab or \t) =>
- - [ [ 1 2 3 ]   
- - [ 4 5 6 ]
- - [ 7 8 9 ] ]
## Note
Fill the array or list using random number generator function between range of 1 to 100 from random number generator package


