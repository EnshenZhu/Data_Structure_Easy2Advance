# Data_Structure_Easy2Advance

This repo is derived from the Data Structures Easy to Advanced Course - Full Tutorial from a Google Engineer (https://www.youtube.com/watch?v=RBSGKlAvoiM&ab_channel=freeCodeCamp.org)

## What is a Data Structure
A data structure (DS) is a way of organizing data so that it can be used (access and edit) effectively.

## Why Data Structure
1. They are essential ingredients in creating fast and powerful algorithms.
2. They help to manage and organize data.
3. They make code cleaner and easier to understand.

## Abstract Data Type vs Data Structure

### Abstract Data Type
An abstract data type (ADT) is an abstraction of a data structure which provides only the interface to which a data structure must adhere to.
The interaface does not give any specific details about how something should be implemented or in what programming languages.

### Examples - Abstraction (ADT) & Implementaion (DS)
| Type | Example |
| --- | --- |
| List | Dynamic Array / Linked List / *They allow adding. removing and indexing* |
| Queue | Linked List based Queue / Array based Queue / Stack based Queue |
| Map | Tree Map / Hash Map / Hash Table |
| Vehicle | Golf Cart / Bicycle / Smart Car |

## Computational Complexity Analysis

### Big-O Notation
Big-O Notation gives an upper bound of the complexity in the **worst** case, helping to quantify performance as the input size becomes **arbitarrily large**.

#### Examples
n -> The size of the input
Complexities ordered in from smallest to largest
| Complexity | Express |
| --- | --- |
| Constant Time | O($1$) |
| Logarithmic Time | O($log(n)$) |
| Linear Time | O($n$) |
| Linearithmic Time | O($nlog(n)$) [normally it is a O(log(n)) loop wrapped with a O(n) loop, or vice versa] |
| Quadric Time | O($n^2$) |
| Cubic Time | O($n^3$) |
| Exponential Time | O($b^n$) b>1 |
| Factorial Time | O($n!$) |

### Big-O Properties

$O(n+c)=O(n)$
$O(cn)=O(n), c>0$

Let f be a function that describes the running time of a particular algorithm for an input of size n:
$f(n)=7(log(n)^3)+15n^2+2n^3+8$