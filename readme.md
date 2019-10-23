
// http://www.dummies.com/go/designpatternsfd1e

 what is a design pattern?

a design pattern is a tested solution to a standard programming problem

Design patterns are all about reusable solutions to common problems in software designing that occur in real-world application development.

deign patterns are solutions to programming problems that automatically implment good design techniques. someone has already faced the issues youre facing, solved them and is willing to show what the best techniques are.

gang of four book
 list 23 design patterns.

 Who are the Gang of Four?

The Gang of Four are the authors of the book, "Design Patterns: Elements of Reusable Object-Oriented Software". This important book describes various development techniques and pitfalls in addition to providing 23 object-oriented programming design patterns. The four authors are Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides.

///concrete classes
A concrete class is a class that has an implementation for all of its methods. They cannot have any unimplemented methods. It can also extend an abstract class or implement an interface as long as it implements all their methods. It is a complete class and can be instantiated.

/////////////////////////////////////////////////////////////////////////
I like thinking about design pattens in terms of my classes being 'people,' and the patterns are the ways that the people talk to each other.

So, to me the factory pattern is like a hiring agency. You've got someone that will need a variable number of workers. This person may know some info they need in the people they hire, but that's it.

So, when they need a new employee, they call the hiring agency and tell them what they need. Now, to actually hire someone, you need to know a lot of stuff - benefits, eligibility verification, etc. But the person hiring doesn't need to know any of this - the hiring agency handles all of that.

In the same way, using a Factory allows the consumer to create new objects without having to know the details of how they're created, or what their dependencies are - they only have to give the information they actually want.
///////////////////////////////////////////////////////////////////////