# read linked list

## What is a Linked List
A Linked List is a sequence of Nodes that are connected/linked to each other. 

* the most feature of a Linked List is that each Node references the next Node

## Types of linked list structure
1. Linear data structures:there is a sequence and an order to how they are constructed and traversed.

2. Non-linear data structures: items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.

## Parts of a linked list
series of nodes:the elements of the list Each node It has just two parts:
* data, or the information that the node contains 
* a reference to the next node(pointer references to — the next node in the list)

### some names
* head: the first node
* next node.
* The end of the list isn’t a node, but rather a node that points to null, or an empty value.


## advantage of a linked list

In contrast to an array, which stores data contiguously in memory, a linked list can easily insert or remove nodes from the list without reorganization of the entire data structure.


## Traversal:
To traversing a linked list, your best way to do that through while() loop we'll not be able to use for() or forEach. The most helpful when traversing is current to know where you are.

## Adding a Node:
Set Current to equal Head
use Add()

## Print Out Nodes:
go to Head
Create a loop
before the loop ends set the Current to the next node.

## Big O Notation
is a way of evaluating the performance of an algorithm.

* Big O Notation takes into account: the speed and efficiency with which something functions when its input grows to be any (crazy big!) size.
  * O(1) function takes constant time, which is to say that it doesn’t matter how many elements we have, or how huge our input is: it’ll always take the same amount of time and memory to run our algorithm.
  * O(n) function is linear, which means that as our input grows (from ten numbers, to ten thousand, to ten million), the space and time that we need to run that algorithm grows linearly.
  * O(n²) function, which clearly takes exponentially more time and memory the more elements that you have.
