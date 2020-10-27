# LAB 05 Report

## Add your name

## Go Type System Overview

Go supports several basic types (`string`, `bool`, and numeric types) and composite types (pointer types, struct types, function types, container types - arrays, slices, maps, interface types, and channel types - for concurrency). Additionally, Go allows programmers to define new types using `type` keyword, with an instance of a type called a value, of the type. Additionally, in Go some types can have methods, which are also called member functions. 

### 1. Learning Data Types in Go 

1.1. Go through the tutorial on data types at the [A Tour of Go](https://tour.golang.org), specifically section under "Basics" on "More types".

In `gotypes1.go` create a Go program that incorporates the following data types (at least one of each):
- pointer, 
- struct,
- array, 
- maps (use `make` function).

Your program should use the types listed above for a specific task or several tasks and it should output something demonstrating the use of these types. It should not closely resemble the examples provided in the tutorial or found online. The program does not need to be complicated or implement a specific application - in this part of the lab, you are just extending your knowledge of composite types in Go.

TODO: Describe your implemented program and how you used the required components. Provide the output of your program using a code block.

1.2. Now, go through the tutorial on "Methods and interfaces" at the [A Tour of Go](https://tour.golang.org). 

In `gotypes2.go` create a Go program that incorporates the following (at least one of each):

- type definition (using `type` keyword),
- two methods: one defined on struct types, the other on non-struct types, 
- interface type,
- Image interface,
- type switch.

Your program should use the concepts listed above for a specific task or several tasks and it should output something demonstrating the use of these concepts. It should not closely resemble the examples provided in the tutorial or found online. The program does not need to be complicated or implement a specific application - in this part of the lab, you are just extending your knowledge of composite types in Go.

TODO: Describe your implemented program and how you used the required components. Provide the output of your program using a code block.

### 2. Comparing and Contrasting Type Systems

As you may remember a "type system" is a mechanism that define types, associates types with certain
language constructs, and provides rules for type equivalence, type compatibility, and type inference.
Type equivalence rules decide when the types of two values are the same, whereas type compatibility rules check when a value of a given type can be used in a given context (the process known as "type checking"), and type inference rules define the type of an expression given components of the expression. 

*Task:* Using other programming languages, such as C, Java and JavaScript, compare the type systems of the Go programming language to other languages, focusing on three rules of a typical type system (type equivalence, type checking and type inference). How are these three rules handles in Go and other languages? Identify similarities and differences in type systems between Go and at least two other programming languages. Provide specific code snippets or pseudocode as examples when you provide your explanation.

TODO: Provide your answer.

### Reflection

What were your biggest learning points during this lab and what challenges have you encountered during this lab?

## I Adhered to the Code of Conduct Guide while Completing this Lab Project.

TODO: Add Your Name Here
