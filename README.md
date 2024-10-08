# Path2Algorithms

Welcome to my **Path2Algorithms** repository!<br>
This repository serves as my personal learning journal, where I document the algorithms I’ve studied and implemented I have learned during my **university algorithms course** and while reading the book _Grokking Algorithms_ by Aditya Bhargava. I created it primarily for myself, as a way to solidify and track my understanding of key concepts. At the same time, I hope it can demonstrate my commitment to mastering algorithms and provide others with insight into my learning process. Thank you for taking the time to explore my work!

## Project Structure

- `python/`: Contains Python implementations of algorithms.
- `kotlin/`: Contains Kotlin implementations of algorithms.

Algorithms implemented in Python & Kotlin. The algorithms are categorized by type (e.g., sorting, searching, graph algorithms), and each language has its own folder.~~~~
Each folder contains subfolders for different algorithm types (e.g., sorting, searching).

---
### Table of Contents to My Notes
1. [Big O notation](#big-o-notation)

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
