## Chapter 5: Hash Tables
- a `hash function` is a function where you put in a string and get back a number (i.e. index)
- a `hash function` and an array together is a data structure called a `hash table`
  - `hash tables` are great when you want to
    - create a mapping from one thing to another thing
    - look something up
      - DNS resolution can be done via `hash tables`
    - `hash tables` are very fast at finding duplicates
    - have really fast search, insert, and delete

- using `hash tables` as cache
   - caching is a common way to make things faster (better performance, get the data faster)
    - the data is stored in a `hash` (e.g. websites)

- `Collisions`: when two or more elements have the same slot in the array
  - not 'game over', but this condition requires using something like a linked list (at this slot) to accomodate
    - ideally, the hash function will limit the need for this, optimizing **performance**
    - `load factor`: (items in hash table) / (total number of slots)
      - load factor of > 1 means you have more items than slots in your array
      - once your load factor > 0.7, it's time to resize your hash table        
