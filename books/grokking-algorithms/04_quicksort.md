### Chapter 4: Quicksort

- background info: see Euclid's algorithm
- quicksort uses the concept "divide & conquer"
- when you're writing a recursive function involving an array, the base case is often an empty array or an array with one elemnt. 

#### quicksort algorithm
1. pick a `pivot`
2. sort
3. if one or both sides requires a sort, then sort it (recursively until you hit the base case)
  - no matter what pivot you pick, you can call quicksort on the two sub-arrays

- the performance of quicksort heavily depends on the pivot you choose.
- you can get the best case consistently as long as you always choose a *random element* as the pivot.
  - doing so will give quicksort an averge runtime of `O(n log n)`
