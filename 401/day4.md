# Day 4 Notes

## Read Linked Lists

### Big O Notation: Algorithm Efficiency

Big O notation describes the efficiency of algorithms or functions based on running time (time efficiency) and memory space (space efficiency).

It measures the worst-case efficiency in terms of time and space.

### Input Size

Input Size refers to the size of the parameter values that an algorithm reads, taking into account the size of each parameter value.
The higher the input size, the more likely that running time and memory space will increase.
The letter 'n' is used to refer to the input size value.

### Units of Measurement

> Time Efficiency

Three measurements of time can be used to evaluate the running time of a function: number of operations executed, number of basic operations executed (most time-consuming operation within the innermost loop), time in milliseconds from start to end of function execution.

> Space Efficiency

Four sources of memory usage can be considered during function run-time: amount of space needed for code, amount of space needed for input data, amount of space needed for output data, amount of space needed for working space during calculation.

### Orders of Growth

Orders of growth describe the overall efficiency of an algorithm by using the input size n and measuring the overall units of space and time required for the given input size n.

As the value of n grows, the Order of Growth represents the increase in running time or memory space.

The following notations describe the relationship of complexity factor to input size n:

O(1) constant efficiency (independent of n)

O(log n) logarithmic efficiency

### Note

Time and Space Complexity are measured differently and should be analyzed separately.
With contemporary computing affording most machines with multiple GB of working memory, algorithm space complexity is not as much of a concern as it used to be.

### Cubic Efficiency

Cubic complexity is a higher degree of what makes quadratic complexity grow at a high rate

Can be illustrated by nesting more loops within an algorithm
A
n example: a simple counter function that keeps track of the number of times the function runs compared to its input value n
This algorithm performs the basic operation count = count + 1 n^3 times, resulting in O(n^3) complexity

### Exponential Efficiency

Exponential complexity represents rapidly growing complexity such that for any input size n, the same number of iterative or recursive loops is performed as n

Example: finding the corresponding Fibonacci value for a given index in the Fibonacci sequence

The algorithm passes the two preceding numbers into a recursive loop, adding up all the 1 values for all the call stack frames called, resulting in O(2^n) complexity growth

### Factorial Efficiency

Factorial complexity means space and time requirements grow extremely fast relative to input size

Often happens when calculating all possible permutations of something like a string or array

Example: finding all permutations of a deck of cards

The algorithm receives 3 parameters: generatedCombinations, currentCardCombination, and cardsToCombine

The complexity increases as the initial deck of cards is looped through and the function is recursively called with different combinations of cards each time, resulting in O(n!) complexity growth.

### Linked Lists

A linked list is a data structure in which objects are connected to one another in a linear fashion. Each object, or "node," in the linked list contains a reference to the next node in the sequence. This makes linked lists a popular choice for implementing dynamic data structures such as stacks, queues, and more.

### Advantages of Linked Lists

Dynamic size: Linked lists can grow or shrink as needed, making them ideal for cases where the number of elements is not known in advance.

Efficient Insertion and Deletion: Adding or removing elements from a linked list can be done quickly, as only the pointers need to be updated.

No need for shifting elements: Linked lists do not require shifting elements around when inserting or deleting, as arrays do.

### Disadvantages of Linked Lists

No constant time access: Unlike arrays, accessing elements in a linked list requires iterating through the list until the desired element is found.

More memory overhead: Each node in a linked list requires a separate memory allocation, which can result in more memory overhead compared to arrays.

### Types of Linked Lists

Singly Linked List: Each node in a singly linked list has a reference to the next node in the sequence.

Doubly Linked List: Each node in a doubly linked list has a reference to the next node as well as the previous node in the sequence.

Circular Linked List: In a circular linked list, the last node in the list points back to the first node, creating a circular loop.

#### Things I want to know more about

> All of this!

#### Sources

https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html

https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html

Click to return [Home!](../README.md)
