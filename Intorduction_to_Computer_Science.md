## Week 0
* Computer Science is just a way of solving problems. There is a input and output. In middle is blackbox.
* computer speaks only binary ex: 001 is 1, 011 is 3 , 110 is 5
* Computer just turns on/off different switches to represent various numbers.
* We collectively agreed long ago to use different numbers to represent letters. Ex: A is 65 which 1000001.
* ASCII - American Standard Code for Information Interchange - standard agreed for representing numbers and letters. Uses only 8 bits
* Unicode uses 8, 16, 32 bits to represent characters, symbols, emojis in various languages. it is a superset of ascii
* Algorthim is a set of instructions for solving a problem.
* lot of problem solving is just utilizing existing intution and translating it in a way other humans or machines understand.

### Basic things in algorthim pseudocode
* Functions - tells computer what to do
* Conditions - asks a boolean expression whether to run the code below or not
* Boolean Expressions
* loops - repeat code again
* Variables
* Threads
* Events

* You can use **scratch.mit.edu** to play with simple visual programs

## Week 1
* Program to print "hello world" in c
```c
#include <stdio.h>

int main(void)
{
  printf("hello world\n");
}
```

* We can use **sandbox.cs50.io** for programming in c
* compiler is a algorthim which converts source code(like python, C, Java) to machine code(1's and 0's, machine readable format)
```c
clang hello.c # to compile the c program to give a.out which contains machine code
.\a.out - to run the output
```

* **\n** tells the computer to move to new line

