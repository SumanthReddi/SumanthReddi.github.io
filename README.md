
# Introduction
### What is programming?
Programming is the art and science of **instructing computers** to perform specific tasks.
It involves writing sets of instructions, known as <mark>code</mark>, using programming languages such as **Java**, **Python** or **C++**. 
These instructions tell the computer what to do and how to do it.

import javaimg from '../img/java.png'

### java 
> Java is a high-level, general-purpose programming language that was developed by Sun Microsystems (now owned by **Oracle**) in the mid-**1990s**. It is known for its simplicity, platform independence, and robustness.

### Learning Java as your first programming language can be a good choice for several reasons:

**Popularity and Versatility**: Java is one of the most popular programming languages in the world, widely used in various domains such as web development, mobile app development (Android), enterprise software, scientific applications, and more. Learning Java opens up a wide range of opportunities and increases your chances of finding job opportunities.

**Object-Oriented Programming (OOP):** Java is a strongly object-oriented language, which means it emphasizes organizing code into reusable objects. Learning Java helps you understand essential OOP concepts such as encapsulation, inheritance, and polymorphism. These concepts are fundamental to many other programming languages, making it easier to learn and transition to them later.

**Rich Standard Library:** Java comes with a vast standard library that provides pre-built classes and functions to perform various tasks. This library covers areas like input/output, networking, database connectivity, and more. By learning Java, you gain exposure to these library components, which can save you time and effort when developing applications.

**Community and Resources:** Java has a large and active community of developers, which means there are abundant learning resources, tutorials, forums, and libraries available to support your learning journey. You can find extensive documentation, books, online courses, and community forums where you can ask questions and get help when needed.

**Strong Language Design:** Java has a well-designed syntax and strict rules, which helps in building robust and reliable software. Learning Java encourages good programming practices such as type safety, exception handling, and memory management. These concepts are transferable to other languages and contribute to writing cleaner and more maintainable code.

**Job Market Demand:** Java skills are highly sought after by employers. Many companies use Java in their tech stacks, and having Java expertise on your resume can make you more marketable and increase your job prospects.


# Java vs Core Java
Java is the broader programming language, while Core Java focuses on the fundamental concepts and constructs within Java.

![img](../img/Corejava.jpeg)


# Learning Path
- Start with Basics 
- Mini programs
- data structures
- Practice and Mini-Projects:

# Resources Required

>start with Jshell (Simple Java CLI )

>Later using Eclipse IDE 

>Then Maven integration

# Variables  

import withoutvar from '../img/withoutvar.png'
import withvar from '../img/withvar.png'

### What is a variable in java?
- Variables are named **containers** used to **store data** in Java programs. 
- They act as placeholders that can hold different types of values, such as <code> numbers</code>, <code>characters</code>, or <code>boolean</code> values. 
- In Java, variables are declared with a specific type and can be assigned values, updated, and used throughout the program.

### Declaration and Initialization

To declare a variable in Java, you need to specify its type followed by the variable name. You can also initialize the variable with an initial value at the time of declaration. Here's the general syntax:

```java
type variableName = initialValue;
```
For example, to declare an integer variable named age and assign it an initial value of 25, you can write:

```java
int age = 25;
```
### Variable Naming

When naming variables, you need to follow certain rules and conventions:

- The name should start with a letter (a-z or A-Z) or an underscore (_).
- The name can contain letters, digits, and underscores.
- Java is case-sensitive, so **myVariable** and **myvariable** are considered different variables.
- Choose **meaningful** and **descriptive** names that indicate the purpose of the variable.

### Variable usage
```java
int x = 5;
int y = 3;
int sum = x + y;
```

In this example, we declare and initialize two integer variables **x** and **y**. We then create a third variable sum and assign it the value of **x + y**. The value of sum would be **8**.

# Data Types 
- Data types in Java specify the **type of data** that can be stored in variables. 
- They define the **range of values** and the operations that can be performed on the data. 

import wallet from '../img/wallet.jpeg'
import cutlery from '../img/cutlery.png'
import shapeGame from '../img/shapeGame.png'
import containers from '../img/containers.jpeg'
import docs from '../img/docs.png'

<p align="center">
  <img src={containers} alt="Image" width="450" height="auto"/>
</p>

- Java has two main categories of data types: **1)**primitive **2** non-primitive/referenced




### Primitive Data Types
- Predefined memory allocation
- Can hold only one value

> In the below example, match objects to shapes, there is a specific pre-defined placehlder for storing an object,
if you try to other object, it does not fit.
<p align="center">
  <img src={shapeGame} alt="Image" width="450" height="auto"/>
</p>


 | Data Type | Size &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| Description |
: --- :|: --- :|: --- |
| byte | 1 byte | Stores whole numbers from -128 to 127 |
| short | 2 bytes | Stores whole numbers from -32,768 to 32,767 |
| int | 4 bytes | Stores whole numbers from -2,147,483,648 to 2,147,483,647 |
| long | 8 bytes | Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
| float | 4 bytes | Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits |
| double | 8 bytes | Stores fractional numbers. Sufficient for storing 15 decimal digits |
| boolean | 1 bit | Stores true or false values |
| char | 2 bytes | Stores a single character/letter or ASCII values |

Ex:
```java
byte myAge = 32;               // (whole number between -128 to 127)
short mySal = 30000;           // (whole number between -32,768 to 32,767)
int myPincode = 516520;        // (whole number -2,147,483,648 to 2,147,483,647)
long myAcc = 9934934739847134l; //whole number -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807)
float myTemp = 98.85f;         // (decimal number with 6-7 decimal points)
double myStockValue=67.13412343d   // (decimal number with upto 15 decimal points)
char myLetter = 'D';           // (Single character)
boolean isDelivered = true;       // (Store true or false)
```

## Data Type Promotion in Java :

