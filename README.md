# What is it?

1. A simple stack-based virtual machine that runs C (missing features below) in the browser.

2. The beginning of an interactive tutorial that covers C, how the VM works, and how the language is compiled.

# Why?

This project is made as an experiment to see if C can be learned easier if the lower level is covered in parallel.

# Can I see it?

Demo: https://vasyop.github.io/miniC-hosting

Tutorial (for people with 0 programming experience) : 
* part 1 : https://vasyop.github.io/miniC-hosting/?0

# Consider [supporting](https://github.com/vasyop/miniC-hosting/blob/master/support.md) the project

# Missing language features

* operator new is working (like in C++), no malloc

* static arrays and structs (dynamic arrays and pointer to structs work fine).
  
* Arrays of structs (arrays of pointers to structs works fine).
  
* for, switch statements

* preprocessor directives
  
* bit operators
  
* only bool,int,char as primitive types and they all have the same size in memory
  
* ++,--,ternary
  
* union,enum
  
* global variables
  
* macros

* delete / delete[]

* function overloading
