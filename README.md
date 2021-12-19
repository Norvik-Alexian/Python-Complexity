# Python-Complexity

## Computer Model
* Memory
* CPU

## Resources Requirement Estimation
We should estimate time (CPU) and memory allocation

## Complexity Estimation Approaches
2 main complexity estimates:
* Time Complexity
* Memory (space) Complexity

## Time Complexity
* Big O notation
* Big Omega Notation
* Theta Notation 

'O' stands for the order of magnitude. Big O notation represents the upper bound (maximum) of an algorithm running time.
It represents the worst case of an algorithm time complexity that is the largest amount of time an algorithm can take to 
for execution

## Other Complexities
* N log N

## List in CPython
Lists are implemented as dynamic array (extra memory is allocated by default, resize is called only when limit is reached)

## Dictionary in CPython
Dictionary is implemented as hashtable

## Dictionaries & Hash
* Dictionaries are implemented as Hashtables in Python
* Dictionary keys can be immutable type object.
* Dictionary key objects should have __ hash __ and __ eq __ methods
* Hash(obj) generates hash for object.

## Arrays Basic Manipulations
* Array store sequence of values providing ability to access a value by index in constant time.
* That fact effect arrays algorithms complexity (binary search can be implemented)
* Array disadvantage is memory pre-allocation requirement and it's difficult to extend, shorted, delete or insert elements 
to them.
* Hash tables solve some issues, allow to add/remove/search element in fast manner (constant time)

## Hashtables
* Hashtable is an array that uses hash function
* hash() gets a key as input and provides as output an integer.
* Hashtable has the following columns: index, hash, key, value

## Dictionary Hash Collisions
* Hash Collision - when different objects will have the same hash value (is possible for different hash function)
* To resolve hash collisions CPython dictionary uses open addressing method aka uses both hash and key combinations for 
finding element

## PEP
* PEP - Python Enhanced Proposal
* PEP8 is essential PEP written by Python creator

## Linters
* Linter - is a tool that analyzes source code to flag programming errors, bugs, stylistic errors, and suspicious construct
* Pycharm comes with default linter that is partially based on PEP8
* Flake8 - is one of the advanced linters

