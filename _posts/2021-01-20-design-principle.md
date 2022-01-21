# SOLID design principle

## Single Responsibility Prinicple
A class should only have one reason to change.
## Opened/Closed Principle
Software entities(classes, modules, functions, etc) should be open for extension, but closed for modification.
## Liskov Substitution Principle
Let Φ(x) be a property provable about objects x of type T. Then Φ(y) should be true for objects y of type S where S is a subtype of T.

Objects of a superclass shall be replaceble with objects of its subclasses without breaking the applications.

## Dependency inversion
High-level modules should not depend on low-level modules. Both should depend on abstractions.

Abstractions should not depend on details. Details should depend on abstractions.

## Interface Segregation Principle
Clients should not be forced to depend upon interfaces that they do not use.
# OOP in Java

OOP is the abbreviation of Object-Oriented Programming.
## Encapsulation
Encapsulation is defined as the wrapping up of data under a single unit. It is the mechanism that binds together code and the data it manipulates. Another way to think about encapsulation is, it is a protective shield that prevents the data from being accessed by the code outside this shield. 
## Abstaction
Abstraction lets programmers create useful and reusable tools. It can be seen as the technique of filtering out the unnecessary details of an object so that there remain only the useful characteristics that define it. Abstraction focuses on the perceived behavior of the entity. It provides an external view of the entity.

## Inheritance
Inheritance in Java is a mechanism in which one object acquires all the properties and behaviors of a parent object. When you inherit from an existing class, you can reuse methods and fields of the parent class. Moreover, you can add new methods and fields in your current class also.

## Polymorphism
Polymorphism in Java is a concept by which we can perform a single action in different ways.

# Others

## Dependency injection
Dependency injection is a technique in which an object receives other objects that it depends on, called dependencies. 
## Reflection in Java
Reflection is an API which is used to examine or modify the behavior of methods, classes, interfaces at runtime.

* The required classes for reflection are provided under java.lang.reflect package.
* Reflection gives us information about the class to which an object belongs and also the methods of that class which can be executed by using the object.
* Through reflection we can invoke methods at runtime irrespective of the access specifier used with them.

## Generic in Java

