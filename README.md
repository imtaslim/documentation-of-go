# Documentation of go

Go is a popular programming language.
Go is used to create computer programs.

<h2>Go Introduction</h2>
<h3>What is Go?</h3>

1. Go is a cross-platform, open source programming language
2. Go can be used to create high-performance applications 
3. Go is a fast, statically typed, compiled language that feels like a dynamically typed, interpreted language
4. Go was developed at Google by Robert Griesemer, Rob Pike, and Ken Thompson in 2007
Go's syntax is similar to C++

<h3>What is Go Used For?</h3>

1. Web development (server-side)
2. Developing network-based programs
3. Developing cross-platform enterprise applications
4. Cloud-native development

<h3>Facts about Go</h3>

1. Statically typed
2. Fast run time
3. Compiled
4. Fast compile time
5. Supports concurrency through goroutines and channel
6. Has automatic garbage collection
7. Does not support classes and objects
8. Does not support inheritance

<h3>Notes:</h3>

1. Compilation time refers to translating the code into an executable program
2. Concurrency is performing multiple things out-of-order, or at the same time, without affecting the final outcome
3. Statically typed means that the variable types are known at compile time

<h3>Go Syntax</h3>
A Go file consists of the following parts:

1. Package declaration
2. Import packages
3. Functions
4. Statements and expressions

<h3>Go Statements</h3>
fmt.Println("Hello World!") is a statement.

In Go, statements are separated by ending a line (hitting the Enter key) or by a semicolon ";".

Hitting the Enter key adds ";" to the end of the line implicitly (does not show up in the source code).

The left curly bracket { cannot come at the start of a line.

<h1> Let's get started</h1>

NOTE
```
Function calls

A function is a chunk of code that you can call from other places in your program.
When calling a function, you can use arguments to provide the function with data.
```
NOTE
```
Types
   
Values in Go are classified into different types, which specify what the values can be used for.
Math operations and comparisons between different types are not allowed, but you can convert
a value to a new type if needed.
Go variables can only store values of their declared type.
```
## BULLET POINTS
```
* Go is statically typed. If you use the wrong type of value in the wrong place, Go will let you know.
* A package is a group of related functions and other code. Before you can use a package’s functions within a Go file, you need to import that package.
* A string is a series of bytes that usually represent text characters.
* A rune represents a single text character.Go’s two most common numeric types are int, which holds integers, and float64, which holds floating-point numbers.
* The bool type holds Boolean values, which are either true or false.
* A variable is a piece of storage that can contain values of a specified type.
* If no value has been assigned to a variable, it will contain the zero value for its type. Examples of zero values include 0 for int or float64 variables, or "" for string variables.
* You can declare a variable and assign it a value at the same time using a := short variable declaration.
* A variable, function, or type can only be accessed from code in other packages if its name begins with a capital letter.
* The go fmt command automatically reformats source files to use Go standard formatting. You should run go fmt on any code that you plan to share with others.
* The go build command compiles Go source code into a binary format that computers can execute.
* The go run command compiles and runs a program without saving an executable file in the current directory.
```
## Escape sequence Value
<table>
    <tr>
        <td>\n</td>
        <td>A newline character.</td>
    </tr>
    <tr>
        <td>\t</td>
        <td>A tab character.</td>
    </tr>
    <tr>
        <td>\"</td>
        <td>Double quotation marks.</td>
    </tr>
    <tr>
        <td>\\</td>
        <td>A backslash.</td>
    </tr>
</table>

<h1>Conditionals and Loops</h1>

NOTE
```
Loops

Loops cause a block of code to execute repeatedly.
One common kind of loop starts with the keyword “for”, followed by an init statement that initializes a variable, a condition expression that determines when to break out of the loop, and a post statement that runs after each iteration of the loop.
```
## BULLET POINTS
```
* A method is a kind of function that’s associated with values of a given type.
* Go treats everything from a // marker to the end of the line as a comment—and ignores it.
* Multiline comments start with /* and end with */. Everything in between, including newlines, is ignored.
* It’s conventional to include a comment at the top of every program, explaining what it does.
* Unlike most programming languages, Go allows multiple return values from a function or method call.
* One common use of multiple return values is to return the function’s main result, and then a second value indicating whether there was an error.
* To discard a value without using it, use the _ blank identifier. The blank identifier can be used in place of any variable in any assignment statement.
* Avoid giving variables the same name as types, functions, or packages; it causes the variable to shadow (override) the item with the same name.
* Functions, conditionals, and loops all have blocks of code that appear within {} braces.
* Their code doesn’t appear within {} braces, but files and packages also comprise blocks.
* The scope of a variable is limited to the block it is defined within, and all blocks nested within that block.
* In addition to a name, a package may have an import path that is required when it is imported.
* The continue keyword skips to the next iteration of a loop.
* The break keyword exits out of a loop entirely.
```
