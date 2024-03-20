# Abstract Data Type
An abstract data type (ADT) is a logical description of how we view the data and possible operations. It includes:
- A queue of print jobs (add to the rear, remove from front)
- A stack of books (add to top, remove from top)
- A list of tasks to do (add to the end, remove most important)
We are concerned only with what the data is representing and not how it is constructed. We are creating an encapsulation around the data which is a type of information hiding.

# Dynamic vs Static
Static data structures are fixed in size, they cannot grow, shrink, or be freed during execution. An array is a static data structure. Dynamic data structures can grow and shrink they allocate and deallocate memory from the heap (an area of memory especially used for this purpose). Excessive allocation of memory, without deallocation, may cause overflow (exceeding maximum memory limit).