# course-plan

Course plan for the Haskell Beginners 2022 course.

* [Course announcement](https://kodimensional.dev/course)

## 🏡 Lecture 1: Fundamentals

* What is Functional Programming?
* FP concepts
* Haskell features
* Haskell toolchain: GHC, GHCi, ghcup, cabal, hls
* How to install Haskell?
* GHCi
  * Arithmetic expressions
  * Comparison operators
  * Boolean expressions
  * Calling functions
* Types
  * `:t` command in GHCi
  * Types of booleans, numbers and functions
* Lists and operations with them
  * Prepending, concatenation
  * Standard list functions
  * Ranges
* Laziness
* String
* Syntax constructions
  * Defining our own functions
  * packages, modules, imports
  * if-then-else
  * guards
  * let-in
  * where
* Immutability
* Recursion
* Higher-Order Functions (HOF)
  * Functions as first-class values
  * Lambda functions
  * Partial application
  * `map`, `filter`, etc.

Slides: https://slides.com/haskellbeginners2022/lecture-1

## 🏗 Lecture 2: Data types

* Tuples
* Pattern-matching
  * case-of
* Type aliases
* Product types
* Records
* Sum types
* newtypes
* Algebraic Data Types
* Totality
* Polymorphism
* Function composition: dot operator (.)
* Function application: dollar operator ($)

Slides: https://slides.com/haskellbeginners2022/lecture-2

## 🎮 Lecture 3: Typeclasses

* Typeclasses
* Instances
* Language Extensions
* InstanceSigs
* Default methods
* Standard typeclasses
* deriving
* Kinds
* Higher-Kinded Typeclasses
* Functor

Slides: https://slides.com/haskellbeginners2022/lecture-3

## 🔈🎤 Lecture 4: Monads and IO

* Monad typeclass
* Monad instances
* General monadic functions
* What is IO?
* Why does IO require a monad?
* Simple IO functions (putStrLn, getLine, readFile, writeFile)
* do-notation
* Separting side-effects from pure functions

Slides: https://slides.com/haskellbeginners2022/lecture-4
