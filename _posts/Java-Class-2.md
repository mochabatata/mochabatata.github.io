title: Java Class 2
date: 2014-08-03 12:30:27
tags: [Java,Class]
category: Programming
---

##Part 3 Variables
###Primitive Data type: 
boolean char | byte short int long | float double
###Objext Variables:
Actually, there is no Objext Variables. It means the variable referenced to object. It is not a container, and it's like pointer and address.
**Example**：
``` bash 
Dog d = new Dog();
d.bark();
```
d is like a remote, "." is like a button on the remote.
###Declaration, creation and assignment of object
``` bash 
Dog d = new Dog();
```
Dog d  ——require jvm to allocate space to variable named d, and the type of d is Dog.
new Dog() ——require JVM allocate stack space to the new object.
= assign operator
###Array：
```bash
int[] nums;         //delaration
nums = new int[7];  //create
```
###Array object：
```bash
Dog [] pets;        //create a remote called pets
pets = new Dog[7];  //define the object the remote pointed to
Dog[0] = new Dog();
```

##Part 4 Method
###Content of class：
What object knows and executes
###Passing：
Argument  Parameter  Return value
###Capsulation：
get(), set()
dog.age = 2; Create setter to age, and use setter to set value to age.
Tis: And filter in setter is nice way to restrict the value of variable.
Variable is private, and setter and getter are public.

##Part 5 Programming
###High level design：
Remember：Think in the way of Object Oriented，and focus on end, not process.
###Class development：
1. What this class should do
2. List variables and Methods
3. Write pseudocode：Declaration of variables, methods and logic of methods
4. Test methods of methods: help you know and debug.
5. Implement the class
6. Debug & redesign
