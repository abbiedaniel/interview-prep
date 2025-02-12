# Design Patterns To Know

## Creational Design Patterns
Focuses on object creation. They help in making a system independent of how its objects are created, composed and represented.

- Singleton Pattern: lets you ensure that a class has only one instance, while providing a global access point to this instance.
- **Factory Method Pattern:** provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created.
- Abstract Factory Pattern: lets you produce families of related objects without specifying their concrete classes.
- **Builder Pattern:** lets you construct complex objects step by step. The pattern allows you to produce different types and representations of an object using the same construction code.
- **Prototype Pattern:** lets you copy existing objects without making your code dependent on their classes.

## Structural Design Patterns
Focuses on how classes and objects are assembled to form larger structures which are efficient and flexible in nature. Structural class patterns use inheritance to compose interfaces or implementations. 

- **Adapter Pattern:** allows objects with incompatible interfaces to collaborate.
- **Bridge Pattern:** lets you split a large class or a set of closely related classes into two separate hierarchies—abstraction and implementation—which can be developed independently of each other.
- Composite Pattern: lets you compose objects into tree structures and then work with these structures as if they were individual objects.
- **Wrapper/Decorator Pattern:** lets you attach new behaviors to objects by placing these objects inside special wrapper objects that contain the behaviors.
- Facade Pattern: provides a simplified interface to a library, a framework, or any other complex set of classes.
- **Proxy Pattern:** lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.
- Flyweight Pattern: lets you fit more objects into the available amount of RAM by sharing common parts of state between multiple objects instead of keeping all of the data in each object.


## Behavioral Design Patterns
Focuses on algorithms and the assignment of responsibilities between objects. Behavioral patterns describe not just patterns of objects or classes but also the patterns of communication between them.

- **Chain of Responsibility Pattern:** lets you pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain.
- **Command Pattern:** turns a request into a stand-alone object that contains all information about the request. This transformation lets you pass requests as a method arguments, delay or queue a request’s execution, and support undoable operations.
- **Iterator Pattern:** lets you traverse elements of a collection without exposing its underlying representation (list, stack, tree, etc.).
- **Mediator Pattern:** lets you reduce chaotic dependencies between objects. The pattern restricts direct communications between the objects and forces them to collaborate only via a mediator object.
- Memento Pattern: lets you save and restore the previous state of an object without revealing the details of its implementation.
- **Observer Pattern:** lets you define a subscription mechanism to notify multiple objects about any events that happen to the object they’re observing.
- State Pattern: lets an object alter its behavior when its internal state changes. It appears as if the object changed its class.
- Strategy Pattern: lets you define a family of algorithms, put each of them into a separate class, and make their objects interchangeable.
- Template Method Pattern: defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps of the algorithm without changing its structure.
- Visitor Pattern: lets you separate algorithms from the objects on which they operate.

<br>

#### Sources
- https://refactoring.guru/design-patterns/behavioral-patterns
- https://www.geeksforgeeks.org/software-design-patterns/
