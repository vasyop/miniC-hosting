# What is it?

A simple stack-based virtual machine that runs C (missing features below) in the browser.

It is also the beginning of an interactive tutorial that covers C, how the VM works, and how the language is compiled.

# Why?

This project is made as an experiment to see if C can be learned easier if the lower level is covered in paralel.

# Can I see it?

Demo: https://vasyop.github.io/miniC-hosting

Tutorial (for people with 0 programming experience) : 
* part 1 : https://vasyop.github.io/miniC-hosting/?0

# Missing language features

* static arrays and structs (dynamic arrays and pointer to structs work fine).
  
* Arrays of structs (arrays of pointers to structs works fine).
  
* for, switch statements
  
* bit operators
  
* only bool,int,char as primitive types and they all have the same size in memory
  
* ++,--,ternary
  
* union,enum
  
* n global variables
  
* mcros

* delete / delete[]

* function overloading
