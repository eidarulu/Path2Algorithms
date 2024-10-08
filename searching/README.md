# Explanation of searching algorithms

Binary search only works when your list is in sorted order.

### Searching Algorithms

- **Binary Search**:  
  Efficient for searching in sorted datasets by repeatedly halving the search space.  
  - Time complexity: **O(log n)**  
  - Use case: Finding elements in a sorted array quickly.


### Big O notation
**Big O** notation tells how fast an algorithm is. Algorithm speed isn’t measured in seconds but in growth of the number of operations. Instead of seconds, we talk about how quickly the run time of an algorithm increases as the size of the input increases.

#### Big O establishes a worst-case run time.<br>
Suppose you’re using *Simple Search* to look for a person in the phone book. If you’re looking for someone who is in the first entry in the phone book you'll find it on the first try. That’s the best-case scenario. Did this algorithm take O(n) or  O(1) time? We use **Big O** notation for worst-case scenario analysis. So you can say that in the worst case, you’ll have to look at every entry in the phone book. That’s O(n) time. It’s a reassurance — you know that simple search will never be slower than O(n) time.

> Along with the worst-case run time, it’s also important to look at the average-case run time.

Some common big O run times you’ll encounter a lot, sorted from fastest to slowest:

- O(log n), also known as log time. Example: binary search.
- O(n), also known as linear time. Example: simple search.
- O(n * log n). Example: a fast sorting algorithm, like quicksort.
- O(n2). Example: a slow sorting algorithm, like selection sort.
- O(n!). Example: a really slow algorithm, like the traveling salesperson.

