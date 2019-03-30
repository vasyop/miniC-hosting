## What is it?

1. A simple stack-based virtual machine that runs C (missing features below) in the browser.

2. The beginning of an interactive tutorial that covers C, how the VM works, and how the language is compiled. It series covers C from the ground up, without having to take anything for granted.

## Why?

7 years ago I was writing my very first line of code.

I knew I liked programming, but I didn't really know what I was doing. 
What's going on?
Why do I have to write this?
What's happening under the hood?
I was frustrated and confused.
I've always hated learning things by heart without really understanding them.

For years I had wished someone could break programming down and teach it from the groud up, concepts first, details later. 
If someone could answer my "why?" questions, everything would be much easier to learn.

With this project, I want to teach programming one step at a time, from the very ground up.

And no, it's not going to take forever. 
I am not covering unnecessary details, those are easy to look up.

## Can I see it?

1. [Sandbox](https://vasyop.github.io/miniC-hosting)

2. Tutorial (for people with 0 programming experience or willing to learn C) : 
    * [Part 1](https://vasyop.github.io/miniC-hosting/?0) - Introduction
    * [Part 2](https://vasyop.github.io/miniC-hosting/?1) - Expressions (part 1)
    * [Part 3](https://vasyop.github.io/miniC-hosting/?2) - Expressions (part 2)

## Subscribe

Get [notified](https://github.us20.list-manage.com/subscribe/post?u=2790571880963241ec5dd7d11&id=0e2d1b34de) when new tutorials are released.

## Feedback

Join the discussion on our [subreddit](https://www.reddit.com/r/minic/).

## Support
Consider [supporting](https://github.com/vasyop/miniC-hosting/blob/master/support.md) the project.

## Missing language features

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
