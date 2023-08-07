# Software Design Methodologies

## Design Strategies

### There are three principle design strategies used in software engineering:

- Structured design
- Function oriented design
- Object oriented design


### 1. What do we mean by coupling and cohesion when discussing structured design?

Coupling describes how closely dependent and modules are, modules are self-contained units of code which are dedicated to a specific function.




The degree of coupling can vary from low to high, usually referred to as loose and tight coupling.
Loose coupling means modules are less dependent on each other and therefore can operate more independently. A benefit of loose coupling is that if your software needs to be expanded it is easier as changes in modules are less likely to have significant impact on others.
Tight coupling means that units of code (e.g. classes) are dependent on each other. One benefit of tight coupling is that you can maintain consistency between modules.




On the other hand Cohesion refers to the extent to which the elements within a module are related to each other. Cohesion also can vary from low to high. High cohesion means modules are highly related this leads to modules being more self contained and consistent. On the other hand low cohesion results in the module performing a myriad of tasks.


### 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

Bottom up design is a design process which starts with the smaller components of the system which are then built upon to get to the larger system.
Top-down design starts with a larger view and aims to then break down the system into smaller and smaller manageable parts. This best describes function oriented design which focuses on breaking down the systems functionality into smaller, independent functions that perform specific roles.



### 3. In which design methodology would a class diagram be most useful?

Class diagrams in the unified model language is a static structure that aims to describe the structure of a system by depicting classes, properties, methods and the relations between objects. A class diagram is most useful for object-oriented design since it revolves around the notion of objects. 



### 4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

Encapsulation: Hiding the internal state of objects and exposing interactions through well-defined interfaces (public methods).
Abstraction: Creating classes to represent real-world entities and abstracting their common characteristics.
Inheritance: Allowing classes to inherit attributes and behaviours from other classes, forming a hierarchical relationship.
Polymorphism: Enabling objects to take multiple forms and allowing different classes to implement the same methods differently.



### 5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

Strategy pattern is a design pattern which defines a group of interchangeable algorithms or strategies and allows them to be selected and used dynamically at runtime.


In an object-oriented system, the pattern could be implemented by creating a strategy interface/abstract class, strategy classes that implement different algorithms, and a context class that holds and delegates to the current strategy.


In a functional system, the pattern is implemented using functions and higher-order functions, passing strategies as arguments to achieve similar encapsulation and dynamic behaviour.



### 6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

For creating an online payment system that is not tied to a particular sector I would use object oriented design. Since
object oriented design allows you to abstract the common aspects of different sectors into reusable classes and interfaces. The principles of polymorphism and inheritance promote consistency in the core functionality while allowing sector-specific variation.