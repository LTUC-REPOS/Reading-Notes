# OOP2

<br><br>


## Design Patterns

<br>

> Patterns are formalized best practices that the Software Developer can use to solve common problems when designing an application. <br>

> In the case of object-oriented programming paradigm, design patterns are generally aimed at solving the problems of object generation and communication <br>

<br>

### There is 3 major types of design patterns:

<br>

#### Creational Patterns:

<br>

> Creational patterns provide ways to instantiate single or groups of objects. Making it easier to create objects in a way that suits the situation. <br>

<p>

Creational Patterns:

Factory Method. The factory pattern is used to replace class constructors, abstracting the process of object generation so that the type of the object instantiated can be determined at run-time. <br>

Singleton. The singleton pattern ensures that only one object of a particular class is ever created. All further references to objects of the singleton class refer to the same underlying instance. <br>

Abstract Factory. The abstract factory pattern is used to provide a client with a set of related or dependent objects. The “family” of objects created by the factory are determined at run-time. <br>

</p>

<br>

#### Creational Patterns:

<br>

> Structural patterns provide a manner to define relationships between classes or objects. Making it easier for these entities to work together. <br>

<p>

Structural Patterns:

Facade. The facade pattern is used to define a simplified interface to a more complex subsystem. <br>

Adapter. The adapter pattern is used to provide a link between two otherwise incompatible types by wrapping the “adaptee” with a class that supports the interface required by the client. <br>

Decorator. The decorator pattern is used to extend or alter the functionality of objects at run-time by wrapping them in an object of a decorator class. This provides a flexible alternative to using inheritance to modify behavior. <br>

</p>


#### Behavioral Patterns:

<br>

> Behavioral patterns define manners of communication between classes and objects. Making it easier and more flexible for these entities to communicate. <br>

<p>

 Behavioral Patterns:

Observer. The observer pattern is used to allow an object to publish changes to its state. Other objects subscribe to be immediately notified of any changes. <br>

Mediator. The mediator pattern is used to reduce coupling between classes that communicate with each other. Instead of classes communicating directly, and thus requiring knowledge of their implementation, the classes send messages via a mediator object. <br>

Chain of Responsibility. The chain of responsibility pattern is used to process varied requests, each of which may be dealt with by a different handler. <br>

</p>


<br>


## Risk Analysis in Software Testing

> risk analysis is the process of identifying the risks in applications or software that 
you built and prioritizing them to test. After that, the process of assigning the level of risk 
is done. The categorization of the risks takes place, hence, the impact of the risk is calculated. <br>

- Why use Risk Analysis?

>helps the developers and managers to mitigate the risks. When a test plan has been created, 
>risks involved in testing the product are to be taken into consideration along with the 
>possibility of the damage they may cause to your software along with solutions.

- Possible risks

Use of new hardware   
Use of new technology   
Use of new automation tool   
The sequence of code   
Availability of test resources for the application

- Risk identification

Business Risks: This risk is the most common risk associated with our topic. It is the risk that may come from your company or your customer, not from your project.

Testing Risks: You should be well acquainted with the platform you are working on, along with the software testing tools being used.

Premature Release Risk: a fair amount of knowledge to analyze the risk associated with releasing unsatisfactory or untested software is required

Software Risks: You should be well versed with the risks associated with the software development process.


- Perform risk Assessment

Searching the risk

Analyzing the impact of each individual risk

Measures for the risk identified


## Dependency Injection

dependency injection is a technique whereby one object (or static method) supplies the dependencies of another object.  
A dependency is an object that can be used (a service).

When class A uses some functionality of class B, then its said that class A has a dependency of class B.

- Three types of dependency injection:

1, constructor injection: the dependencies are provided through a class constructor.   
2, setter injection: the client exposes a setter method that the injector uses to inject the dependency.   
3, interface injection: the dependency provides an injector method that will inject the dependency into  
any client passed to it. Clients must implement an interface that exposes a setter method that accepts the dependency.

- Benefits and Disadvantages of DI

Help unit testing   
Extending the application and enable loose coupling   
Complex to learn   
Compile errors





