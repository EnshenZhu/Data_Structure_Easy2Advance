# Data_Structure_Easy2Advance

This repository is derived from the Data Structures Easy to Advanced Course - Full Tutorial from a Google Engineer (https://www.youtube.com/watch?v=RBSGKlAvoiM&ab_channel=freeCodeCamp.org)

## What is a Data Structure

A data structure (DS) organizes data to make it be used (access and edit) effectively.

## Why Data Structure

1. They are essential ingredients in creating fast and robust algorithms.
2. They help to manage and organize data.
3. They make code cleaner and easier to understand.

## Abstract Data Type vs Data Structure

### Abstract Data Type

An abstract data type (ADT) is an abstraction of a data structure that provides only the interface to which a data structure must adhere. The interface does not specify how something should be implemented or in what programming languages.

### Examples - Abstraction (ADT) & Implementation (DS)

| Type    | Example                                                                  |
|---------|--------------------------------------------------------------------------|
| List    | Dynamic Array / Linked List / *They allow adding. removing and indexing* |
| Queue   | Linked List-based Queue / Array-based Queue / Stack-based Queue          |
| Map     | TreeMap / Hash Map / Hash Table                                         |
| Vehicle | Golf Cart / Bicycle / Smart Car                                          |

## Computational Complexity Analysis

### Big-O Notation

Big-O Notation gives an upper bound of the complexity in the **worst** case, helping to quantify performance as the input size becomes **arbitrarily large**.

#### Examples

n -> The size of the input
Complexities are ordered from smallest to largest

| Complexity        | Express                                                                                |
|-------------------|----------------------------------------------------------------------------------------|
| Constant Time     | $O(1)$                                                                                 |
| Logarithmic Time  | $O(log(n))$                                                                            |
| Linear Time       | $O(n)$                                                                                 |
| Linearithmic Time | $O(nlog(n))$ [normally it is a O(log(n)) loop wrapped with a O(n) loop, or vice versa] |
| Quadratic Time    | $O(n^2)$                                                                               |
| Cubic Time        | $O(n^3)$                                                                               |
| Exponential Time  | $O(b^n)$,b>1                                                                           |
| Factorial Time    | $O(n!)$                                                                                |

### Big-O Properties

$O(n+c)=O(n)$; $O(cn)=O(n), c>0$

Let f be a function that describes the running time of a particular algorithm for an input of size n:
$f(n)=7(log(n)^3)+15n^2+2n^3+8$; $O(f(n))=O(n^3)$ because $n^3$ is mostly dominant in this case.

### Classic Big-O Examples

1. Finding all subsets of a set - $O(2^n)$
2. Finding all permutations of a string - $O(n!)$
3. Sorting using mergesort - $O(nlog(n))$
4. Iterating over all the cells in a matrix of size n by m - $O(nm)$

## Static and Dynamic Arrays (Part 1/2)

### Discussion and examples of Arrays

#### What is an Array?

A static array is a fixed-length container containing n elements **indexable** from the range [0,n-1]

**Q: What is meant by being 'indexable'**
A: This means that each slot/index in the array can be referenced with a number. (Static arrays are given as contiguous chunks of memory.)

#### When and where is a static Array used?

1. Storing and accessing sequential data.
2. Temporarily storing objects.
3. Used by I/O routines as buffers.
4. 
