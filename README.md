# Lab 3: Implementing a minimum heap within Java

## Purpose
Familiarize myself with the main functions used to maintain minimum heap properties. Used as lab work for a data structures and algoithms course.

## Content Path
https://github.com/quinnwai//minimum-heap-impl/tree/master/labs/heaps/MinHeap.java

## Overview
All data is stored in an array of Decreaser objects which contain a value, heap reference, and location. The array begins at index 1.

The key implemented functions for this project are `insert`, `decrease`, `extractMin`, and `heapify`.
 -`insert(T thing)`: inserts a node of value `thing` to the bottom of the tree and calls on decrease to maintain the minimum heap property
 -`decrease(int loc)`: recursively replaces the child node at `loc` with its parent up the tree if the child's value is smaller than the parent's value
 -`extractMin()`: extracts the root of the tree, fills in the proper code, and calls on heapify to maintain the minimum heap property.
 -`heapify(int where)`: recursively replaces the child node at `where` with its parent down the treee if child's value is smaller than the parent's value





