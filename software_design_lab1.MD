Software Design Lab


1. What do we mean by coupling and cohesion when discussing structured design?


Coupling in structured design:\ulnone

Measuring the extent of how two modules (a class, function etc.) within a design are linked. There are strongly coupled and loosely coupled modules.

Cohesion in structured design:

Cohesion is the ability for a module to perform one task, with most of what the module needs in the module itself.


2. What\'92s the difference between top-down and bottom-up design? Which best describes a function oriented design?

\
Top-down design:

Design starting with the problem/concept and then breaking that down into smaller parts to make it more easily managed.

Bottom-up design:

Bottom up design starts with specifying the smaller components, which then forms up the larger components until the bigger picture is created. OOP would suit this.

Function oriented design is a top down approach, as the general model is broken down into smaller bits, each having their own function.


3. In which design methodology would a class diagram be most useful?


A class diagram would be most useful in object oriented design, as real world objects/entities are represented, and classes are the blueprint in which objects are created from.


4. What are the four pillars of object oriented programming?


- Abstraction - Abstraction is hiding the internal workings/implementation details inside something, for example, calling a function and not worrying about all the code within it.
- Encapsulation - Encapsulation refers to keeping data within a single unit (object, class) and keeping the data within it private.
- Inheritance - Inheritance is when methods and properties of one class are passed down to another class.
- Polymorphism - Polymorphism is the ability to have behaviours which can be changed within different classes and objects e.g., overriding a function.


5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

The strategy patten is a design pattern where a bigger class that does one thing lots of different ways, is broken down into smaller classes called 'strategies' . A strategy of how to do the one thing can then be selected when it needs to be done.\

It would be implemented using a high order function (function taking in other functions as parameters) in functional design, whereas in object oriented design it would be implemented using an interface and classes than implement that interface.\


6. Which design methodology would you suggest following? Give some justification for your decision.


I would use object oriented design to create a new online payment system. I would do this for the following reasons.

- Object oriented design uses interfaces. This in turn could be useful for creating classes that use the method pay() for example, which would be able to be overridden in those classes. For example, one class for takeaways implementing the pay method could also include a discount function that wouldn't be wanted in the banking realm.
- It would be very scalable, as classes would be loosely coupled (using interfaces for methods) instead of having to be tightly coupled (a class is dependant on another class).
- encapsulation allows for private properties of objects.