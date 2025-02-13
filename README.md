# Stacks Implementation

This project consists of two types of stack implementations in Java:

1. **ExpandableArrayStack**: An implementation of a stack using a dynamically resizing array.
2. **LinkedStack**: An implementation of a stack using a linked list.

## ExpandableArrayStack

This stack implementation starts with an array of size 1. Whenever the array is full, it dynamically resizes by doubling its size. If the size becomes less than a quarter of its capacity after a pop operation, it reduces its size by half.

### Features:
- Push: Adds an element to the stack.
- Pop: Removes the top element from the stack.
- Peek: Views the top element of the stack without removing it.
- IsEmpty: Checks if the stack is empty.
- Size: Returns the current number of elements in the stack.

## LinkedStack

This stack uses a linked list to store elements. Each node contains the element and a reference to the next node.

### Features:
- Push: Adds an element to the stack.
- Pop: Removes the top element from the stack.
- Top: Views the top element of the stack without removing it.
- IsEmpty: Checks if the stack is empty.
- Size: Returns the current number of elements in the stack.
