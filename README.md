# java-study-notes
## Study notes for java

### Introduction
These are my personal study notes inspired from jwasham's coding interview university https://github.com/jwasham/coding-interview-university
but this list is more specific to java while jwasham's repository covers other languages as well.
Feel free to fork / star / download ... whatever you want. 

## Table of contents
- [Big O notations](#big-o-notation)
- [Data Structures](#data-structures)
  - [Arrays](#arrays)
  - [ArrayList](#arraylist)
  - [LinkedList](#linkedlist)
  - [Stack](#stack)
  - [Queue](#queue)
  - [HashTable](#hashtable)
  - [Set](#set)
 
 - [Trees](#trees)
  - [Series](#series)
  - [BFS and DFS](#bfsdfs)
  - [Binary Search Tree](#bst)
  - [Heap / Priority Queue / Binary Heap](#heap)
  
- [Sorting](#sorting)
 
- [Graphs](#graphs)
  
- [Recursion](#recursion)

- [Dynamic Programming](#dynamic_programming)

- [Object Oriented Programming](#oop)

- [Design Patterns](#design_patterns)

- [Combinatorics and Probability](#combinatorics-probability)

- [NP, NP-Complete and Approximation Algorithms](#np-approx)

- [Caches](#caches)

- [Processes and Threads](#processes-threads)

- [Testing](#testing)






#big-o-notation
We know there are tools to measure how fast a program runs. There are programs called profilers which measure running time in milliseconds and can help us optimize our code by spotting bottlenecks. While this is a useful tool, it isn't really relevant to algorithm complexity. Algorithm complexity is something designed to compare two algorithms at the idea level — ignoring low-level details such as the implementation programming language, the hardware the algorithm runs on, or the instruction set of the given CPU. We want to compare algorithms in terms of just what they are: Ideas of how something is computed. Counting milliseconds won't help us in that. It's quite possible that a bad algorithm written in a low-level programming language such as assembly runs much quicker than a good algorithm written in a high-level programming language such as Java. So it's time to define what a "better algorithm" really is.

Complexity analysis allows us to measure how fast a program is when it performs computations. Examples of operations that are purely computational include numerical floating-point operations such as addition and multiplication; searching within a database that fits in RAM for a given value; determining the path an artificial-intelligence character will walk through in a video game so that they only have to walk a short distance within their virtual world; or running a regular expression pattern match on a string. Clearly, computation is ubiquitous in computer programs.



#References:
-http://discrete.gr/complexity/
