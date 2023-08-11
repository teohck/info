# Learn the Basics

## Introduction

The C programming language is a general purpose programming language, which relates closely to the way machines work. Understanding how computer memory works is an important aspect of the C programming language. Although C can be considered as "hard to learn", C is in fact a very simple language, with very powerful capabilities.

C is a very common language, and it is the language of many applications such as Windows, the Python interpreter, Git, and many many more.

C is a compiled language - which means that in order to run it, the compiler (for example, GCC or Visual Studio) must take the code that we wrote, process it, and then create an executable file. This file can then be executed, and will do what we intended for the program to do.

## Our first program
Every C program uses libraries, which give the ability to execute necessary functions. For example, the most basic function called printf, which prints to the screen, is defined in the stdio.h header file.

To add the ability to run the printf command to our program, we must add the following include directive to our first line of the code:

```
#include <stdio.h>
```