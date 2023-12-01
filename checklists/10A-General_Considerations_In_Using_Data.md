# General Considerations In Using Data

## Initializing Variables

- [ ] Does each routine check input parameters for validity?
- [ ] Does the code declare variables close to where they're first used?
- [ ] Does the code initialize variables as they're declared, if possible?
- [ ] Does the code initialize variables close to where they're first used, if it isn't possible to declare and initialize them at the same time?
- [ ] Are counters and accumulators initialized properly and, if necessary, reinitialized each time they are used?
- [ ] Are variables reinitialized properly in code that's executed repeatedly?
- [ ] Does the code compile with no warnings from the compiler?
- [ ] If your language uses implicit declarations, have you compensated for the problems they cause?

## Other General Issues in Using Data

- [ ] Do all variables have the smallest scope possible?
- [ ] Are references to variables as close together as possible—both from each reference to a variable to the next and in total live time?
- [ ] Do control structures correspond to the data types?
- [ ] Are all the declared variables being used?
- [ ] Are all variables bound at appropriate times, that is, striking a conscious balance between the flexibility of late binding and the increased complexity associated with late binding?
- [ ] Does each variable have one and only one purpose?
- [ ] Is each variable's meaning explicit, with no hidden meanings?