![data type promotion small](https://user-images.githubusercontent.com/2780145/34364362-403e9db4-eaab-11e7-914b-7acc9007cf41.png)

### Non-Primitive Data Types

- Dynamic memory allocation 

> Docs are dynamic, they can store text, images, videos and pages will be dynamically appended hence the size
will vary based on the content


Examples of Non-Primitive Data Types
- **String:** Represents a sequence of characters.
- **Arrays:** Represents a collection of elements of the same type.
- **Classes:** Represents user-defined types.

Ex: 
```java
String myText = "Hello";     // String
```

Java Operators
--------------

Operators in Java are special symbols or keywords used to perform operations on operands. They allow you to manipulate values, perform calculations, compare values, and more. Java provides a wide range of operators, including `arithmetic, assignment, comparison, logical, and ternary` operators.

### Assignment Operators

Assignment operators are used to assign values to variables. They combine the assignment (=) operator with arithmetic or other operators. Here's an example of an assignment operator:

*   **`=` (assignment)**: Assigns the value on the right to the variable on the left.
```java
jshell> int x=10;
x ==> 10

jshell> boolean isOrdered=true, isDelevered=false;
isOrdered ==> true
isDelevered ==> false

```

### Arithmetic Operators

Arithmetic operators are used to perform basic mathematical operations, such as addition, subtraction, multiplication, division, and modulus (remainder). Here are some examples of arithmetic operators:

*  ** `+` (addition)**: Adds two values together. 
```java 
jshell> int x=10, y=20;
x ==> 10
y ==> 20

jshell> int sum=x+y;
sum ==> 30  
```
*   ** `-` (subtraction)**: Subtracts one value from another.
```java
jshell> int x=10,y=5;
x ==> 10
y ==> 5

jshell> int subtraction=x-y;
subtraction ==> 5
```
*   **`*` (multiplication)**: Multiplies two values.
```java
jshell> int x=10,y=5,z=2;
x ==> 10
y ==> 5
z ==> 2

jshell> int result=x*y*z;
result ==> 100
```
*   ** `/` (division)**: Divides one value by another.
```java
jshell> int x=25,y=5;
x ==> 25
y ==> 5

jshell> int result=x/y;
result ==> 5
```
*   ** `%` (modulus)**: Returns the remainder of a division.
```java
jshell> int x=27,y=5;
x ==> 27
y ==> 5

jshell> int result=x%y;
result ==> 2
``` 

### Comparison Operators

Comparison operators are used to compare two values and determine their relationship. They return a boolean value (`true` or `false`) based on the comparison result. Here are some examples of comparison operators:

*   **`==` (equality)**: Checks if two values are equal.
```java
jshell> int x=25,y=30;
x ==> 25
y ==> 30

jshell> x==y
$23 ==> false
```
*   **`!=` (inequality)**: Checks if two values are not equal.
```java
jshell> int x=25,y=30;
x ==> 25
y ==> 30

jshell> x!=y
$24 ==> true
```
*   **`>` (greater than)**: Checks if the value on the left is greater than the value on the right.
```java
jshell> int x=25,y=30;
x ==> 25
y ==> 30

jshell> x>y
$25 ==> false
```
*   **`<` (less than)**: Checks if the value on the left is less than the value on the right.
```java
jshell> int x=25,y=30;
x ==> 25
y ==> 30

jshell> x<y
$26 ==> true
```
*   **`>=` (greater than or equal to)**: Checks if the value on the left is greater than or equal to the value on the right.
```java
jshell> int x=30,y=30;
x ==> 30
y ==> 30

jshell> x>=y
$27 ==> true
```
*   **`<=` (less than or equal to)**: Checks if the value on the left is less than or equal to the value on the right.
```java
jshell> int x=3,y=30;
x ==> 3
y ==> 30

jshell> x<=y
$24 ==> true
```
### Logical Operators

Logical operators are used to perform logical operations on boolean values. They combine multiple conditions and determine the final boolean result. Here are some examples of logical operators:

*   `&&` (logical AND): Returns `true` if both conditions are `true`.
```java
jshell> boolean isOrdered=true, isDelivered=false;
isOrdered ==> true
isDelivered ==> false

jshell> boolean isOrderComplete= isOrdered && isDelivered;
isOrderComplete ==> false
```
*   `||` (logical OR): Returns `true` if at least one condition is `true`.
```java

jshell> boolean jumpedSignal=true;
jumpedSignal ==> true

jshell> int speed=40;
speed ==> 40

jshell> boolean penalty= (speed >80) || (jumpedSignal==true)
penalty ==> true
```
*   `!` (logical NOT): Negates a boolean value.
```java
jshell> boolean lightOn=true;
lightOn ==> true

jshell> !lightOn
$38 ==> false
```


### Ternary Operator

The ternary operator is a shorthand operator used for conditional expressions. It evaluates a condition and returns one of two values based on the result of the condition. Here's an example of the ternary operator:

`variable = (condition) ? value1 : value2;`
```java
jshell> boolean speedTicket=(speed>80) ? true: false;
speedTicket ==> true
```
In this example, if the speed is > 80 then `true` will be assigned to speedTicket else `false` 

That's a simple explanation of Java operators in markup language. Operators are essential for performing various operations in Java, enabling you to manipulate data, make decisions, and control the flow of your program.

# Control Flow
- Control flow or flow of control is the order in which instructions, statements and function calls being executed or evaluated when a program is running. 
- In Java, control flow statements are used to alter, redirect, or to control the flow of program execution based on the application logic.

# Java Control Flow Statement Types
In Java, Control flow statements are mainly categorized in following types 
- Selection statements
- Iteration statements
- Jump statements

![img](https://w3adda.com/wp-content/uploads/2018/12/java-control-statements-1024x547.jpg)


# Selection statements
- Selection statements first evaluate the expression, if expression outcome  is **TRUE** then it executes one set of instructions, if outcome is **FALSE** then it executes the other instructions.

### Following are the Java Selection Statements
- If Else
- Switch

# If Else Statement

**Syntax:  Just if condition**

```
if(TRUE){
    //runs this code
}
````

Ex: 
```
if(numb%2==0){
    System.out.println("Its a even number");
}
```
- if numb==10 --> then output --> **Its a even number**
- if numb==11 --> then output --> 


**Syntax:  If Else**
```
if(TRUE){
    //runs this code
}else{
    //runs this code
}
````

Ex: 
```
if(numb%2==0){
    System.out.println("Its a even number");
}else{
    System.out.println("Its a odd number");
}
```
- if numb==10 --> then output --> **Its a even number**
- if numb==11 --> then output -->  **Its a odd number**


**Syntax  Nested if condition**
<br />
![img](https://media.geeksforgeeks.org/wp-content/uploads/20191119124152/c-cpp-if-else-if.png)

```
if(Condition1){
    //runs this code
}else if(Condition2){
    //runs this code
}else if(Condition3){
    //runs this code
}else{
    // runs if no codition is true
}
````

Ex: 
```
if(numb%2==0 && numb<20){
    System.out.println("Its a even number and value is less than 20");
}else if(numb%2==0 && numb>20){
    System.out.println("Its a even number and value is greater than 20");
}else if(numb%2!=0 && numb<20){
    System.out.println("Its a odd number and value is less than 20");
}else{
    System.out.println("Its a odd number and value is greater than 20");
}
```
- if numb==10 --> then output --> **Its a even number and value is less than 20**
- if numb==26 --> then output --> **Its a even number and value is greather than 20**
- if numb==5 --> then output --> **Its a odd number and value is less than 20**
- if numb==25 --> then output --> **Its a odd number and value is greater than 20**


# Switch Statement

-In Java, switch case statement is **simplified** form of the Java **Nested if else statement**
- it helps to avoid long chain of if..else if..else statements. 
- A switch case statement evaluates an expression against multiple cases in order to identify the block of code to be executed.

![img](https://i2.wp.com/techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/03/switch-statement-in-java.jpg?ssl=1)

Ex:
```java
int day = 5;
    switch (day) {
    case 1:
      System.out.println("Monday");
      break;
    case 2:
      System.out.println("Tuesday");
      break;
    case 3:
      System.out.println("Wednesday");
      break;
    case 4:
      System.out.println("Thursday");
      break;
    case 5:
      System.out.println("Friday");
      break;
    case 6:
      System.out.println("Saturday");
      break;
    case 7:
      System.out.println("Sunday");
      break;
    default:
      System.out.println("Invalid");
    }
```

# Iteration statements
- In Java, Iteration statements are used to **execute the block of code repeatedly** for a specified number of times or until it meets a specified condition. 
- Iteration statements are commonly known as **loops or looping statements**.

## Types of Iteration Statements
- while loop
- do while loop
- for loop

### While loop
- while loop is just like if statement but it will repeatedly executing till the condition becomes **FALSE**

**Syntax**
```
while (condition){    
//code to be executed   
Increment / decrement statement  
}    
```

Ex:
```
int x=1;
while (x<=100){    
System.out.println(x);
x++; 
}    
```

### do while
- Unlike while, The do…while loop executes block of statements inside loop body first and then test the condition for next iteration and executes next only if condition is true.
- do...while executes atleast once irrespective of condition is true or false

**Syntax**
```
do{
    // loop body
} while(condition);
```

Ex:
```
    int i=1;    
    do{    
        System.out.println(i);    
    i++;    
    }while(i<=10);    
} 
```


### for loop
- Use for loop when you know when the loop should end
**Use case**: Write numbers from 1 to 100
here we know that we have to continuously write the numbers untill 100, hence the loop must end 100th time

**Syntax:**

```
for(Initialization; Condition; incr/decr){
	// loop body
}
```

Ex:
```
for(int i=1; i<=100; i++){
	System.out.println(i);
}
```

# Java Break Statement
- In Java, break statement inside any loop gives you way to break or **terminate the execution of loop** containing it, 
- And transfers the execution to the next statement following the loop.

Syntax:
```
break;
```

Example:
```

 
        int count = 0;
        
        System.out.println("Java Break Statement");
        while(count <= 10){
        count = count + 1;
        if(count == 5){
            break;
        }
        System.out.println("Inside loop "+count);
        }
        System.out.println("Out of while loop");
 
```

# Continue
- Contiue statement does not terminate the loop, but it will skip that specific iteration and transfer the control to the start of the loop

Syntax: 
```
continue;
```

Ex:
```
public class Main
{
	public static void main(String[] args) {

        int ctr = 0;
    
        System.out.println("Java Continue Statement");
        while(ctr < 10){
            ctr = ctr + 1;
            if(ctr == 5){
                System.out.println("5 is skipped");
                continue;
            }
            System.out.println("Number is "+ctr);
        }
        System.out.println("Out of while loop");

	}
}
```

# String Class
import ExpOne from '../../../../modules/ExpOne'
import Equals from '../../../../modules/ExpOne/Equals'
import EqualsIgnoreCase from '../../../../modules/ExpOne/EqualsIgnoreCase'
import Contains from '../../../../modules/ExpOne/Contains'
import Length from '../../../../modules/ExpOne/Length'
import Replace from '../../../../modules/ExpOne/Replace'
import ToUpper from '../../../../modules/ExpOne/ToUpper'
import ToLower from '../../../../modules/ExpOne/ToLower'


- String is a **non-primitive** data type, meaning it will not have a pre-defined memory allocation
- byte, short, int, long, float, bouble, boolean were primitive data types,because they have pre-defined memory allocation
- Also, primitive data types will not have any operations but non-primitive data types does have operations implemented
- String objects are **immutable**, meaning it is constant and can cannot be changed once it has been created.

# How to create a String?
- Create using String liternal
    * Ex: String name="OneAuto";
- Create using new keyword
    * Ex: String name = new String("OneAuto");

# String Methods
1.  [char charAt(int index)](https://beginnersbook.com/2013/12/java-string-charat-method-example/ "CharAt"): It returns the character at the specified index. Specified index value should be between 0 to length() -1 both inclusive. It throws IndexOutOfBoundsException if index&lt;0||&gt;= length of String.
2.  [boolean equals(String string)](https://beginnersbook.com/2013/12/java-string-equals-and-equalsignorecase-methods-example/): Compares the string with the specified string and returns true if both matches else false.
3.  [boolean equalsIgnoreCase(String string)](https://beginnersbook.com/2013/12/java-string-equals-and-equalsignorecase-methods-example/): It works same as equals method but it doesn’t consider the case while comparing strings. It does a case insensitive comparison.
4.  [int compareTo(String string)](https://beginnersbook.com/2013/12/java-string-compareto-method-example/ "CompareTo"): This method compares the two strings based on the Unicode value of each character in the strings.
5.  [int compareToIgnoreCase(String string)](https://beginnersbook.com/2013/12/java-string-comparetoignorecase-method-example/): Same as CompareTo method however it ignores the case during comparison.
6.  [boolean startsWith(String prefix, int offset)](https://beginnersbook.com/2013/12/java-string-startswith-method-example/): It checks whether the substring (starting from the specified offset index) is having the specified prefix or not.
7.  [boolean startsWith(String prefix)](https://beginnersbook.com/2013/12/java-string-startswith-method-example/): It tests whether the string is having specified prefix, if yes then it returns true else false.
8.  [boolean endsWith(String suffix)](https://beginnersbook.com/2013/12/java-string-endswith-method-example/ "endsWith"): Checks whether the string ends with the specified suffix.
9.  [int hashCode()](https://beginnersbook.com/2013/12/java-string-trim-and-hashcode-methods/): It returns the hash code of the string.
10. [int indexOf(char ch)](https://beginnersbook.com/2013/12/java-string-indexof-method-example/): Returns the index of first occurrence of the specified character ch in the string.
11. [int indexOf(char ch, int fromIndex)](https://beginnersbook.com/2013/12/java-string-indexof-method-example/): Same as indexOf method however it starts searching in the string from the specified fromIndex.
12. [int lastIndexOf(char ch)](https://beginnersbook.com/2013/12/java-string-lastindexof-method-example/): It returns the last occurrence of the character ch in the string.
13. [int lastIndexOf(char ch, int fromIndex)](https://beginnersbook.com/2013/12/java-string-lastindexof-method-example/): Same as lastIndexOf(char ch) method, it starts search from fromIndex.
14. [int indexOf(String str)](https://beginnersbook.com/2013/12/java-string-indexof-method-example/): This method returns the index of first occurrence of specified substring str.
15. [int lastindexOf(String str)](https://beginnersbook.com/2013/12/java-string-lastindexof-method-example/): Returns the index of last occurrence of string str.
16. [String substring(int beginIndex)](https://beginnersbook.com/2013/12/java-string-substring-method-example/): It returns the substring of the string. The substring starts with the character at the specified index.
17. [String substring(int beginIndex, int venkatndex)](https://beginnersbook.com/2013/12/java-string-substring-method-example/): Returns the substring. The substring starts with character at beginIndex and ends with the character at venkatndex.
18. [String concat(String str)](https://beginnersbook.com/2013/12/java-string-concat-method-example/ "concat"): Concatenates the specified string “str” at the end of the string.
19. [String replace(char oldChar, char newChar)](https://beginnersbook.com/2013/12/java-string-replace-replacefirst-replaceall-method-examples/): It returns the new updated string after changing all the occurrences of oldChar with the newChar.
20. [boolean contains(CharSequence s)](https://beginnersbook.com/2017/10/java-string-contains-method/): It checks whether the string contains the specified sequence of char values. If yes then it returns true else false. It throws NullPointerException of ‘s’ is null.
21. [String toUpperCase(Locale locale)](https://beginnersbook.com/2013/12/java-string-tolowercase-method-example/): Converts the string to upper case string using the rules defined by specified locale.
22. [String toUpperCase()](https://beginnersbook.com/2013/12/java-string-tolowercase-method-example/): Equivalent to toUpperCase(Locale.getDefault()).
23. [public boolean isEmpty()](https://beginnersbook.com/2017/10/java-string-isempty-method-with-example/): This method returns true if the given string has 0 length. If the length of the specified Java String is non-zero then it returns false.
24. [public static String join()](https://beginnersbook.com/2017/10/java-string-join-method/): This method joins the given strings using the specified delimiter and returns the concatenated Java String
25. [String replaceFirst(String regex, String replacement)](https://beginnersbook.com/2013/12/java-string-replace-replacefirst-replaceall-method-examples/): It replaces the first occurrence of substring that fits the given regular expression “regex” with the specified replacement string.
26. [String replaceAll(String regex, String replacement)](https://beginnersbook.com/2013/12/java-string-replace-replacefirst-replaceall-method-examples/): It replaces all the occurrences of substrings that fits the [regular expression regex](https://beginnersbook.com/2014/08/java-regex-tutorial/ "Java Regular Expressions (java regex) Tutorial with examples") with the replacement string.
27. [String\[\] split(String regex, int limit)](https://beginnersbook.com/2013/12/java-string-split-method-example/): It splits the string and returns the array of substrings that matches the given regular expression. limit is a result threshold here.
28. [String\[\] split(String regex)](https://beginnersbook.com/2013/12/java-string-split-method-example/): Same as split(String regex, int limit) method however it does not have any threshold limit.
29. [public static String format()](https://beginnersbook.com/2017/10/java-string-format-method/): This method returns a formatted java String
30. [String toLowerCase()](https://beginnersbook.com/2013/12/java-string-tolowercase-method-example/): Equivalent to toLowerCase(Locale. getDefault()).
31. [String trim()](https://beginnersbook.com/2013/12/java-string-trim-and-hashcode-methods/): Returns the substring after omitting leading and trailing white spaces from the original string.
32. [char\[\] toCharArray()](https://beginnersbook.com/2013/12/java-string-tochararray-method-example/): Converts the string to a character array.
33. [static String copyValueOf(char\[\] data)](https://beginnersbook.com/2013/12/java-string-copyvalueof-method-example/): It returns a string that contains the characters of the specified character array.
34. [static String copyValueOf(char\[\] data, int offset, int count)](https://beginnersbook.com/2013/12/java-string-copyvalueof-method-example/): Same as above method with two extra arguments – initial offset of subarray and length of subarray.
35. [void getChars(int srcBegin, int srcEnd, char\[\] dest, int destBegin)](https://beginnersbook.com/2013/12/java-string-getchars-method-example/): It copies the characters of **src** array to the **dest** array. Only the specified range is being copied(srcBegin to srcEnd) to the dest subarray(starting fromdestBegin).
36. [static String valueOf()](https://beginnersbook.com/2017/10/java-string-valueof-method/): This method returns a string representation of passed arguments such as int, long, float, double, char and char array.
37. [boolean contentEquals(StringBuffer sb)](https://beginnersbook.com/2013/12/java-string-contentequals-method-example/ "contentEquals"): It compares the string to the specified string buffer.
38. [boolean regionMatches(int srcoffset, String dest, int destoffset, int len)](https://beginnersbook.com/2013/12/java-string-regionmatches-method-example/): It compares the substring of input to the substring of specified string.
39. [boolean regionMatches(boolean ignoreCase, int srcoffset, String dest, int destoffset, int len)](https://beginnersbook.com/2013/12/java-string-regionmatches-method-example/): Another variation of regionMatches method with the extra boolean argument to specify whether the comparison is case sensitive or case insensitive.
40. [byte\[\] getBytes(String charsetName)](https://beginnersbook.com/2013/12/java-string-getbytes-method-example/): It converts the String into sequence of bytes using the specified charset encoding and returns the array of resulted bytes.
41. [byte\[\] getBytes()](https://beginnersbook.com/2013/12/java-string-getbytes-method-example/): This method is similar to the above method it just uses the default charset encoding for converting the string into sequence of bytes.
42. [int length()](https://beginnersbook.com/2013/12/java-string-length-method-example/): It returns the length of a String.
  
# Most used String Methods in Automation testing

 :memo: **String Equals()**

Compares the string with the specified string and returns true if both matches else false.
   ```java
  String s1="hello"; 
   String s2="hello"; 
   String s3="hi";
   System.out.println(s1.equals(s2));   // returns true
   System.out.println(s1.equals(s3));   // returns false
```
<Equals></Equals>

 :memo: **String equalsIgnoreCase()**

It works same as equals method but it doesn’t consider the case while comparing strings.
   ```java
   String s1="hello"; 
   String s2="HELLO"; 
   System.out.println(s1.equals(s2));            // returns false
   System.out.println(s1.equalsIgnoreCase(s2));   // returns true
```
<EqualsIgnoreCase></EqualsIgnoreCase>

 :memo: **String contains()**

It checks whether the string contains the specified sequence of char values. If yes then it returns true else false.
   ```java
   String name=" hello how are you doing"; 
   System.out.println(name.contains("how are you"));  // returns true
   System.out.println(name.contains("hello"));        // returns true  
   System.out.println(name.contains("fine"));         // returns false  
```
<Contains></Contains>

 :memo: **String length()**

It returns the length of a String.
   ```java
   String s1="hello"; 
   System.out.println("string length is: "+s1.length()); //returns 5
```
<Length></Length>

 :memo: **String replace()**

It returns the new updated string after changing all the occurrences of oldChar with the newChar.

   ```java
  String s1="hello"; 
   String replaceString=s1.replace('h','t'); //tello
```
<Replace></Replace>

 :memo: **String toUpperCase()**

Converts to Upper Case
   ```java
   String s1="hello";  
   String s1upper=s1.toUpperCase(); //return HELLO
```
<ToUpper></ToUpper>

 :memo: **String toLowerCase()**

Converts to Lower Case

   ```java
   String s1="HELLO";  
   String s1upper=s1.toLowerCase(); //return hello
```
<ToLower></ToLower>

 :memo: **String valueOf()**

It returns a string that contains the characters of the specified character array.
   ```java
   int value=20; 
   String s1=String.valueOf(value); 
   System.out.println(s1+17);       //returns 2017
```

 :memo: **String trim()**

Returns the substring after omitting leading and trailing white spaces from the original string.

   ```java
   String s1="  hello   ";  
   s1.length();        //return 10
   s1=s1.trim();
   s1.length();       //returns 5
```

 :memo: **String Concat()**
 
Concatenates the specified string “str” at the end of the string.
```java
String s1="hello";
String s2=" how are you";
s1=s1.concat(s2); //returns "hello how are you"
```
<ExpOne></ExpOne>

 :memo: **String toCharArray()**
 
Converts the string to a character array.
```java
  String s1="Welcome";
   char[] ch=s1.toCharArray(); //returns {}'W','e','l','c','o','m','e'}
```
 :memo: **String split()**
 
It splits the string and returns the array of substrings that matches the given regular expression
```java
  String s1="Wel-come";
   String[] ch=s1.split("-"); //returns {}"Wel", "come"}
```
 :memo: **String endsWith()**
 
It checks whether the substring is having the specified postfix or not.

```java
  String s1="Welcome";
  s1.endsWith("me"); //returns true
  s1.endsWith("mo"); //returns false
```
 :memo: **String startsWith()**

It checks whether the substring is having the specified prefix or not.

```java
  String s1="Welcome";
  s1.startsWith("Wel"); //returns true
  s1.startsWith("el"); //returns false
```


# Class
- A class is a user defined blueprint or prototype from which objects are created.  It represents the set of properties or methods that are common to all objects of one type. In general, class declarations can include these components, in order: 

* **Modifiers:** A class can be public or has default access (Refer this for details).
* **class keyword:** class keyword is used to create a class.
* **Class name:** The name should begin with an initial letter (capitalized by convention).
* **Body:** The class body surrounded by braces, { }. 

# Object
- It is a basic unit of Object-Oriented Programming and represents the real life entities.  A typical Java program creates many objects, which as you know, interact by invoking methods. An object consists of : 

* **State**: It is represented by attributes of an object. It also reflects the properties of an object.
* **Behavior**: It is represented by methods of an object. It also reflects the response of an object with other objects.
* **Identity**: It gives a unique name to an object and enables one object to interact with other objects.

![img](https://i.stack.imgur.com/lNUAA.png)

# Object vs Class

<table class="alt">
<tbody><tr><th>Object</th><th>Class</th></tr>
<tr><td>Object is an <strong>instance</strong> of a class.</td><td>Class is a <strong>blueprint or template</strong> from which objects are created.</td></tr>
<tr><td>Object is a <strong>real world entity</strong> such as pen, laptop, mobile, bed, keyboard, mouse, chair etc.</td><td>Class is a <strong>group of similar objects</strong>.</td></tr>
<tr><td>Object is a <strong>physical</strong> entity.</td><td>Class is a <strong>logical</strong> entity.</td></tr>
<tr><td>Object is created through <strong>new keyword</strong> mainly e.g. Student s1=new Student();</td><td>Class is declared using <strong>class keyword</strong> e.g. class Student{}</td></tr>
<tr><td>Object is created <strong>many times</strong> as per requirement.</td><td>Class is declared <strong>once</strong>.</td></tr>
<tr><td>Object <strong>allocates memory when it is created</strong>.</td><td>Class <strong>doesn't allocated memory when it is created</strong>.</td></tr>
</tbody></table>


# Constructor

- Constructor in java is used to **create the instance** of the class. 
- Constructors are almost similar to methods except for two things - its **name** is the **same as the class name** and it has **no return type**.

Ex:
```java
public class School{

    //default constructor
    public School(){
        //initialise the object
    }
}
```

### Default Constructor
- If we don’t provide a constructor, then java provides default constructor implementation for us to use.

### No-Args Constructor
- Constructor without any argument is called a no-args constructor. It’s like overriding the default constructor

```java
public class School{
    String schoolType;
    
    public School(){
        schoolType="private";
        System.out.println("Created an object of schooltype: "+schoolType);
    }

    public static void main(String[] args) {
		School d = new School();
        System.out.println(d.schoolType());
	}
}

output => Created an object of schooltype: private
```

### Parameterized Constructor
- Constructor with **arguments** is called parameterized constructor. 

```java
public class School{

String schoolType;
 
    //Parameterized Constructor
    public School(String schoolType){
        this.schoolType=schoolType;
        System.out.println("Created an object of schooltype: "+schoolType);
    }

    public static void main(String[] args) {
		School d = new School("private");
        School x= new School("Govt");
	}
}

output =>
Created an object of schooltype: private
Created an object of schooltype: Govt
```

###  Constructor Overloading in Java
- When we have more than one constructors, then it’s constructor overloading in java

```java
public class School{

String schoolType;

 public School(){
        schoolType="private";
        System.out.println("Created an object of schooltype: "+schoolType);
    }
    //overloaded constructor
    public School(String schoolType){
        this.schoolType=schoolType;
        System.out.println("Created an object of schooltype: "+schoolType);
    }

    public static void main(String[] args) {
		School d = new School();
        School x= new School("Govt");
	}
}

output =>
Created an object of schooltype: private
Created an object of schooltype: Govt
```

# Method
>A Java method is a collection of statements that are grouped together to perform an operation. When you call the System.out.println() method, for example, the system actually executes several statements in order to display a message on the console.

Now you will learn how to create your own methods with or without return values, invoke a method with or without parameters, and apply method abstraction in the program design.

## Creating Method
Considering the following example to explain the syntax of a method −

Syntax
```
public static int methodName(int a, int b) {
   // body
}
```
Here,

**public static** − modifier

**int** − return type

**methodName** − name of the method


**int a, int b** − list of parameters

Method definition consists of a method header and a method body. The same is shown in the following 

Syntax
```
modifier returnType nameOfMethod (Parameter List) {
   // method body
}
```
The syntax shown above includes −

**modifier** − It defines the access type of the method and it is optional to use.

**returnType** − Method may return a value.

**nameOfMethod** − This is the method name. The method signature consists of the method name and the parameter list.

**Parameter List** − The list of parameters, it is the type, order, and number of parameters of a method. These are optional, method may contain zero parameters.

**method body** − The method body defines what the method does with the statements.

## Example

Here is the source code of the above defined method called min(). This method takes two parameters num1 and num2 and returns the maximum between the two −

/** the snippet returns the minimum between two numbers */

```
public static int minFunction(int n1, int n2) {
   int min;
   if (n1 > n2)
      min = n2;
   else
      min = n1;

   return min; 
}
```


# Java Access Modifiers

<table class="alt">
<tbody><tr><th>Access Modifier</th><th>within class</th><th>within package</th><th>outside package by subclass only</th><th>outside package</th></tr>
<tr><td><b>Private</b></td><td>Y</td><td>N</td><td>N</td><td>N</td></tr>
<tr><td><b>Default</b></td><td>Y</td><td>Y</td><td>N</td><td>N</td></tr>
<tr><td><b>Protected</b></td><td>Y</td><td>Y</td><td>Y</td><td>N</td></tr>
<tr><td><b>Public</b></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td></tr>
</tbody></table>

# Inheritance
- Inheritance in Java is a mechanism in which **one object acquires all the properties and behaviors of a parent object.**
- We can use the existing features of one class in another class.
- The inheritance provides a greate advantage called **code re-usability.** With the help of code re-usability, the commonly used code in an application need not be written again and again.

* **ChildClass/SubClass/DerivedClass** - the class that inherits from another class
* **ParentClass/SuperClass/BaseClass** - the class being inherited from


# How to inherit parent class properties and behaviours?
- using a special keyword **extends** 

Syntax:
```
class <ChildClassName> extends <ParentClassName>{
    ...
    //Implementation of child class
    ...
}
```
ex:
```
class Company{
    String companyName="OneAuto";
    String headQuarters="Bangalore";

    void onlineTeaching(){

    }

    void materialPublishing(){

    }

    void promotions(){

    }

}

Class Alex extends Compnay{

    void Test(){
        System.out.println(companyName); //this is inherited from parent
    }

}
```

# Why to inherit?

![img](../img/whyinherit.png)

- To reuse the code

# Types of inheritance?

There are five types of inheritances, and they are as follows.

* Simple Inheritance (or) Single Inheritance
* Multiple Inheritance
* Multi-Level Inheritance
* Hierarchical Inheritance
* Hybrid Inheritance

![img](../img/inheritTypes.jpg)

**Note** : The java programming language does not support multiple inheritance type. However, it provides an alternate with the concept of interfaces.

# Single inheritance
- one child class derives from one parent class.
ex:
```
class ParentClass{
	int a;
	void setData(int a) {
		this.a = a;
	}
}
class ChildClass extends ParentClass{
	void showData() {
		System.out.println("Value of a is " + a);
	}
}
public class SingleInheritance {

	public static void main(String[] args) {

		ChildClass obj = new ChildClass();
		obj.setData(100);
		obj.showData();

	}

}
```

# Multi level inheritance
- The child class derives from a class which already derived from another class.

ex:
```
class ParentClass{
	int a;
	void setData(int a) {
		this.a = a;
	}
}
class ChildClass extends ParentClass{
	void showData() {
		System.out.println("Value of a is " + a);
	}
}
class ChildChildClass extends ChildClass{
	void display() {
		System.out.println("Inside ChildChildClass!");
	}
}
public class MultipleInheritance {

	public static void main(String[] args) {

		ChildChildClass obj = new ChildChildClass();
		obj.setData(100);
		obj.showData();
		obj.display();

	}

}
```

# Hierarchical Inheritance
- Two or more child classes derive from one parent class

ex:
```
class ParentClass{
	int a;
	void setData(int a) {
		this.a = a;
	}
}
class ChildClass extends ParentClass{
	void showData() {
		System.out.println("Inside ChildClass!");
		System.out.println("Value of a is " + a);
	}
}
class ChildClassToo extends ParentClass{
	void display() {
		System.out.println("Inside ChildClassToo!");
		System.out.println("Value of a is " + a);
	}
}
public class HierarchicalInheritance {

	public static void main(String[] args) {

		ChildClass child_obj = new ChildClass();
		child_obj.setData(100);
		child_obj.showData();
        
		ChildClassToo childToo_obj = new ChildClassToo();
		childToo_obj.setData(200);
		childToo_obj.display();

	}

}
```
# Hybrid Inheritance
- The hybrid inheritance is the combination of more than one type of inheritance. We may use any combination as a single with multiple inheritances, multi-level with multiple inheritances, etc.,


# Points to be remembered in inheritance

- If a class is **final** then it cannot be inherited
- If a method is **private** then it cannot be inherited
- If a methods is **static** then it cannot be overridden in child class
- **super** keyword will be used to invoke parent class members or operations
- **protected** members or operations can be accessed only within the package or using inheritance

  # Polymorphism

- **Real life example of polymorphism:** A person at the same time can have different characteristic. Like a man at the same time is a father, a husband, an employee. So the same person posses different behavior in different situations. This is called polymorphism.
- Polymorphism means **"many forms"**, and it occurs when we have many classes that are related to each other by inheritance.
- This allows us to perform a **single action in different ways.**


# Types of Polymorphism 
## run time or dynamic polymorphism
  * This can be achieved usnig **Method overriding**
ex:
For example, think of a superclass called **Animal** that has a method called **animalSound().** Subclasses of Animals could be **Pigs, Cats, Dogs, Birds** - And they also have their own implementation of an animal sound (the pig oinks, and the cat meows, etc.):

```
class Animal {
  public void animalSound() {
    System.out.println("The animal makes a sound");
  }
}

class Pig extends Animal {
  public void animalSound() {
    System.out.println("The pig says: wee wee");
  }
}

class Dog extends Animal {
  public void animalSound() {
    System.out.println("The dog says: bow wow");
  }
}

class Main {
  public static void main(String[] args) {
    Animal obj = new Animal();  // Create a Animal object
    obj.animalSound();
    obj = new Pig();  // Create a Pig object
    obj.animalSound();
    obj = new Dog();  // Create a Dog object
    obj.animalSound();
  }
}
```
## Compile time polymorphism
  * This can be achieved using method overloading

  ex: 
```
  class Parent
{
    void demo (int a)
    {
       System.out.println ("a: " + a);
    }
    void demo (int a, int b)
    {
       System.out.println ("a and b: " + a + "," + b);
    }
    double demo(double a) {
       System.out.println("double a: " + a);
       return a*a;
    }
}
class Child
{
    public static void main (String args [])
    {
        Parent Obj = new Parent();
        double result;
        Obj.demo(10);
        Obj.demo(10, 20);
        result = Obj.demo(5.5);
        System.out.println("O/P : " + result);
    }
}
```


## Polymorphism - Method Overloading vs Method Overriding

<table class="alt">
<tbody><tr><th>Method Overloading </th><th>Method Overriding</th></tr>
<tr><td>Method overloading is used <em>to increase the readability</em> of the program.</td><td>Method overriding is used <em>to provide the specific implementation</em> of the method that is already provided by its super class.</td></tr>
<tr><td>Method overloading is performed <em>within class</em>.</td><td>Method overriding occurs <em>in two classes</em> that have IS-A (inheritance) relationship.</td></tr>
<tr><td>In case of method overloading, <em>parameter must be different</em>.</td><td>In case of method overriding, <em>parameter must be same</em>.</td></tr>
<tr><td>Method overloading is the example of <em>compile time polymorphism</em>.</td><td>Method overriding is the example of <em>run time polymorphism</em>.</td></tr>
<tr><td>In java, method overloading can't be done by changing only the return type of method. <em>Return type can be same/different</em> in overloading, but you must change the parameter.</td><td><em>Return type must be same or covariant (changing return type to subclass type)</em> in method overriding.</td></tr>
</tbody></table>

# Encapsulation

- Encapsulation in Java is a mechanism of wrapping the data (variables) and code acting on the data (methods) together as a single unit. 
- In encapsulation, the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class. Therefore, it is also known as **data hiding.**

![img](https://www.scientecheasy.com/wp-content/uploads/2018/06/encapsulation-in-java.png)
## To achieve encapsulation in Java −

- Declare the variables of a class as **private.**
- Provide public **setter and getter** methods to modify and view the variables values.

Ex:

```
public class EncapTest {
   private String name;
   private String idNum;
   private int age;

   public int getAge() {
      return age;
   }

   public String getName() {
      return name;
   }

   public String getIdNum() {
      return idNum;
   }

   public void setAge( int newAge) {
      age = newAge;
   }

   public void setName(String newName) {
      name = newName;
   }

   public void setIdNum( String newId) {
      idNum = newId;
   }
}
```
- The public setXXX() and getXXX() methods are the access points of the instance variables of the EncapTest class. Normally, these methods are referred as getters and setters. 
- The variables of the EncapTest class can be accessed using the following program
```
public class RunEncap {

   public static void main(String args[]) {
      EncapTest encap = new EncapTest();
      encap.setName("James");
      encap.setAge(20);
      encap.setIdNum("12343ms");

      System.out.print("Name : " + encap.getName() + " Age : " + encap.getAge());
   }
}
```

## Benefits of Encapsulation
- The fields of a class can be made read-only or write-only.
- A class can have total control over what is stored in its fields.

  # Abstraction

- **Abstraction** is a process of **hiding the implementation** details and showing only functionality to the user.

- A class which is declared with the **abstract** keyword is known as an abstract class in Java.
- It can have **abstract** and **non-abstract** methods (method with the body).
- Object (cannot be instantiated) cannot be created for abstract classes
- abstract class can only be **extended** in child classes
- As abstract contains both abstract and non-abstract, **100%** is not possible through abstraction

syntax:
```

ex:
```
abstract class A{
}
```
abstract class Bike{  
  abstract void run();  
}  
class Honda4 extends Bike{  
void run(){System.out.println("running safely");}  
public static void main(String args[]){  
 Bike obj = new Honda4();  
 obj.run();  
}  
}  
```

# Arrays

- Arrays are used to **store multiple values** in a single variable, instead of declaring separate variables for each value.

:::note initialization
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
int[] myNum = {10, 20, 30, 40};
char[] grades= {'a', 'b','c'};
```

## Access array elements

- Access an array element by referring to the **index** number.

```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars[0]);
==>  Volvo
```

## Change an array element

- Change the value of a specific element by referring to the **index** number:
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
cars[0] = "Opel";
System.out.println(cars[0]);
==> Opel
```

## Array Length

- To find out how many elements an array has, use the **length** property:
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars.length);
==> 4
```

## Loop through Arrays

- **for** iteration loop can used by *incrementing* the index till the **last index** (*length-1*)
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
int lastIndex= cars.length-1;
for(int i=0;i<=lastIndex;i++){
System.out.println(cars[i]);
}

==> Volvo BMW Ford Mazda

```

- For-Each loop can also be used, which is simple and does not need an index counter

```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

for(Strnig car:cars)){
System.out.println(car);
}

==> Volvo BMW Ford Mazda

```

:::note 
If you compare the for loop and for-each loop, you will see that the for-each method is easier to write, it does not require a counter (using the length property), and it is more readable.

:::

## Multidimensional Arrays

- A multidimensional array is an *array of arrays*.
- Multidimensional arrays are useful when you want to store data as a *tabular form*, like a table with *rows and columns*.
```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };

