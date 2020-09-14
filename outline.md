Information hiding as the priciple for decomposing systems into modules

Information hiding
- Fundamental cost in SE is accomodating change
- A change that modifies multiple modules is more costly than a change that is isolated in a single module

Therefore
- Anticipate likely changes
- Define interfaces that capture the stable aspects and implementations that capture changeable aspects

Caveat:
- You cannot build a design that anticipates all changes (same as make everything easily accessible in a car engine)
- Making it expensive to replace a filter would be not sensible


What we can hide
- Algorithms
- Data representations
- Hardware specifics
- External API/domain specifics
- Where information is acquired

Modularity

Bezos API mandate



Design reviews
- Can be internal or external
- Goal is to sanity-check your design and get constructive feedback
- Need to boil it down to its essence when you present your design

