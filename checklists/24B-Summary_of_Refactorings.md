# Summary of Refactorings

## Data Level Refactorings

- [ ] Replace a magic number with a named constant
- [ ] Rename a variable with a clearer or more informative name
- [ ] Move an expression inline
- [ ] Replace an expression with a routine
- [ ] Introduce an intermediate variable
- [ ] Convert a multi-use variable to a multiple single-use variables
- [ ] Use a local variable for local purposes rather than a parameter
- [ ] Convert a data primitive to a class
- [ ] Convert a set of type codes to a class
- [ ] Convert a set of type codes to a class with subclasses
- [ ] Change an array to an object
- [ ] Encapsulate a collection
- [ ] Replace a traditional record with a data class

## Statement Level Refactorings

- [ ] Decompose a boolean expression
- [ ] Move a complex boolean expression into a well-named boolean function
- [ ] Consolidate fragments that are duplicated within different parts of a conditional
- [ ] Use break or return instead of a loop control variable
- [ ] Return as soon as you know the answer instead of assigning a return value within nested if-then-else statements
- [ ] Replace conditionals with polymorphism (especially repeated case statements)
- [ ] Create and use null objects instead of testing for null values

## Routine Level Refactorings

- [ ] Extract a routine
- [ ] Move a routine's code inline
- [ ] Convert a long routine to a class
- [ ] Substitute a simple algorithm for a complex algorithm
- [ ] Add a parameter
- [ ] Remove a parameter
- [ ] Separate query operations from modification operations
- [ ] Combine similar routines by parameterizing them
- [ ] Separate routines whose behavior depends on parameters passed in
- [ ] Pass a whole object rather than specific fields
- [ ] Pass specific fields rather than a whole object
- [ ] Encapsulate downcasting

## Class Implementation Refactorings

- [ ] Change value objects to reference objects
- [ ] Change reference objects to value objects
- [ ] Replace virtual routines with data initialization
- [ ] Change member routine or data placement
- [ ] Extract specialized code into a subclass
- [ ] Combine similar code into a superclass

## Class Interface Refactorings

- [ ] Move a routine to another class
- [ ] Convert one class to two
- [ ] Eliminate a class
- [ ] Hide a delegate
- [ ] Replace inheritance with delegation
- [ ] Replace delegation with inheritance
- [ ] Remove a middle man
- [ ] Introduce a foreign routine
- [ ] Introduce a class extension
- [ ] Encapsulate an exposed member variable
- [ ] Remove Set() routines for fields that cannot be changed
- [ ] Hide routines that are not intended to be used outside the class
- [ ] Encapsulate unused routines
- [ ] Collapse a superclass and subclass if their implementations are very similar

## System Level Refactorings

- [ ] Duplicate data you can't control
- [ ] Change unidirectional class association to bidirectional class association
- [ ] Change bidirectional class association to unidirectional class association
- [ ] Provide a factory routine rather than a simple constructor
- [ ] Replace error codes with exceptions or vice versa