```

## Access/Modify Elements

- To access/Modify the elements of the array, specify **two indexes**

```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
System.out.println(myNumbers[1][2]); 
==> 7

myNumbers[1][2] = 9;
System.out.println(myNumbers[1][2]);
==> 9

```

## Loop Through a Multi-Dimensional Array

- We can also use a for *loop inside another for loop* to get the elements of a two-dimensional array (we still have to point to the *two indexes*):

```java
  int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
    for (int i = 0; i < myNumbers.length; ++i) {
      for(int j = 0; j < myNumbers[i].length; ++j) {
        System.out.println(myNumbers[i][j]);
      }
    }

==> 1 2 3 4 5 6 7 
```

# Collections 

- **Collections** and **arrays** are similar in that they both hold collection of objects
- However, unlike arrays, Collections **do not** need to be assigned a **certain capacity** when instantiated. 
- Collections can also grow and shrink in **size automatically** when objects are added or removed.
- Collections **cannot hold primitive** data types such as int, long, or double.
- Instead, Collections can hold **wrapper classes** such as **Integer**, **Long**, or **Double**.
- There are three generic types of Collection: **ordered lists**, **dictionaries/maps**, and **sets**.

## Ordered collections

- Ordered lists allows the programmer to **insert items** in a **certain order** and retrieve those items in the same order. 
- An example is a **Waiting List** in train ticket.
- The base interfaces for ordered lists are called **List** and **Queue**

## Unordered collections
- Sets are **unordered collections** that can be iterated and contain each element at most once. 
- The base interface for sets is called **Set**

## Dictionaries/Maps
- Dictionaries/Maps **store** references to objects with a **lookup key** to access the object's values.
- One example of a key is an **Employee id** to get **Employee details**.
- The base interface for dictionaries/maps is called **Map**.



### ArrayList (implements List interface)

:::note initialization
```java
List<Type> obj= new ArrayList<Type>();
Ex:
List<String> allaryList= new ArrayList<String>();

