# Defensive Programming

## General

- [ ] Does the routine protect itself from bad input data?
- [ ] Have you used assertions to document assumptions, including preconditions and postconditions?
- [ ] Have assertions been used only to document conditions that should never occur?
- [ ] Does the architecture or high-level design specify a specific set of error handling techniques?
- [ ] Does the architecture or high-level design specify whether error handling should favor robustness or correctness?
- [ ] Have barricades been created to contain the damaging effect of errors and reduce the amount of code that has to be concerned about error processing?
- [ ] Have debugging aids been used in the code?
- [ ] Has information hiding been used to contain the effects of changes so that they won't affect code outside the routine or class that is changed?
- [ ] Have debugging aids been installed in such a way that they can be activated or deactivated without a great deal of fuss?
- [ ] Is the amount of defensive programming code appropriate—neither too much nor too little?
- [ ] Have you used offensive programming techniques to make errors difficult to overlook during development?

## Exceptions

- [ ] Has your project defined a standardized approach to exception handling?
- [ ] Have you considered alternatives to using an exception?
- [ ] Is the error handled locally rather than throwing a non-local exception if possible?
- [ ] Does the code avoid throwing exceptions in constructors and destructors?
- [ ] Are all exceptions at the appropriate levels of abstraction for the routines that throw them?
- [ ] Does each exception include all relevant exception background information?
- [ ] Is the code free of empty catch blocks? (Or if an empty catch block truly is appropriate, is it documented?)

## Security Issues

- [ ] Does the code that checks for bad input data check for attempted buffer overflows, SQL injection, html injection, integer overflows, and other malicious inputs?
- [ ] Are all error-return codes checked?
- [ ] Are all exceptions caught?
- [ ] Do error messages avoid providing information that would help an attacker break into the system?
