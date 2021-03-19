# Excercise 19

Java OOPS..
- Understand concepts of constructors and it types.
- Understand fundamental concepts of Java arrays.
- Understand getter and setter methods.
- Understand Exceptions

## Some basic definitions in OOPS world:

* Methods - Functions inside the class
* Members or data members - Variables inside the class

## Problem definition:

- We know Java arrays are static in size after initialization. So we are going to create a dynamic array class which is going to grow or shrink according to the size and capacity of the array. The best alternative for this problem is List. But we are not going to use any collection libraries. So solve this problem without any packages.

- **Statement:** Create a class called DynamicArray which solves the above problem definition.


### Details

-Lets give a try to one of the important algorithms.
- Create a class DynamicArray for this problem only for integer array.
- Object initialization should be able to accept different kind of arguments such as blank, (int)capacity , (float)growth_factor, (float)empty_factor
- Try to include different type of parameterized constructors for this problem.
- int capacity - Determines the size of the array.
- float growth_factor - how much size the new array should take.
- float empty_factor - when to shrink the size of the array.
- Use getters and setter functions to set and get values of parameter variables(capacity(int) , growth_factor(float), empty_factor(float)) apart from the constructor initialization.
- int[] getArray() - return the array.
- add(int) - add new value to the array.
- void grow(int[]) - grow-th function should call every time new element added into the array check if the max capacity is reached or not if yes use the increase size of the array.
- delete_first() - remove the first element of the array ,replace the first element with '0',shift left the whole array for one step left and update the affected varibles.
- delete_last() - remove the last element of the array,update the affected variables.
- delete(int index) - replace the index variable with zero,do a left  shift for the rest of the right side element from index position and update the affected variables.
- void shrink() - shrink function to the check size of the array with respect to capacity of the array check with the empty factor if it is greater ,then reduce size of the array. If the index is out of bounds raise a user defined exception meaningful information.
- You can add your methods and data members with your own  without affecting the logic.

### Note

- More reference check table doubling algorithm.
- https://www.youtube.com/watch?v=BRO7mVIFt08





