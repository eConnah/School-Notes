# Abstract Data Type
An abstract data type (ADT) is a logical description of how we view the data and possible operations. It includes:
- A queue of print jobs (add to the rear, remove from front)
- A stack of books (add to top, remove from top)
- A list of tasks to do (add to the end, remove most important)
We are concerned only with what the data is representing and not how it is constructed. We are creating an encapsulation around the data which is a type of information hiding.

## Queues
In a queue there are four distinct operations:
- Add item to the rear of the queue
- Remove item from the front of the queue
- Check if the queue is empty
- Check if the queue is full
We can't add to a full queue or remove an item from an empty queue Therefore, when the queue is initialised, we need to specify the maximum number that it can hold, e.g. maxSize. We may also need a variable size to hold the number of items currently in the queue.

### Circular Queue
A circular queue algorithm overcomes the problem of reusing the spaces that have been freed by dequeueing from the front of the array.

### Priority Queue
In a priority queue, some items are allowed to 'jump' the queue. This type of queue is used when the items arriving have some type of priority associated with them.

# Dynamic vs Static
Static data structures are fixed in size, they cannot grow, shrink, or be freed during execution. An array is a static data structure. Dynamic data structures can grow and shrink they allocate and deallocate memory from the heap (an area of memory especially used for this purpose). Excessive allocation of memory, without deallocation, may cause overflow (exceeding maximum memory limit).