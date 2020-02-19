# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Polymorphism means that something can have many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
This allows us to treat a class as another type of class at the same time. This is used in Java
in the form of abstract classes

3. What can we use to implement polymorphism in Java?
We can implement polymorphism in Java using abstract classes that others inherit from.
We can also use interfaces that force new classes to abide to certain 'rules'.

4. How many 'forms' can an object take when using polymorphism?
As long as an object abides to either the abstract class or the interface, as many as you want.

5. Give an example of when you could use polymorphism.
An example would be able to create a 'device' class and make instances such as computer or printer
that abide by the idea that they are 'devicable'


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
Composition is when you want to give things certain abilities without polluting their class hierarchy which things that don't concern it
"High-level modules should not depend on low-level modules. Both should depend on abstractions."

7. When would you use composition? Provide a simple example in Java.
When multiple objects do a similar things you can abstract their functionality into an interface

8. What is/are the advantage(s) of using composition?
Can reuse code
change the implementation of a class used in a composition without adapting any external clients

9. When an object is destroyed, what happens to all the objects it is composed of?
The other objects are unaffected, which is helpful keeping our code reliable
