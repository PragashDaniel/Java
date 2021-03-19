# Excercise 15

Java OOPS..

- Especially Abstract Classes 
- Understand the difference between interface and abstract class.
- Understand about abstract methods and final methods


## Some basic definitions in OOPS world:

* Methods - Functions inside the class
* Members or data members - Variables inside the class

## Problem definition:

- Goal is create a class to implement complex number addition ,complex number subtraction and complex number multiplication.
- Create a class called ComplexNumber should have only two data members with type float and name should be real and imaginary. Also the class should implement toString method which should meaningfully return the real and imaginary part with **"i"** as a single string.   
- Abstract class Name it as Arithmetic class with following methods.
- - final float add(float,float)
- - final float sub(float,float)
- - final float mul(float,float)
- - abstract void display(ComplexNumber)
- Create a derived class called FractionArith from Arithmetic class must have following methods.
- -  ComplexNumber complexAdd(ComplexNumber,ComplexNumber) =>Internal arithmetic functionality should be extended from the base class Arithmetic.(All arithmetic operation should be implemented by methods)
- -  ComplexNumber complexSub(ComplexNumber,ComplexNumber) =>Internal arithmetic functionality should be extended from the base class Arithmetic.(All arithmetic operation should be implemented by methods)
- -  ComplexNumber complexMul(ComplexNumber,ComplexNumber) =>Internal arithmetic functionality should be extended from the base class Arithmetic.(All arithmetic operation should be implemented by methods)
- -  void display(ComplexNumber)



