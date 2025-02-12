
## OOP Fundamentals
#### Abstraction
- An abstraction hides the internal implementation details. Typically done with an interface file that has all the key definitions. The class that implements the interface must have each method defined.
- Example: `class Car implements Honda` where Car is the abstracted class and Honda is the concrete class
#### Encapsulation
- Protecting data members and methods in a class. Typically, data members are private and methods like getters and setter are public and allow controlled access to data. Data validation can be implemented in setters to ensure data integrity.
- Example: `public`, `private`, `protected`, `default`
#### Inheritance
- Porcess of one class inheriting properties and methods from another class.
- Example: `class Car extends Vehicle` where Car inherits properties and methods from Vehicle class. Car can override Vehicle methods. 
#### Polymorphism
- Ability of objects to have multiple forms or to be treated as objects of a common type
- Compile-time polymorphism:
  - Method overloading where one or more methods have the same name but different parameters
  - Operator overloading where you can define custom behaviors for operators such as +, -, or < for user-defined classes
- Run-time polymorphism (aka late binding or dynamic polymorphism):
  - Method overriding where a child class can provide a new implementation for a parent class's method.
  - Virtual methods can be overridden in the child class.

## SOLID Principles
#### Single Responsibility Principle
- Every class, module or function in  a program should have one responsibility/purpose.
#### Open Close Principle
- Classes, modules, or functions should be open for extension, but closed for modification. Changes are handled as new methods or new classes.
#### Liskov Substitution Principle
- Every subclass or derived class should be substitutable for their base or parent class. Functions that use pointers to base classes must be able to use objects of derived classes without knowing it.
#### Interface Segregation Principle
- No code should be forced to depend on methods it does not use. ISP splits interfaces that are very large into smaller and more specific ones so that clients will only have to know about the methods that are of interest to them.
#### Dependency Inversion Principle
- High level modules should depend on abstraction rather than concreate implementations. This helps decouple the high-level and low-level modules, making it easier to change the low-level ones without affecting the high level ones.
