# High-Quality Routines

## Big-Picture Issues

- [ ] Is the reason for creating the routine sufficient?
- [ ] Have all parts of the routine that would benefit from being put into routines of their own been put into routines of their own?
- [ ] Is the routine's name a strong, clear verb-plus-object name for a procedure or a description of the return value for a function?
- [ ] Does the routine's name describe everything the routine does?
- [ ] Have you established naming conventions for common operations?
- [ ] Does the routine have strong, functional cohesion—doing one and only one thing and doing it well?
- [ ] Do the routines have loose coupling—are the routine's connections to other routines small, intimate, visible, and flexible?
- [ ] Is the length of the routine determined naturally by its function and logic, rather than by an artificial coding standard?

## Parameter-Passing Issues

- [ ] Does the routine's parameter list, taken as a whole, present a consistent interface abstraction?
- [ ] Are the routine's parameters in a sensible order, including matching the order of parameters in similar routines?
- [ ] Are interface assumptions documented?
- [ ] Does the routine have seven or fewer parameters?
- [ ] Is each input parameter used?
- [ ] Is each output parameter used?
- [ ] Does the routine avoid using input parameters as working variables?
- [ ] If the routine is a function, does it return a valid value under all possible circumstances?
