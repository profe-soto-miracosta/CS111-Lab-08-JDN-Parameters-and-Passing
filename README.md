 

# Lab 08: JDN - Parameters + Passing

## Learning Objectives
- Demonstrate an understanding of how to design flexible, maintainable, reusable static methods
- Demonstrate effective industry-standard code documentation.

## Program Description
**Perform Julian Day calculations within a static method.**
Take a moment to think about the method you are designing, without clear and concise documentation, we have only the java code itself. Unless you wrote the code yourself, it would be hard for another programmer to use in collaboration. When filling in the documentation, carefully document the description, preconditions, and postconditions. 

## Definitions

- Julian Day Number: https://en.wikipedia.org/wiki/Julian_day
- Check your work with, http://numerical.recipes/julian.html (make sure to select "Auto (Julian/Gregorian)" calendar option).

## Specifications
1. Take the prototype you built from _Lab 03: DACA + DATA MANIPULATION_
2. Separate out the code to develop a static method named `calculateJDN` with parameters for `monthToday`, `dayToday`, and `yearToday`.

Uncomment the code for the output section and the method header for `calcJulianDate()` in the lab to begin.


## Test
The lab contains a test for your method, passing in Katherine Johnson's birthday and comparing your methods return to the expected return value. Refer to the definitions section to check your work.

Katherine Johnson's birthday, 8/26/1918, has a JDN 2421832.

When you are finished, **add more two method calls in main, to calculate two more Julian dates of your choosing.** (Do your birthday or the day we landed on the moon, etc, whatever you would like) 

Once you've done that submit your code.

## HACKER CHALLENGE

### Create a `printCentered` method

Create a static method that takes in two parameters: width and a string containing text to be printed in the center of the console.

In _Lab 05 DACA + DATA_, you were exposed to a `String` method called `String.format()`. In Order to complete this hacker challenge, you will need to make use of another `String` method called `length()`, _this is your hint on how to center your text regardless of what strings you pass in as a parameter._ 

**Note** `length()` is a non-static method. To use this method, you must call it on a string variable. This is a different way to call a method than we are used to. For example,

```
String greeting = "Hello";
int size = greeting.length(); //for this example, size would store 5
```

Use what you have learned about parameters and passing, along with format specifiers to build a method to center your text _auto-magically_! (from now on, whenever you need formatted text, you now know how to create a method that does it for you, convenient!)

Here is the documentation of `length()` you can use to aid you in building your method: 

```
/**
* Returns the length of a string.
*
* @param: none
* @return an integer, the length of the string in Unicode characters.
**/
```