## What is it?

1. A simple stack-based virtual machine that runs C in the browser.

2. An interactive tutorial that covers C, how the VM works, and how the language is compiled, everything from the ground up.

## Why?

This project demystifies compilers without getting lost in unnecessary details. 
MiniC visually explores how a compiler can break down the C language into simple instructions and how those are executed by a virtual CPU. 

![alt text](/gif/both.gif)

## Can I see it?

1. [Sandbox](https://vasyop.github.io/miniC-hosting)

2. Tutorial (for people with 0 programming experience or willing to learn C) : 
    * [Part 1](https://vasyop.github.io/miniC-hosting/?0) - Introduction
    * [Part 2](https://vasyop.github.io/miniC-hosting/?1) - Expressions (part 1)
    * [Part 3](https://vasyop.github.io/miniC-hosting/?2) - Expressions (part 2)
    * [Part 4](https://vasyop.github.io/miniC-hosting/?3) - Variables and program structure

## Subscribe

Get [notified](https://github.us20.list-manage.com/subscribe/post?u=2790571880963241ec5dd7d11&id=0e2d1b34de) when new tutorials are released.

## Feedback

Join the discussion on our [subreddit](https://www.reddit.com/r/minic/).

## Support
Consider [supporting](https://github.com/vasyop/miniC-hosting/blob/master/support.md) the project.

## Documentation

### Virtual Instruction Set



### Missing language features

* only bool, int, char and pointers as data types and they all have the same size in memory

* no malloc, but operator new is working (like in C++), 

* no static arrays and structs (dynamic arrays and pointer to structs work fine).
  
* no arrays of structs (arrays of pointers to structs works fine).
  
* no for and switch statements

* no preprocessor directives
  
* no bitwise operators
  
* no ++, --, ternary operators
  
* no union and no enum
  
* no global variables

* no function pointers

* no free / delete operator

* no function overloading
