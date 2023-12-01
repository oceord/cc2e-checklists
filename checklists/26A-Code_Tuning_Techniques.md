# Code-Tuning Techniques

## Improve Both Speed and Size

- [ ] Substitute table lookups for complicated logic
- [ ] Jam loops
- [ ] Use integer instead of floating-point variables
- [ ] Initialize data at compile time
- [ ] Use constants of the correct type
- [ ] Precompute results
- [ ] Eliminate common subexpressions
- [ ] Translate key routines to assembler

## Improve Speed Only

- [ ] Stop testing when you know the answer
- [ ] Order tests in case statements and if-then-else chains by frequency
- [ ] Compare performance of similar logic structures
- [ ] Use lazy evaluation
- [ ] Unswitch loops that contain if tests
- [ ] Unroll loops
- [ ] Minimize work performed inside loops
- [ ] Use sentinels in search loops
- [ ] Put the busiest loop on the inside of nested loops
- [ ] Reduce the strength of operations performed inside loops
- [ ] Change multiple-dimension arrays to a single dimension
- [ ] Minimize array references
- [ ] Augment data types with indexes
- [ ] Cache frequently used values
- [ ] Exploit algebraic identities
- [ ] Reduce strength in logical and mathematical expressions
- [ ] Be wary of system routines
- [ ] Rewrite routines in line
