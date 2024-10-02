A problem is defined as being computable if there is an algorithm that can solve every instance of it in a finite number of steps. Some problems may be theoretically soluble by computer but if they take millions of years to solve, they are, in a practical sense, insoluble. Limits are imposed by both algorithmic complexity and hardware. Problems that were insoluble 50 years ago have now become computable.

# Travelling Salesman
One way of attempting to solve the problem is the brute force method, using this method, all possible routes are tested. It has the [[Big-O notation]] of $O(n!)$. A problem that has a polynomial-time solution or better is called a tractable problem $O(n)$, $O(n^{2})$, $O(nk)$. Algorithms with time complexities are all 'efficient' algorithms for solving problems

An intractable problem is one that does not have a polynomial time solution Algorithms of time complexity $O(2^{n})$ and $O(n!)$ are examples of inefficient algorithms. Although the problem may have a theoretical solution, it is impossible to solve it within a reasonable time for values of $n$ greater than something very small.

# Heuristic methods 
Not all intractable problems are equally hard it may be relatively easy to get an approximate answer that is good enough. A heuristic approach is one which tries to find a solution which may not be perfect but which is adequate for its purpose.