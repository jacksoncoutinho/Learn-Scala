# Scala Introduction
* Scala, short for **Scalable Language**, is a hybrid functional programming language.
* It was designed by Martin Odersky. It was officially released for java platform in early 2004.
* It is both a **Functional programming** and **Object Oriented programming language** that runs on the JVM! 
* It is a pure object-oriented language in the sense that every value is an object.
* Is a general purpose programming language providing support for functional programming and a strong static type system.  
* Scala compiler compiles your Scala code into **_Java Byte Code_** which can then be executed by the scala command. The scala command is similar to the java command, in that it executes your compiled Scala code.
* Scala has a set of features which differ from Java. Some of these are: 
  - All types are objects  
  - Type Inference  
  - Functions and Objects 
  - Domain Specific Language support  
  - Traits 
  - Closures  
  - Concurrency support 

## Scala Data Types
| Type  | Value Space |
| ------------- | ------------- |
| Boolean  | true or false  |
| Byte  | 8 bit signed value  |
| Short	| 16 bit signed value |
| Char	| 16 bit unsigned Unicode character |
| Int |	32 bit signed value |
| Long |	64 bit signed value |
| Float |	32 bit IEEE 754 single-precision float |
| Double |	64 bit IEEE 754 double-precision float |
| String |	A sequence of characters |
| Unit | Corresponds to no value (void) |
| Null | null or empty reference |
| Nothing | The subtype of every other type; includes no values | 
| Any | The supertype of any type; any object is of type Any |
| AnyRef | The supertype of any reference type |

Example to declare variables:
> var myInt : Int

> var myString : String
* All the data types listed above are objects. There are no primitive types like in Java. This means that you can call methods on an Int, Long etc.
