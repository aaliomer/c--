# c--
This is a multiple paradigm language to replace c++ and rust.
It should be easier to pick up, as boring and more productive than Go.

the top goals of this language are:
- interoperability with c and possibly other functional languages with algebraic data types (why can't we call an elm function? or generate elm code?)
- readability. rust and c++ are very difficult to read. nim, crystal, go and python are closer to what we want.
- no garbage collection, no runtime and no built in allocator (think zig)
- real algebraic data types and possibly dependent types (think idris + elm)
- polymorphism in generics and limited function overloading (can't overload functions with the same number of params)
- methods and interfaces (mix of explicit and implicit interfaces. think go meets Java)
- macros! annotation and function based (think nim)
- modules as first class citizens (think typescript)
- array based... ish
- copies methods names and signatures from other languages standard library to make it easy to learn
- Destructors! think javascript
- minimal syntax sugar (not religious though like Go)
- library driven mostly and not language driven.
- DSL's not as a goal, but as a consequence of macros.
- compiles fast! use regular grammar and modular compilation. think zig
- type inference. no one needs to type all that crap. We have IDE's
- one or two ways to do one thing (instead of super opinionated languages)
- expression based
