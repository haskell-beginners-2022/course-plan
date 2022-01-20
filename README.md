# course-plan

Course plan for the Haskell Beginners 2022 course.

* [Course announcement](https://kodimensional.dev/course)

Exercises and installation instructions can be found in the `exercises` repository:

* [haskell-beginners-2022/exercises](https://github.com/haskell-beginners-2022/exercises)

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

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-1
📽 Video: [Haskell Beginners 2022: Lecture 1](https://www.youtube.com/watch?v=6MsQcUprO9o)

## 🏗 Lecture 2: Data types

* Pattern-matching
  * Top level
  * `case-of`
  * List patterns
  * Recursion and pattern matching
  * Pattern matching pitfalls
* Totality
* Tuples
* Algebraic Data Types
  * Product types
  * Sum types
* Data types in Haskell
  * `data`
  * Simple product types
  * Records
  * Enumerations
  * Simple sum types
  * Recursive data types
  * `type`
  * `newtype`
* Polymorphism
  * Parametric polymorphism
  * Types of standard functions
  * Hoogle
  * Polymorphic data types
  * Standard polymorphic data types
* Eta-reduction 
* Function composition: dot operator (.)

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-2
📽 Video: [Haskell Beginners 2022: Lecture 1](https://www.youtube.com/watch?v=rf-lie7U04Q)

## 🎮 Lecture 3: Typeclasses

* Parametric polymorphism vs Ad-hoc polymorphism
* Typeclasses
  * `class` 
  * `instance`
  * Default methods
  * `{-# MINIMAL #-}`
* Language Extensions
  * `{-# LANGUAGE #-}` 
  * `InstanceSigs` 
* Standard typeclasses
  * Eq
  * Ord
* `deriving`
  * Stock derivable typeclasses
  * `GeneralizedNewtypeDeriving` 
* Semigroup
* Monoid
* Kinds
* Higher-Kinded Types
* Functor
* `foldr` and `foldl'`
* Foldable

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-3

## 🔈🎤 Lecture 4: Monads and IO

* Monad typeclass
* Monad instances
* General monadic functions
* What is IO?
* Why does IO require a monad?
* Simple IO functions (putStrLn, getLine, readFile, writeFile)
* do-notation
* Separting side-effects from pure functions

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-4
