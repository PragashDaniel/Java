# Excercise 27

Java Comparator & Comparable:
- Understand Java Comparators.
- Understand Java Comparable.  
- Understand POJO classes in java and also getter, setter methods.

## Some basic definitions in OOPS world:

* Methods - Functions inside the class
* Members or data members - Variables inside the class

## Problem definition:

- Create a POJO class called Employee with a following members name[String] , Salary[Integer]. The values should be assigned only through appropriate setter methods and also the Employee method should have getter methods and toString methods.
- Also Employee class should implements Comparable interface and should be implemented to do the Comparing process on salary field of the Employee class in descending order.  
- Create a list of ten employees,name of the employee should be assigned using exercise 20 random name generator function and length of the name should be variable length from the range of 5 to 15 characters of length and  salary should be assigned randomly between the value of  10,000 - 1,00,000.
- Create class called NameLengthSort implements Comparator which sorts Employee list on ascending order based on length of the name.
- Using streams and sort the Employee list using comparable of Employee class and print both name and salary of the Employee on the same stream statement.
- Using Collections,sort() sort the Employee list using NameLengthSort comparator.
