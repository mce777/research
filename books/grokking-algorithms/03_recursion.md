### Chapter 3 - Recursion
- `recursion`is when a function calls itself
  - `recursive case`: the condition in which the function *should* call itself (e.g. i > 1)
  - `base case`: the condition in which the function should *no longer* call itself
    - if there's no base case, you risk an infinite loop

- `call stack`
  - when you call a function from another function, the calling function is paused in a partially completed state
  - a stack has two operations: `push` and `pop`
