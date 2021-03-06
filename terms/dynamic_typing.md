# Dynamic typing

## Definition
When type safety is enforced at runtime. Values are associated with type information, which can also be used for other purposes, such as runtime reflection. Used in languages such as Python, Ruby, Lisp, Perl, etc. 

### Benefits
Compiler may run faster; easy to load code dynamically at runtime; allows some things that are type safe but are still excluded by a static type system; easy to use duck typing to get naturally generic code with little overhead for the programmer; reflection, introspection and metaprogramming becomes easier.
 
### Drawbacks
Type errors cannot be detected at compile time; rigorous testing is needed to avoid type errors; some optimisations may be difficult to perform (less of a problem with just-in-time compilation).

Dynamic typing does not imply [Weak typing](Weak typing).

## Meta
* this sameAs http://en.wikipedia.org/wiki/Dynamic_typing
* this similarTo static typing
* this similarTo duck typing
* this similarTo weak typing
* #Types
