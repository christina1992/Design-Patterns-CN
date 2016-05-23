# Design-Patterns-CN
My own examples of some of the design patterns

<em>Design Patterns</em> are used to make your code more flexible and maintainable and are general solutions to common problems.
A pattern is a guideline for flexible and resilient code design.

#Strategy Pattern
The Strategy Pattern defines a family of algorithms,encapsulates each one, and makes them interchangeable. Strategy lets the algorithm vary independently from clients that use it.

#Observer Pattern
The Observer Pattern defines a one-to-many dependency between objects so that when one object changes state, all of it's dependents are notified and updated automaticly. (This pattern is one of the most commonly used patterns)
The advantage of this pattern is LOOSE COUPLING. The goal is to reduse the dependency between the subject and the objects, so that each can VARY independently of each other.
LOOSLY COUPLED - Any changes we make to the subject or the observer never affects the other. That's true loose coupling.

#Decorator Pattern
The Decorator Pattern attaches additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality. (Based on Design Principle #5)
