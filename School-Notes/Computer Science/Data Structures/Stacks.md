In computer science, a stack is a fundamental data structure that follows the Last In First Out (LIFO) principle. A stack is a linear data structure where elements are added and removed from the same end called the top of the stack. The basic operations on a stack include push, pop, and peek. Stacks are commonly used in various applications such as function call management, undo mechanisms, and expression evaluation.

Stacks can be implemented using arrays or linked lists. The array implementation of a stack provides efficient memory usage, as the size of the stack is fixed. However, this can lead to stack overflow if the stack becomes full. On the other hand, the linked list implementation allows for dynamic memory allocation, but it may have higher memory overhead.

These methods could be written to implement the required functionality of a stack:
- push(item) — adds item to the top of the stack
- pop() — removes and returns the item on the top of the stack
- isFull() — checks if the stack is full
- isEmpty() — checks if the stack is empty
- peek() — return the top item without removing it
- size() — return the number of items on the stack