```
:::

|Task|Method|Example|
|--|--|--|
|Add an element |add(element)|arrayList.**add**("John"); <br/>==> [John]|
|Add an element at index|add(index, element)|arrayList.**add**(0,"Kennedy") <br/>  ==> [Kennedy, John]|
|Add multiple elements|addAll(array[]);|arrayList.**addAll**(Arrays.asList("Kamala", "Mani", "Stephen")); <br/> ==> [Kennedy, John, Kamala, Mani, Stephen]|
|Get an element at index|get(index)|arrayList.**get**(3); <br/> ==> "Mani"|
|Get all elements|[Iterator](##Iterator) or [forEach](##forEach) |check example|
|find an index of element|indexOf(element)|arrayList.**indexOf**("Mani") <br/> ==> 3|
|Update an element at index|set(index, element)|arrayList.**set**(3,"Sundar") <br/> ==> "Sundar" |
|Remove an element at index|remove(index) |==> [Kennedy, John, Kamala, Sundar, Stephen] <br/> arrayList.**remove**(3) <br/> ==> [Kennedy, John, Kamala, Stephen]|
|Remove all elements|clear|arrayList.**clear**() <br/> ==> []|
|get size of array|size()|arrayList.**size**() <br/> ==> 0|
|check if arryay contains specific element|contians(element)|==> [Kamala, Mani, Stephen] <br/> arrayList.**contains**("Mani") <br/> ==> true|
|check if array is empty|isEmpty()| arrayList.**isEmpty**() <br/> ==> false|

- *LinkedList*, *stack* also implements List, but we do not use them much in automation
- *Queue* is another iteface, which we does not use much in automation


## HashSet (implements Set Interface)

:::note initialization
```java
Set<Type> obj= new HashSet<Type>();
ex: 
Set<String> hashSet= new HashSet<String>();
```
:::
 

|Task|Method|Example|
|--|--|--|
|Add an element |add(element)|hashSet.**add**("John"); <br/>==> [John]|
|Add an element at index|Because it is unordered list, cannot insert item at specific index|NA|
|Add multiple elements|addAll(set);|hashSet.**addAll**(Arrays.asList("Kamala", "Mani", "Stephen")); <br/> ==> [John, Kamala, Mani, Stephen]|
|Get an element at index|Does not support because it is an unordered list|NA|
|Get all elements|[Iterator](##Iterator) or [forEach](##forEach) |check example|
|find an index of element|NA|NA|
|Update an element at index|NA|NA |
|Remove an element at index|NA|NA |
|Remove all elements|clear|hashSet.**clear**() <br/> ==> []|
|get size of set|size()|hashSet.**size**() <br/> ==> 0|
|check if set contains specific element|contians(element)|==> [Kamala, Mani, Stephen] <br/> hashSet.**contains**("Mani") <br/> ==> true|
|check if set is empty|isEmpty()| hastSet.**isEmpty**() <br/> ==> false|


## HashMap (implements Map interface)

:::note initialization
```java
Map<Key,Value> obj= new HashMap<Key,Value>();

