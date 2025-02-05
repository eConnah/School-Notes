The only thing a function can do is calculate something and return a result and it is said to have no side effects. A consequence of not being able to change the value of an object is that every time a function is called with the same parameters it will always return the same result. A simple function can be proved to be correct and then used to build more complex functions.

Haskell splits your created function into its own separate functions. Such that a function such as 
```haskell
add3Integers x y z = x + y + z
add3Integers 1 2 3
```
Is actually run as
```haskell
lineOne y = y + 1
lineOne 2
lineTwo z = z + 3
```

Partial function application is when we have values that are hardcoded into the function to stop Haskell creating an unnecessary function.

When a function has type variable a when you run
```haskell
:type function
```
it means its a polymorphic function and can be overridden.

# Higher-Order Functions
A function is higher-order if it takes a function as an argument or returns a function as a result or does both.

## Map
Map is a higher order function that takes a list and the function to be applied to the elements in the list as inputs and returns a list made by applying the function to each element of the old list.
A list is a collection of elements which can be written in square brackets.
```haskell
map max(3)[1,2,3,4,5,]
map (+5)[1,2,6]
```

## Filter
Filter is another higher-order function which takes a predicate (Boolean condition) and a list. It returns the elements within the it that satisfy the Boolean condition.
```haskell
filter (>6)[2,5,6,8,9]
filter (==5)[2,7,6,5,1]
```

# Fold
A fold (or reduce) function reduces a list to a single value using recursion. For example to sum all the elements of a list starting from the left.
```haskell
foldl (+)0[2,3,4,5]
foldr (/)1[2,3,4,5]
```
foldl stands for fold left where you start with your leftmost value going right. foldr is when you start with your right most value and fold left.