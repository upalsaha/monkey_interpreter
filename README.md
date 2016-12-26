# Monkey Interpreter
Interpreter for Monkey programming language written in Go

Based on [*Writing an Interpreter in Go*](https://interpreterbook.com/) by [Thorsten Ball](https://github.com/mrnugget)

The Monkey programming language was created by Ball to teach interpreter concepts, and has the following features:
- C-like syntax
- variable bindings
- integers and booleans
- arithmetic expressions
- built-in functions
- first-class and higher-order functions
- closures
- string data structure
- array data structure
- hash data structure

Parser algorithms based on Pratt Parsing

Evaluator is built asa tree-walking interpreter, with no preprocessing or compilation, much like Lisp interpreters