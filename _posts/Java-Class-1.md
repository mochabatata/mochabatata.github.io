title: 'Java Class 1'
date: 2014-08-01 16:05:45
tags: [Java,Class]
category: Programming
---

##Part 1 Basic
###About Java:
Java: Write-once/run-anywhere
###About Environment:
IDE (Integrated Development Environment)
SDK (Software Development Environment)
Mac OS X internally installed Java SDK 
###Compile and run:
1. .java as file name
2. javac compiles .java files, and creates .class files if no error occurs. 
3. JVM runs .class files, and searches the main method in all classes at the beginning.

###Program structure:
A .java file contains the definition of classes.
A Class contains kinds of methods. 

##Part 2 Class and Object
Change your life：(eg: Rotated shapes & playing sounds)
###Class：
**Inheritance**: Figure out the same charactors in the classes，and extract a new class as parent calss. Child class inheritance parent class's methods.
**Overriding**: Child class redefines the basic class's method. You can return a derived type of what the base class method returned.
###Object：
Three levels of object structure: name, object, method
Tips:Object is the instance of class 
###main():
Use:
1. Test class
2. Start the Java program
###Garbage collector：
The object is created on memory. When JVM detects the object won't be used any moew, the object is marked and garbage collector recycles it.