## Assignment 2 (Variable and Data Types)
1. What do you understand by variable?
-  Variable is a quantity that may change withning contextual or mathmetical problem or experiment. They are known as variable because the values can change. 
However, in Java, variables are containers that store data values and need to be declared by data type.
  
3. Name types of variables.
- Non static fields/Instance variables
- Static fields
- Local variables 
- Parameters
4. What is the difference between static and instance variables?
- Instance variables belong to an object and they belong to an object. Their classes are unique to each instances.
- Static variables are declared with static modifiers. This values are not unique and don't belong to specific object. Instead this is static and belongs to all objects.

5.	Which type of variable requires a keyword to determine its scope?
- Static variables require a keyword to determine its scope.

6.	Which thing specifies the size and type of variable?
Data type specifies the size and type of variable. Primitive data type is responsible for specifying the size and type.

7.	Can we use a variable without declaring it?
No, all variables need to be declared.

8.	How can we declare a variable?
- Specify the tupe, leave one space and then use name of the variable and then end the line with ; 

9.	How can we initialize a variable?
- Initialiazation require assigning a value. However, the first step is declaring the variable with int (example int id;) and then assign value (example id = 1;)

10.	Make a list of common Java data types.
- Common data types 
  - Short (2 bytes) 
  - int (4 bytes)
  - long (8 bytes)
  - byte
  - char
  - boolean
  - float
  - double

11.	Which data types are created by programmers and are not defined by Java?
- Non  primitive data types such as class, object, string, array and interfaces.

12.	Java has how many primitive data types?
- Eight

13.	What data type would you use for storing the number of students in a class?
- Int because we are looking at whole number.

14.	What data type would you use for storing the average test score in a class?
- double as this numbers have twice precision of the float type. Otherwise we can use float if we dont need precision.
 
15.	How would you declare a variable storing the tax rate?
- byte can be used to store tax rate as its normally a smaller number.

16.	How would you declare a variable that tells the grade (A, B, C, or D) of students?
- char will be used to declared text variables such as A, B, C or D.

17.	List the name conventions you learned in class about variables.
- Variable names are case sensitive
- The name should always start with letter instead of signs or digits.
- When choosing names use full name as that makes code easier.
- The name should consist of only one word in all lowercase letters. If it consist more than one word then capitalize the first letter of innerword.

18.	Name the Data type used for an object 'Pen'.
- char as its a text data.

19.	Write a program and declare the variable of each data type you learned in class. Initialize each variable with appropriate values and print them. 
- public class DataType {
<br> public static void main(String[] args)
<br> {
<br> int myNum = 5; //integer (whole number)
<br> float myFloatNum = 5.99f; //floating point number
<br> double myDoubleNum = 15.99d; //double floating number
<br> char myLetter = 'D'; // character as in text
<br> boolean myBoolean = true; // Boolean as in true or false
<br> String myText = "Hello"; // Text
<br> System.out.println(myNum);
<br> System.out.println(myFloatNum);
<br> System.out.println(myDoubleNum);
<br> System.out.println(myLetter);
<br> System.out.println(myBoolean);
<br> System.out.println(myText);
}
}

20.	Write a program to print your name, email, address, phone number, and id. 
- public class Detail {
<br> public static void main(String[] args)
<br> {
<br> String myName = "John";
<br> String myEmail = "john@javaassignment2.com";
<br> String myAddress = "34212 Ryan Road, MI";
<br> int myNumber = 646872827;
<br> int id = 1;
<br> System.out.println(myName);
<br> System.out.println(myEmail);
<br> System.out.println(myAddress);
<br> System.out.println(myNumber);
<br> System.out.println(id);
}
}	

21.	What do you understand by typecasting?
- Typecasting is a way of converting one type of data to another type.

22.	In which type casting Java automatically converts one data type to another data type?
- During impicit casting. When converting from narrower range to wider range.

23.	Write a program to convert int to double and print a message stating which type casting you did?
- public class ConvertTest {
<br> public static void main(String[] args) {
<br> int myInt = 9;
<br> double myDouble = myInt; // Automatic casting: int to double
<br> System.out.println(myInt);
<br> System.out.println(myDouble);
<br> }
<br> }

24.	Write a program to convert double to int and print a message stating which type casting you did?
- public class ConvertTest2 {
<br> public static void main(String[] args) {
<br> double myDouble = 19.99d;
<br> int myInt = (int) myDouble; // Automatic casting: int to double
<br> System.out.println(myDouble);
<br> System.out.println(myInt);
<br> }
<br> }

25.	Write a program to convert int to string and print a message stating which type casting you did?
- Int can not be converted into string.

26.	Write a program to convert string to int and print a message stating which type casting you did?
- String can not be converted into int.

27.	Write a program to convert float to double and print a message stating which type casting you did?
- public class FloatDouble {
  <br> public static void main(String[] args) {
    <br> float myFloat = 1.99f;
    <br> double myDouble = myFloat; // Automatic casting: float to double

    <br> System.out.println(myFloat);
    <br>System.out.println(myDouble);
  <br>}
<br>}

28.	Write a program to convert byte to float and print a message stating which type casting you did?
- public class ByteFloat {
  <br> public static void main(String[] args) {
    <br> byte myByte = 10;
    <br> float myFloat = myByte; // Automatic casting: Byte to Float

    <br>System.out.println(myByte);
    <br>System.out.println(myFloat);
  <br>}
<br>}

29.	Write a Java program to get the character at the 5th index of the String “automation”.


30.	Write a program to find the length of the string "automation".


31.	Write a Java program to concatenate a string “Java” to the end of another string “C#”.


32.	Write a Java program to compare a string “automation” and another string “Automation”.


33.	Write a Java program to check whether a string “Software” ends with the contents of another string “Hardware”. 

34.	Write a Java program to replace a character “n” with character “m” in the string “Automation”.


35.	Write a Java program to check whether a string “Java is my favorite programming Lang” starts with the contents of another string “Python is my favorite programming language”.


36.	Write a program to get a substring of the string “Let this be the last year tha you doubt yourself, fear, change or quit. Never give up” starting from index 10 and ending at index 26.


37.	Write a Java program to convert all the characters in a string “YourName” to lowercase.


38.	Write a Java program to convert all the characters in a string “YourName” to uppercase.


39.	Write a program to reverse a string “ Java is my favorite”. 


