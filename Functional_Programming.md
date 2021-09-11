# **Functional-Programming**

Functional programming is a programming paradigm in which we try to bind everything in pure mathematical functions style. It is a declarative type of programming style. Its main focus is on “what to solve” in contrast to an imperative style where the main focus is “how to solve”. It uses expressions instead of statements. An expression is evaluated to produce a value whereas a statement is executed to assign variables.


## Functional programming vs Object-oriented programming :-

It’s important to compare these programming ways to identify the differences and identify correct usage of functional programming. Primary concern of functional programming is not ‘ how to do it ’ but rather ‘ what to do ’. Major difference could be identified as using the declarative programming model in functional programming rather than it’s competitor’s imperative programming model.


## Functional Programming is based on Lambda Calculus :-

Lambda calculus is a framework developed by Alonzo Church to study computations with functions. It can be called the smallest programming language in the world. It gives the definition of what is computable. Anything that can be computed by lambda calculus is computable. It is equivalent to the Turing machine in its ability to compute. It provides a theoretical framework for describing functions and their evaluation. It forms the basis of almost all current functional programming languages. 

## Concepts of functional programming:

Pure functions
Recursion
Referential transparency
Functions are First-Class and can be Higher-Order
Variables are Immutable

## Advantages and Disadvantages of Functional programming

Advantages:

* Pure functions are easier to understand because they don’t change any states and depend only on the input given to them. Whatever output they produce is the return value they give. Their function signature gives all the information about them i.e. their return type and their arguments.
* The ability of functional programming languages to treat functions as values and pass them to functions as parameters make the code more readable and easily understandable.
* Testing and debugging is easier. Since pure functions take only arguments and produce output, they don’t produce any changes don’t take input or produce some hidden output. They use immutable values, so it becomes easier to check some problems in programs written uses pure functions.
* It is used to implement concurrency/parallelism because pure functions don’t change variables or any other data outside of it.
* It adopts lazy evaluation which avoids repeated evaluation because the value is evaluated and stored only when it is needed.

Disadvantages:

* Sometimes writing pure functions can reduce the readability of code.
* Writing programs in recursive style instead of using loops can be bit intimidating.
* Writing pure functions are easy but combining them with the rest of the application and I/O operations is a difficult task.
* Immutable values and recursion can lead to decrease in performance.

## Applications:

It is used in mathematical computations.
It is needed where concurrency or parallelism is required.

