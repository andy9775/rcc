# rcc: rcor C compiler

A C compiler under development

by ROCHA, Rodrigo Caetano

### DONE

* Scanner: lexical analyser
* Parser: syntactic analyser
* Macro pre-processor (e.g.: #include, #define)
* Basic data-type structures (e.g.: primitives, struct)
* Basic identifier structures (e.g.: function names, variable names)
* AST: build the abstract syntax tree (almost finished)
* CGen: generate C code from the AST

### TODO

* TypeCheck: perform semantic analysis
* RIR: design and generate an intermediate representation
* LLGen: generate LLVM IR code from the RIR
* RIR backend: generate a RIR backend for different architectures
* Optimizations on both AST and RIR level

### Building Dependencies

* [bison](http://www.gnu.org/software/bison/) 
* [flex](http://flex.sourceforge.net/)

