# Learning Java from Scratch

This will include timestamped learning details to show progress.

I am learning using "Complete Java Development: Spring Boot, Microservices, Spring AI" by Telusko on Youtube. Youtube video link: [Go to video](https://www.youtube.com/watch?v=q6z_UCBM5Ek&t=2784s)

## Current Stack

### 17-05-2026
- Java Version: 17.0.18
- Javac version: 17.0.10
- OS: Ubuntu

## Daily Learning
### Core Java
#### 17-05-2026

**Youtube timestamp 00:00:00 - 00:45:00**

Today I learned about the following
- Java Compiler and JDK: Important to write and run java on any device
- Java is a write once read anywhere (WORA) language, meaning that once java is written it becomes platform dependant
- JVM means Java Virtual Machine
- JRE mean Java Runtime Engine
- JRE contains the JVM and other library used to write java
- It is good to use a java version that has Long Term Support (LTE) meaning it is still being maintained.
- When writing java, there is a main file where all other files are called from. This is the file that the java compiler converts into byte code. And it is this byte code that the JVM understands as it does not understand raw java code. The byte code is also one file.
- The main file contains a class and a method with the signature I acronymed (PSVMSA) mean "public static void main (string a[])"
- jshell. The java command line tool use to run java code without the overhead of classes, methods and main file.

#### 18-05-2026

**Youtube timestamp 00:45:00 - 2:30:00**

Today I learned about the following:
- They are two groups of datatypes in Java
- One of the two group is called Primitive Datatypes and we focused on this group.
- Primitive Datatypes can be further broken down into integer (int), float, character (char) and Boolean (bool).
- Integer can be further broken down into bytes, short, long, etc
- Float can be further broken down into float and double.
- Datatypes need to be obviously stated such as float and long e.g 2.5f and 345l
- Implicit and explicit type casting
- Implicit type casting is a the act of converting similar datatypes from a datatype with less storage space to one of higher storage space e.g. bytes to short, float to double
- Explicit type casting makes the opposite of implicit casting possible but it requires explicitly calling the target datatype which always has lesser storage. 
- Arithmetic operators: +, -, *, /, %, +=, -=, *=, /=, ++, --
- Assignment operator: =
- Tenary operator: ?:
- Conditional operators: <, >, <=, >=, ==, if-else if-else, switch-case-default.
- Logical operations: &, |, &&, || 
- Loops: While, Do while, For
- Ensure to end java statements with ;

