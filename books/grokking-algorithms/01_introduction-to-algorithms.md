### Chapter 1: Introduction to Algorithms

- An `algorithm` is a set of instructions for accomplishing a task
- Examples
  - `simple search`: aka inefficient, stupid search
    - linear time, in Big-0: O(n)
  - `binary search`: 
    - divide an conquer
    - you're cutting the possibilities in half with each attempt.
    - runs in `logarithmic time`, in Big-0: O(log n)

- Big O establishes a worst-case run time
  - O(log n): log time, eg `binary search`
  - O(n): linear time, eg `simple search`
  - O(n * log n): a fast sorting algorithm like `quicksort`
  - O(n²): a slow sorting algorithm like `selection sort`
  - O(n!): factorial time, a really slow algorithm like the `traveling salesperson`
