# polymorphism_composition_homework

Polymorphism
What does the word 'polymorphism' mean?
Polymorphism describes situations in which something occurs in several different forms.


What does it mean when we apply polymorphism to OO design? Give a simple Java example.

public interface IBuy {
  public String buy();
}

public class Cola implements IBuy {
    public String buy() {
      return "buying a cola";
    }
}

public class Sandwich implements IBuy {
    public String buy() {
      return "buying a sandwich";
    }
}

What can we use to implement polymorphism in Java?

Inheritance and Interfaces

How many 'forms' can an object take when using polymorphism?

Unlimited?

Give an example of when you could use polymorphism.



Composition and Aggregation
What do we mean by 'composition' in reference to object-oriented programming?

An object being composed of other objects.

When would you use composition? Provide a simple example in Java.

A unicycle class, that contains a wheel class. The Unicycle cannot exist without the wheel.

Give a difference between composition and aggregation?

Conpostion is when the object is destroyed all of its behaviours are also destroyed. Aggregation iis different in that the objects can exist independently from the object which contains them.

What is/are the advantage(s) of using composition/aggregation?

There is great code reusability.

When using composition, when an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed.

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

They continue to exist.
