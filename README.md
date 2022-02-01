# course-plan

Course plan for the Haskell Beginners 2022 course.

* [Course announcement](https://kodimensional.dev/course)

Exercises and Haskell installation instructions can be found in the `exercises` repository:

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
  * `if-then-else`
  * guards
  * `let-in`
  * `where`
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
* Function composition: dot operator `(.)`

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-2

📽 Video: [Haskell Beginners 2022: Lecture 1](https://www.youtube.com/watch?v=rf-lie7U04Q)

## 🎮 Lecture 3: Typeclasses

* Parametric polymorphism vs Ad-hoc polymorphism
* Typeclasses
  * `class` 
  * `instance`
  * Default methods
  * `{-# MINIMAL #-}`
  * Small typeclasses vs Big typeclasses
* Language Extensions
  * `{-# LANGUAGE InstanceSigs #-}` 
* Standard typeclasses
  * `Eq`
  * Haskell Equality Table
  * `Ord`
  * `Num`
* `deriving`
  * Stock derivable typeclasses
  * `{-# LANGUAGE GeneralizedNewtypeDeriving #-}`
* Algebraic typeclasses
  * `Semigroup`
  * `Monoid`
  * Laws
* Kinds
* `Functor`
* Folds
  * `foldr`
  * `foldl`
  * `foldl'`
  * `foldr` vs `foldl'`
  * `Foldable`
* Strict and Lazy evaluation
  * Lazy evaluation
  * Tail Call Optimization (TCO)
  * Equational reasoning
  * `{-# LANGUAGE BangPatterns #-}` 

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-3

📽 Video: [Haskell Beginners 2022: Lecture 3](https://www.youtube.com/watch?v=Vs-vvlYLtRI)

## 🔈🎤 Lecture 4: Monads and IO

* Monad example
  * `andThen` for `Maybe`, `Either` and list
* Monad as programming pattern
* `Monad`
  * The typeclass
  * Instances
  * Laws
  * Usage example 
* **FAM**ily: `Functor`, `Applicative`, `Monad`
* Purity
* Why Purity + Laziness is a problem for sie effects?
* `IO`
  * Why does IO require a monad?
  * `String` vs `IO String`
  * `getLine`
  * `putStrLn`
  * `Main` and `main`
* _Then_ operator: `>>`
* `do`-notation
* Cabal
  * Packages
  * `build-depends` 
* Functional Core, Imperative Shell

🎞 Slides: https://slides.com/haskellbeginners2022/lecture-4

📽 Video: [Haskell Beginners 2022: Lecture 4](https://www.youtube.com/watch?v=12D4Y2Hdnhg)
