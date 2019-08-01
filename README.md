# freeCodeCamp Elk Grove Compiler Talk Slides
I gave a talk on how a compiler is constructed for freeCodeCamp Elk Grove. This was meant to be a very brief introduction to fundamental compiler topics like the ones listed below. I structured the talk in a way where I gave a brief explanation of the theory then I provided an example of how the theory plays into the implementation of a compiler. Although I didn't go into each topic in-depth, I felt like it was enough information to encourage the audience to do further research into these compiler topics. 

# Topics Covered/Introduced
- Cross-compilers
- Translation Compilers
- Decompiler
- Scanning
  - Tokens
  - Regular Expressions
  - NFA and DFA
  - Thompson's Construction
  - Subset Construction
  - Kleene's Construction
  - Table Driven Scanners
  - [Flex](https://www.gnu.org/software/flex/)
- Parsing
  - Grammars
  - Parse Trees
  - Top-down Parsing
  - Bottom-up Parsing
  - LR(1) Parsing
  - [Bison](https://www.gnu.org/software/bison/)
- Intermediate Representations
  - IR's in AST Trees
  - ILOC
  - AST to ILOC Conversion
- Code Optimizations
  - Common Sub-expression Elimination (CSE)
  - Constant Folding
  - Loop Unrolling
- Instruction Scheduling
- Instruction Selection
- Register Allocation

If you want to check out a toy compiler I wrote, [click here](https://github.com/jefflow/baby-c-compiler).
  
