# All_Designs_Patterns


#Creational Design Patterns

This repository contains examples of creational design patterns implemented in Java. Creational design patterns focus on object creation mechanisms, trying to create objects in a manner suitable to the situation. The examples include:

#Singleton Pattern

#Factory Method Pattern

Examples

#Singleton Pattern

The Singleton Pattern ensures that a class has only one instance and provides a global point of access to it.

Example Description:

Singleton: Provides a method to get the single instance of the class and ensures only one instance exists.
Usage:

java
Copy code
// Example usage for Singleton Pattern
javac src/singleton/*.java
java -cp src singleton.Main


#Factory Method Pattern
The Factory Method Pattern defines an interface for creating objects but allows subclasses to alter the type of objects that will be created.

Example Description:

Creator: Declares the factory method, which returns an object of type Product.
ConcreteCreator: Overrides the factory method to return an instance of a ConcreteProduct.
Product: Defines the interface for objects created by the factory method.
ConcreteProduct: Implements the Product interface.
Usage:

java
Copy code
// Example usage for Factory Method Pattern
javac src/factorymethod/*.java
java -cp src factorymethod.Main

#Behavioral Design Patterns

This repository contains examples of behavioral design patterns implemented in Java. Behavioral design patterns are concerned with the interaction and responsibility of objects. The examples include:

#Observer Pattern

#Strategy Pattern

Examples

#Observer Pattern

The Observer Pattern defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.

Usage:

java
Copy code
// Example usage for Observer Pattern
javac src/observer/*.java
java -cp src observer.Main

#Strategy Pattern

The Strategy Pattern defines a family of algorithms, encapsulates each one, and makes them interchangeable. It lets the algorithm vary independently from clients that use it.

Usage:

java
Copy code
// Example usage for Strategy Pattern
javac src/strategy/*.java
java -cp src strategy.Main


# Structural Design Patterns

This repository contains examples of structural design patterns implemented in Java. Structural design patterns are concerned with how classes and objects are composed to form larger structures. The examples include:

1. **Flyweight Pattern**
2. **Proxy Pattern**
### Running the Example:
```sh
javac src/flyweight/*.java
java -cp src flyweight.Main
