## Scala Classes

Classes in Scala are blueprints for creating objects. They can contain methods, values, variables, types, objects, traits, and classes which are collectively called members

###### Objects in Scala: 
* Object O creates a singleton object O as instance of some anonymous class; it can be used to hold static members that are not associated with instances of some class. 
* Object O extends T makes the object O an instance of trait T; you can then pass O anywhere, a T is expected. 
* If there is a class C, then object C is the companion object of class C; note that the companion object is not automatically an instance of C. 

###### Singleton Objects 
* No instantiation 
* Just one, in memory  
* Initialized on first access  
 
###### Companion Object Properties: 
* Are singleton objects that live in the same file as the class of the same name.  
* Companion Objects and companion class can see the private members of each other   
> class CompanionClass{  def greet(){  println("Hello") }  }  
> object CompanionObject{ def main(args:Array[String]){ new CompanionClass().greet() println("Companion object")  }  } 

