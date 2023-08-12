# ADC 2023

### Abstract

Rust has become an exciting alternative to C++ for audio programming. This talk will explain how Rust's unique type system can be leveraged to create elegant DSP code, with an emphasis on conciseness, clarity, and safety. This talk will show that many features of audio programming DSLs can be achieved using advanced features of the Rust type system, and how Rust's zero-cost abstractions can be used to create DSP elements that are flexible, composable, and don't compromise performance. It will also show how to instantiate and implement audio processing graphs in imperative, functional, and declarative styles.

## Outline
 - Overview of the rust type system, with an emphasis on traits, impls, generics, monomorphization, and macros
 - Implementing generic sample and buffer primitives
 - Implementing a DSP algorithm using using slice iterators
 - Leveraging traits to create composable generator, processor, and block abstractions
 - Composing audio processing graphs
   - Imperatively
   - Declaritively
   - Functionally
   - With macros
   - With operators

### Details
 - **Introduction**: Purpose of this talk
   - Ugly C++ code
   - Nicer looking Faust code (not good for everything)
   - Nicer looking CMajor code (proprietary compiler)
 - **Intro to Rust**: Crash course on the Rust type system
 - **Traits**: Implementing `Processor` and `Generator` using `Sample`/`Frame` and `Block`
 - **Iterators**: Using iterators to implement stuff
 - **Declarative**: More stuff
 - **Functional**: More stuff