Ex: 
Map<Integer,String> obj= new HashMap<Integer,String>();

```
:::

|Task|Method|Example|
|--|--|--|
|Add a pair (key,value) |put(key,value)|hashMap.**put**(1,"Kennedy") <br/> ==> {1=Kennedy}|
|Add multiple pairs|putAll(anotherHashMap)|Map<Integer,String> sectionB=new HashMap<Integer,String>(); <br/> hashMap.**putAll**(sectionB) <br/> ==> {1=Kennedy, 2=James, 3=Alex}|
|Get a value using key|get(key)|hashMap.**get**(2) <br/>  ==> "James"|
|Get all pairs|[Iterator](#Iterator) or [forEach](#forEach) |check example|
|Update a pair with key|put(key,value)|hashMap.**put**(1,"Calvin") <br/> ==> ==> {1=Calvin, 2=James, 3=Alex}
|Remove a pair with key|remove(key)|hashMap.**remove**(2) <br/> {1=Calvin, 3=Alex}|
|Remove all pairs |clear()|hashSet.clear() <br/> ==> {}|
|get size of map|size()|hashMap.**size**() <br/> ==> 0|
|check if pair contains specific value|contiansValue(value)|{1=Kennedy, 2=James, 3=Alex} <br/> hashMap.**containsValue**("Alex") <br/> ==> true|
|check if pair contains specific key|contiansKey(key)|{1=Kennedy, 2=James, 3=Alex} <br/> hashMap.**containsKey**(2) <br/> ==> true|
|check if pair is empty|isEmpty()| hashMap.**isEmpty**() <br/> ==> false|
|Add a pair with null key |put(null,value)|hashMap.**put**(null,"Tom") <br/> ==> {null=Tom, 1=Kennedy, 2=James, 3=Alex}|

## HashTable (implements Map interface)

:::note initialization
```java
Hashtable<Key,Value> table=new Hashtable<Key,Value>();
Ex:
Hashtable<Integer,String> table=new Hashtable<Integer,String>();
```
:::

- HashTable provides same functions like HashMap but it does not allow either null key or value
Ex:
```java

