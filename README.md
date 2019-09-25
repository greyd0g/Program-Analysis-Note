# Way-To-Programming-Analysis

## Tool

Here are some tools for program analysis. I strongly recommend you to implement algorithms on them.

- `LLVM`: the `Clang Static Analyzer` is a awesome tool to analyze C/C++ from AST level. And `LLVM Pass` provides a more low-level IR to analyze.
- `Soot`: tools for Java program anlysis and optimization
- `BAP`: Binary Analysis Platform. Written in OCaml. We can inspect customize IR `BIL` to analyze different binary.

## Intro

Normally, the basic parts include dataflow analysis frameword, pointer analysis, and abstract interpretation (baby level of course).

- Courses:
  - [UW CSE 501](https://courses.cs.washington.edu/courses/cse501/15sp/): Personally recommend, the contents are more compacted.
  - [CMU CS17-355](http://www.cs.cmu.edu/~aldrich/courses/17-355-19sp/): Some slides are missing. And the contents focus on security stuff more.

- Books:
  - [SPA Book](https://cs.au.dk/~amoeller/spa/spa.pdf): Personally recommend. This book is static analysis oriented. It also provied a toy language analyszer. The psedu-code and syntax are better the PPA.
  - Principle of Program Analysis: Old school book. The syntax is abstract. Might be too hard to understand.
  
## Intermediate

TODO...

## Advanced

TODO...

## State of Art

TODO..
