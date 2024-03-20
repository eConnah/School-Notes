# Queues
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