table.put(null, "Alex")
|  Exception java.lang.NullPointerException
|        at Hashtable.put (Hashtable.java:480)
|        at (#79:1)


table.put(1,null)
|  Exception java.lang.NullPointerException
|        at Hashtable.put (Hashtable.java:475)
|        at (#84:1)

````

# Traversing collections

- Any collection can be traversed using either an **iterator** or **forEach** loop

## Iterator

- An Iterator is an object that can be used to loop through collections.
- It is called an **iterator** because **iterating** is the technical term for **looping**.

## ArrayList/HashSet iterator
```java
List<String> languages = new ArrayList<>();

    // Add elements in the array list
    languages.add("Java");
    languages.add("Python");
    languages.add("JavaScript");
    languages.add("Swift");

    // Create a variable of Iterator
    // store the iterator returned by iterator()
    Iterator<String> iterate = languages.iterator();
    System.out.print("ArrayList: ");

    // loop through ArrayList till it has all elements
    // Use methods of Iterator to access elements
    while(iterate.hasNext()){
      System.out.print(iterate.next());
      System.out.print(", ");
    }

==> ArrayList: Java, Python, JavaScript, Swift,
```

## HashMap/HashTable iterator

```java
// create a HashMap
    HashMap<String, String> languages = new HashMap<>();
    languages.put("Java", "Enterprise");
    languages.put("Python", "ML/AI");
    languages.put("JavaScript", "Frontend");
    System.out.println("HashMap: " + languages);

    // create an object of Iterator
    Iterator<Entry<String, String>> iterate1 = languages.entrySet().iterator();

    // iterate through key/value mappings
    System.out.print("Entries: ");
    while(iterate1.hasNext()) {
      System.out.print(iterate1.next());
      System.out.print(", ");
    }

==> HashMap: {Java=Enterprise, JavaScript=Frontend, Python=ML/AI}
```


## forEach

## ArrayList/HashSet forEach
```java
List<String> languages = new ArrayList<>();

    // Add elements in the array list
    languages.add("Java");
    languages.add("Python");
    languages.add("JavaScript");
    languages.add("Swift");

    System.out.print("ArrayList: ");

    // loop through ArrayList till it has all elements
    for(String language:languages){
      System.out.print(language);
      System.out.print(", ");
    }

==> ArrayList: Java, Python, JavaScript, Swift,
```

## HashMap/HashTable forEach

```java
// create a HashMap
    HashMap<String, String> languages = new HashMap<>();
    languages.put("Java", "Enterprise");
    languages.put("Python", "ML/AI");
    languages.put("JavaScript", "Frontend");
    System.out.println("HashMap: " + languages);


    // loop through each Entry through key/value mappings
    for(Entry<String,String> language:languages) {
      System.out.print(language);
      System.out.print(", ");
    }

==> HashMap: {Java=Enterprise, JavaScript=Frontend, Python=ML/AI}
```

# LinkedList
- LinkedList is also part of Collections framework
- It is a linear data structure where the elements are not stored in continuous locations
- The elements are linked using pointers and addresses

![img](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png)


# Operations
<table><thead><tr><th>Method</th><th>Description</th></tr></thead><tbody><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-add-method-in-java/"><strong>add(int index, E element)</strong></a></th><th>This method Inserts the specified element at the specified position in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-add-method-in-java/"><strong>add(E e)</strong></a></th><th>This method Appends the specified element to the end of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-addall-method-in-java/"><strong>addAll(int index, Collection&lt;E&gt; c)</strong></a></th><th>This method Inserts all of the elements in the specified collection into this list, starting at the specified position.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-addall-method-in-java/"><strong>addAll(Collection&lt;E&gt; c)</strong></a></th><th>This method Appends all of the elements in the specified collection to the end of this list, in the order that they are returned by the specified collection’s iterator.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-addfirst-method-in-java/"><strong>addFirst(E e)</strong></a></th><th>This method Inserts the specified element at the beginning of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-addlast-method-in-java/"><strong>addLast(E e)</strong></a></th><th>This method Appends the specified element to the end of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-clear-method-in-java/"><strong>clear()</strong></a></th><th>This method removes all of the elements from this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-clone-method-in-java/"><strong>clone()</strong></a></th><th>This method returns a shallow copy of this LinkedList.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-contains-method-in-java/"><strong>contains(Object o)</strong></a></th><th>This method returns true if this list contains the specified element.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-descvenkatngiterator-method-in-java-with-examples/"><strong>descvenkatngIterator()</strong></a></th><th>This method returns an iterator over the elements in this deque in reverse sequential order.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-element-method-in-java-with- examples/"><strong>element()</strong></a></th><th>This method retrieves, but does not remove, the head (first element) of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-get-method-in-java/"><strong>get(int index)</strong></a></th><th>This method returns the element at the specified position in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-get-getfirst-getlast-java/"><strong>getFirst()</strong></a></th><th>This method returns the first element in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-getlast-method-in-java/"><strong>getLast()</strong></a></th><th>This method returns the last element in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-indexof-method-in-java/"><strong>indexOf(Object o)</strong></a></th><th>This method returns the index of the first occurrence of the specified element in this list, or -1 if this list does not contain the element.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-lastindexof-method-in-java/"><strong>lastIndexOf(Object o)</strong></a></th><th>This method returns the index of the last occurrence of the specified element in this list, or -1 if this list does not contain the element.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-listiterator-method-in-java/"><strong>listIterator(int index)</strong></a></th><th>This method returns a list-iterator of the elements in this list (in proper sequence), starting at the specified position in the list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-offer-offerfirst-offerlast-java/"><strong>offer(E e)</strong></a></th><th>This method Adds the specified element as the tail (last element) of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-offer-offerfirst-offerlast-java/"><strong>offerFirst(E e)</strong></a></th><th>This method Inserts the specified element at the front of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-offer-offerfirst-offerlast-java/"><strong>offerLast(E e)</strong></a></th><th>This method Inserts the specified element at the end of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-peek-peekfirst-peeklast-java/"><strong>peek()</strong></a></th><th>This method retrieves, but does not remove, the head (first element) of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-peek-peekfirst-peeklast-java/"><strong>peekFirst()</strong></a></th><th>This method retrieves, but does not remove, the first element of this list, or returns null if this list is empty.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-peek-peekfirst-peeklast-java/"><strong>peekLast()</strong></a></th><th>This method retrieves, but does not remove, the last element of this list, or returns null if this list is empty.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-poll-pollfirst-polllast- examples-java/"><strong>poll()</strong></a></th><th>This method retrieves and removes the head (first element) of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-poll-pollfirst-polllast- examples-java/"><strong>pollFirst()</strong></a></th><th>This method retrieves and removes the first element of this list, or returns null if this list is empty.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/java-util-linkedlist-poll-pollfirst-polllast- examples-java/"><strong>pollLast()</strong></a></th><th>This method retrieves and removes the last element of this list, or returns null if this list is empty.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-pop-method-in-java/"><strong>pop()</strong></a></th><th>This method Pops an element from the stack represented by this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-push-method-in-java/"><strong>push(E e)</strong></a></th><th>This method Pushes an element onto the stack represented by this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-remove-method-in-java/"><strong>remove()</strong></a></th><th>This method retrieves and removes the head (first element) of this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-remove-method-in-java/"><strong>remove(int index)</strong></a></th><th>This method removes the element at the specified position in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-remove-method-in-java/"><strong>remove(Object o)</strong></a></th><th>This method removes the first occurrence of the specified element from this list, if it is present.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-removefirst-method-in-java/"><strong>removeFirst()</strong></a></th><th>This method removes and returns the first element from this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-removefirstoccurrence-method-in- java/"><strong>removeFirstOccurrence(Object o)</strong></a></th><th>This method removes the first occurrence of the specified element in this list (when traversing the list from head to tail).</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-removelast-method-in-java/"><strong>removeLast()</strong></a></th><th>This method removes and returns the last element from this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-removelastoccurrence-method-in-java-with-example/"><strong>removeLastOccurrence(Object o)</strong></a></th><th>This method removes the last occurrence of the specified element in this list (when traversing the list from head to tail).</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-set-method-in-java/"><strong>set(int index, E element)</strong></a></th><th>This method replaces the element at the specified position in this list with the specified element.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-size-method-in-java/"><strong>size()</strong></a></th><th>This method returns the number of elements in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-spliterator-method-in-java/"><strong>spliterator()</strong></a></th><th>This method Creates a late-binding and fail-fast Spliterator over the elements in this list.</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-toarray-method-in-java-with-example/"><strong>toArray()</strong></a></th><th>This method returns an array containing all of the elements in this list in proper sequence (from first to last element).</th></tr><tr><th><a href="https://www.geeksforgeeks.org/linkedlist-toarray-method-in-java-with-example/"><strong>toArray(T[] a)</strong></a></th><th>This method returns an array containing all of the elements in this list in proper sequence (from first to last element); the runtime type of the returned array is that of the specified array.</th></tr><tr><th><strong>toString()</strong></th><th>This method returns a String containing all of the elements in this list in proper sequence (from first to last element), each element is separated by commas and the String is enclosed in square brackets.</th></tr></tbody></table>

# disadvantages
- Allows duplicates values
- No sorting
- More memory is required to store elements in linked list as compared to array. Because in linked list each node contains a pointer and it requires extra memory for itself.

  # Priority Queue
## Queue
- Queue is a basic data structure which follows first-in-first-out (FIFO)
- This data structure provides basic operations like **push, pop, search** etc
![img](https://www.atechdaily.com/resources/images/posts/2020/3/130/stackvsqueue.png)

## PriorityQueue
- Sometimes the elements of the queue are needed to be processed according to the priority, that’s when the PriorityQueue comes into play.
- The **front** of the priority queue contains the **least element** according to the specified ordering, and the **rear** of the priority queue contains the **greatest** element.
![img](https://www.callicoder.com/static/dc8fe7b4bba83ff881497f51b25951a2/51aac/priority-queue-data-structure.jpg)
- So when you remove an element from the priority queue, the least element according to the specified ordering is removed first.


# operations
<table><thead><tr><th>METHOD</th><th>DESCRIPTION</th></tr></thead><tbody><tr><td><a href="https://www.geeksforgeeks.org/queue-peek-method-in-java/">peek()</a></td><td>Retrieves, but does not remove, the head of this queue, or returns null if this queue is empty.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/queue-poll-method-in-java/">poll()</a></td><td>Retrieves and removes the head of this queue, or returns null if this queue is empty.</td></tr></tbody></table>

<table><thead><tr><th>METHOD</th><th>DESCRIPTION</th></tr></thead><tbody><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-add-method-in-java/">add(E e)</a></td><td>Inserts the specified element into this priority queue.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-clear-method-in-java/#:~:text=clear()%20method%20is%20used,only%20empty%20an%20existing%20PriorityQueue.">clear()</a></td><td>Removes all of the elements from this priority queue.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-comparator-method-in-java/">comparator()</a></td><td>Returns the comparator used to order the elements in this queue, or null if this queue is sorted according to the natural ordering of its elements.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-contains-method-in-java/#:~:text=PriorityQueue.,any%20particular%20element%20or%20not.&amp;text=Return%20Value%3A%20The%20method%20returns,queue%20otherwise%20it%20returns%20False.">contains​(Object o)</a></td><td>Returns true if this queue contains the specified element.</td></tr><tr><td>forEach​(Consumer&lt;? super E&gt; action)</td><td>Performs the given action for each element of the Iterable until all elements have been processed or the action throws an exception.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-iterator-method-in-java/">iterator()</a></td><td>Returns an iterator over the elements in this queue.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-offer-method-in-java/">&nbsp;offer​(E e)</a></td><td>Inserts the specified element into this priority queue.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-remove-method-in-java/">remove​(Object o)</a></td><td>Removes a single instance of the specified element from this queue, if it is present.</td></tr><tr><td>removeAll​(Collection&lt;?&gt; c)</td><td>Removes all of this collection’s elements that are also contained in the specified collection (optional operation).</td></tr><tr><td>removeIf​(Predicate&lt;? super E&gt; filter)</td><td>Removes all of the elements of this collection that satisfy the given predicate.</td></tr><tr><td>retainAll​(Collection&lt;?&gt; c)</td><td>Retains only the elements in this collection that are contained in the specified collection (optional operation).</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-spliterator-method-in-java/">spliterator()</a></td><td>Creates a late-binding and fail-fast Spliterator over the elements in this queue.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-toarray-method-in-java/#:~:text=toArray(arr%5B%5D)%20method%20in,the%20previous%20method%20without%20parameters.">&nbsp;toArray()</a></td><td>Returns an array containing all of the elements in this queue.</td></tr><tr><td><a href="https://www.geeksforgeeks.org/priorityqueue-toarray-method-in-java/#:~:text=toArray(arr%5B%5D)%20method%20in,the%20previous%20method%20without%20parameters.">&nbsp;toArray​(T[] a)</a></td><td>Returns an array containing all of the elements in this queue; the runtime type of the returned array is that of the specified array.</td></tr></tbody></table>

# Stack
- The data structure is based on the basic principle of **last-in-first-out. (LIFO)**
- In addition to the basic **push and pop** operations, the class provides three more functions of **empty, search, and peek.**

![img](https://static.javatpoint.com/core/images/java-stack.png)

# push
![img](https://static.javatpoint.com/core/images/java-stack2.png)
# pop
![img](https://static.javatpoint.com/core/images/java-stack3.png)

# Operations
| METHOD | DESCRIPTION |
| --- | --- |
| [empty()](https://www.geeksforgeeks.org/stack-empty-method-in-java/) | It returns true if nothing is on the top of the stack. Else, returns false. |
| [peek()](https://www.geeksforgeeks.org/stack-peek-method-in-java/) | Returns the element on the top of the stack, but does not remove it. |
| [pop()](https://www.geeksforgeeks.org/stack-pop-method-in-java/) | Removes and returns the top element of the stack. An ‘EmptyStackException’ <br /><br />An exception is thrown if we call pop() when the invoking stack is empty. |
| [push(Object element)](https://www.geeksforgeeks.org/stack-push-method-in-java/) | Pushes an element on the top of the stack. |
| [search(Object element)](https://www.geeksforgeeks.org/stack-search-method-in-java/) | It determines whether an object exists in the stack. If the element is found,<br /><br />It returns the position of the element from the top of the stack. Else, it returns -1. |

# Encapsulation

- Encapsulation in Java is a mechanism of wrapping the data (variables) and code acting on the data (methods) together as a single unit. 
- In encapsulation, the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class. Therefore, it is also known as **data hiding.**

![img](https://www.scientecheasy.com/wp-content/uploads/2018/06/encapsulation-in-java.png)
## To achieve encapsulation in Java −

- Declare the variables of a class as **private.**
- Provide public **setter and getter** methods to modify and view the variables values.

Ex:

```
public class EncapTest {
   private String name;
   private String idNum;
   private int age;

   public int getAge() {
      return age;
   }

   public String getName() {
      return name;
   }

   public String getIdNum() {
      return idNum;
   }

   public void setAge( int newAge) {
      age = newAge;
   }

   public void setName(String newName) {
      name = newName;
   }

   public void setIdNum( String newId) {
      idNum = newId;
   }
}
```
- The public setXXX() and getXXX() methods are the access points of the instance variables of the EncapTest class. Normally, these methods are referred as getters and setters. 
- The variables of the EncapTest class can be accessed using the following program
```
public class RunEncap {

   public static void main(String args[]) {
      EncapTest encap = new EncapTest();
      encap.setName("James");
      encap.setAge(20);
      encap.setIdNum("12343ms");

      System.out.print("Name : " + encap.getName() + " Age : " + encap.getAge());
   }
}
```

## Benefits of Encapsulation
- The fields of a class can be made read-only or write-only.
- A class can have total control over what is stored in its fields.
