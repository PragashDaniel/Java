# Excercise 16

## Sage who can predict your personality

Java OOPS.. 

- Just fun exercise to create a tool who predict your personality based on your name and your favorite number.
- Deploy the tool as a jar, which interact with user meaningfully in the command line. So software should be user friendly in the command line.
- Reference for personality types: https://www.16personalities.com/personality-types; Here you can get 16 different personality based on this the tool should predict person's personality.
- Programming constraint: the code should have a Do-While loop and switch-case statement.
- Logic should be implemented using class and its methods


## Some basic definitions in OOPS world:

* Methods - Functions inside the class
* Members or data members - Variables inside the class

## Problem definition:

- Goal is create a class **Sage** to predict user's personality.
- class Sage should have a method predictPersonality, implemented as below:
- - String predictPersonality(String person_name,Integer favorite_number)
- - should implement a switch case statement to map the information with personality.
- class Sage should have a method personNameToNumber implemented as below:
- - Integer personNameToNumber(String person_name)
- - User your own logic to convert String to Numbers but it should utilise all characters in the string.
- - Use this helper function inside predictPersonality method to convert string  to number.
    
- main function should have a Do-While loop where this process needs to run infinitely and at every iteration you need to ask the user whether he or she should want to continue or not.If not then break the loop and exit the tool.
- Don't forget the tool should be interactive and user friendly, Though it is a command line one.



