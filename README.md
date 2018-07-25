# Java_Method_Practice

For the exercises below only create the function call in the main, the function declaration, and any returns if necessary. If no return is necessary enter NONE
### Example 1
Create a function that’s passed three numbers and returns the sum

Main

* ```newFunction(number1, number2, number3);```

Function Declaration

* ```public static int newFunction(int num1, int num2, int num3){```

Function Return

* ```return (num1 + num2 + num3)```

### Example 2
Create a function that’s passed four names and returns an array of those names

Main

* ```newFunction (name1, name2, name3, name4);```

Function Header

* ```Public static ArrayList<String> newFunction (String name1, String name2, String name3, String name4){```

Function Return

* ```return newArray```

## Exercises
1. Create a function that’s passed two numbers and prints the sum.

Main: newFunction (number1, number2);
Function Header: public static void newFunction (int number1, int number2){
Return: NONE

2. Create a function that’s passed [NAME] and prints Hello [NAME].

Main: newFunction(name);
Function Header: public static void newFunction(String name){
Return: NONE

3. Create a function that’s passed a firstName and lastName. Return lastName comma firstName.

Main: newFunction(lastName, firstName);
FH: public static String newFunction(String lastName, String firstName)
result = lastName + " , " + firstName;
Return: result

4. Create a function that’s passed a name and the number of times a user wants to print Hello [NAME]. Print Hello [NAME] that many times in the function.

Main: newFunction(name, numberOfTimes);
FH: public static void newFunction(String name, int numberOfTimes){
Return: NONE

5. Create a function that’s passed two numbers and if the user wants to add, subtract, multiply, or divide. Return the result.

Main: newFunction (num1, num2, mathOption)
FH: public static int newFunction (int number1, int number2, String mathOption){
Return: result

6. Create a function that’s passed an array of names and prints each item on a different line.

Main: newFunction(arrayNames)
FH: public static void newFunction(ArrayList<String> arrayNames){
Return: NONE

7. Create a function that’s passed an array of names and a number that returns the item at the index of that number.

Main: newFunction(arrayName, userInput)
FH: public static int newFunction(ArrayList<String> nameArray, int returnItemIndex){
Return: nameArray.get(returnItemIndex)

8. Create a function that’s passed two numbers and returns the sum. Create another function that takes the sum of that function and prints “The sum is [SUM]“
Main: newFunction(
FH:
Return: 
9. Create a function that’s passed two numbers and returns the sum. Create another function that takes the sum of that function and returns “The sum is [SUM]“
10. Create a function that’s passed two names and returns an Array. Create another function that’s passed two integers and returns the difference. Create a third function that’s passed an integer array and prints it.


**EXTRA CREDIT:**
Create the entire program. Create a function that’s passed two numbers and ask if the user wants to add, subtract, multiply, or divide. Return a string that prints the two numbers, which operation it did, and the result.
