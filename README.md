Overview
This project is a university project that implements a Fibonacci Heap data structure in Java. Developed in 2021, this implementation provides an efficient heap data structure with advanced operations.

Features

Insert elements with O(1) amortized time complexity

Find minimum element with O(1) time complexity

Delete minimum element with O(log n) amortized time complexity

Meld (merge) heaps efficiently

Decrease key operation with O(1) amortized time complexity

Methods - Heap Operations

isEmpty(): Check if the heap is empty

insert(int key): Insert a new element

deleteMin(): Remove the minimum element

findMin(): Get the minimum element

meld(FibonacciHeap heap2): Merge with another heap

size(): Get the number of elements in the heap

delete(HeapNode x): Remove a specific node

decreaseKey(HeapNode x, int delta): Reduce a node's key

countersRep(): Get an array of tree counters

potential(): Calculate heap potential

totalLinks(): Get total link operations

totalCuts(): Get total cut operations

kMin(FibonacciHeap H, int k): Find k smallest elements
