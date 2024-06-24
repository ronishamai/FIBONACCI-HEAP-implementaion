# Fibonacci Heap Implementation
This project implements a Fibonacci Heap data structure.

## Description
A Fibonacci Heap is a type of heap data structure that supports efficient operations like insertion, deletion of minimum element, and merging of heaps. It consists of a collection of trees that are min-heap ordered. Each node in the heap stores an integer key.

## Implemented Operations
- **isEmpty()**: Checks if the heap is empty.
- **insert(int key)**: Inserts a new node with the given key into the heap.
- **deleteMin()**: Deletes the node with the minimum key from the heap.
- **findMin()**: Returns the node with the minimum key in the heap.
- **meld(FibonacciHeap heap2)**: Merges another Fibonacci Heap with the current heap.
- **size()**: Returns the number of nodes in the heap.
- **countersRep()**: Returns an array representing the number of trees in the heap at each rank.
- **delete(HeapNode x)**: Deletes the specified node from the heap.
- **decreaseKey(HeapNode x, int decrease)**: Decreases the key of the specified node by the given amount.
- **potential()**: Returns the current potential of the heap.
- **totalLinks()**: Returns the total number of link operations performed since the start of the program.
- **totalCuts()**: Returns the total number of cut operations performed since the start of the program.
- **kMin(FibonacciHeap H, int k)**: Returns an array of the k smallest elements in the heap H.

## Implementation Details
The trees in the heap are ordered chronologically from left to right, and roots of trees are never marked. Specific operations like consolidation and cutting follow detailed rules to maintain heap properties efficiently.

## Complexity
Each function includes a documented analysis of its time complexity in terms of the number of elements n in the heap. The implementation aims for optimal worst-case and amortized time complexities.
