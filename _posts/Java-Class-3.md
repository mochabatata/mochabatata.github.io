title: Java Class 3
date: 2014-08-03 12:55:15
tags: [Java,Class]
category: Programming
---


##Part 6 Java API
Java contains hondreds of libraries and methods
###Arraylist
add(Object elem) 
remove(int index) 
remove(Object elem) 
contains(Object elem) //true if contains
isEmpty() list 
indexOf(Object elem) // -1 id no elements
size()
get(int index)
###ArrayList and array
```bash
new ArrayList<String>();  //ArrayList
new String[2];            //array
```
```bash
myList.add(b);            //ArrayList
myList[1] = b;            //array
```
###About API
package：java.util.ArrayList
Difference between import and include："import" ellipsised the front packages' names
Inquire API：HTML API documents

##Part 7 Inheritance & Polymorphism
"For better Life"
###Inheritance
Jvm doesn't care about which class the method comes from.
**Relationship between classes**：
is-a : one way, suitable for inheritance
has-a : contains
**Access lecel**
public-yes, private-no
private < default < protected < public
**Meaning**：
Reduce redundancy; Same protocol
**Prohibits inheritance**：
1. One package's class only can be inherited by the same package's classes
2. final keyword
3. private

**Overriding**: method
Can not change parameters and the return type.
public cannot be changes to private.

###Polymorphism
Dog myDog = new Dog();
Animal myDog = new Dog();
Aninal is parent class of Dog
**Parameters'  and return type's Polymorphism**：
Eg:makenoise(animal a)
makenoise(d)
makenoise(c)！
**Meaning**：Via polymorphism, adding new child class don't need to change parent class codes.

###Overloading
Same method name, but different parameters
! Nothing to do with Polymorphism

Properity: extension
Different return type and differnt parameters both
