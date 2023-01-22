# GRASP
## Defination
General Responsibility Assignment Software Patterns (or Principles), abbreviated GRASP, is a set of "nine fundamental principles in object design and responsibility assignment

## Patterns
- **Information expert** : used to determine where to delegate responsibilities such as methods, computed fields, and so on.
- **Creator** : Lead us to determine who is the best person to create objects.
- **Controller** : How are requests delegated from UI layer objects to domain layer objects, including coordinating the system operation?
- **Indirection** : Indirection introduces an intermediate unit to 
communicate between the other units, so that 
the other units are not directly coupled.
- **Low coupling** :  How strongly the objects are connected to each other?
- **High cohesion** : How are the operations of any element are functionally 
related?
- **Polymorphism** : Responsibility for defining the variation of behaviors based on type is assigned to the type for which this variation happens.
- **Protected variations** : It provides a well defined interface so that the there will be no affect on other units.
- **Pure fabrication** : create a class that does not map to a domain object, and let it achieve this new responsibility in a cohesive way.

## Nice to remember
- `Information expert` lead us to `high cohesion`.
- `Controller` in `GRASP` is more or less like controller in `MVC`.
- `Controller` object can be part of `application/service layer`.
- We always prefer `low coupling`.
- We always prefer `high cohesion`.

## Source(s)
- [Wikipedia](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))
- [Boldare](https://www.boldare.com/blog/solid-cupid-grasp-principles-object-oriented-design/#what-is-solid-and-why-is-it-more-than-just-an-acronym?-what-is-grasp-and-why-is-it-challenging?)
- [Colorado State University](https://home.cs.colorado.edu/~kena/classes/5448/f12/presentation-materials/rao.pdf)
- [fluentcpp](https://www.fluentcpp.com/2021/06/23/grasp-9-must-know-design-principles-for-code/)