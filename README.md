# SOLID Principles
SOLID Principles code sample using C# .NET 5

###  Single Responsibility Principle:
- It means that everything in a class should be related to a single purpose
- There can be many members in a class as long as they are related to a single responsibility
- User registration service should have different service for email sending and logging
### Open Closed Principle
- States that the software entities (classes or methods) should be open for extension but closed for modification.
- Any new functionality should be implemented by adding new classes, attributes, and methods, instead of changing the current ones or existing ones.
- Basically, we should strive to write a code that doesn’t require modification every time a customer changes its request
### Liskov Substitution Principle
- States that child class objects should be able to replace parent class objects without compromising application integrity
- "S is a subtype of T, and then objects of type T may be replaced with an object of type S"
- Derived types must be completely substitutable for their base types.
### Interface Segregation Principle: 
- No client should be forced to depend on methods it does not use.
- One heavy interface needs to be split into many smaller and relevant interfaces so that the clients can know about the interfaces that are relevant to them.
- States that we should reduce code objects down to the smallest required implementation thus creating interfaces with only required declarations.
- An interface that has a lot of different declarations should be split up into smaller interfaces.
- It increases the readability and maintainability of our code.
### Dependency Inversion Principle
- High-level modules should not depend on low-level modules. Both should depend on abstractions.
- Abstraction should not depend on details. Details should depend on abstraction.
- The interaction between high level and low-level modules should be thought of as an abstract interaction between them
