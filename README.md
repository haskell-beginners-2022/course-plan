# course-plan

<p align="center">
  <img width="256" height="256" src="https://raw.githubusercontent.com/haskell-beginners-2022/course-plan/main/logo.png">
</p>

Haskell and Functional Programming course for complete beginners.

> :warning: The course authors no longer provide reviews of the solutions.
> However, all the learning materials are free and publicly available.
> You can learn Haskell on your own or with the help of others.

Course learning materials comprise:

* [🎥 Four 1-hour lectures on YouTube][video]
* [🖼 Slides][slides]
* [🧩 Practical exercises and Haskell installation instructions][exercises]

[video]: https://www.youtube.com/watch?v=6MsQcUprO9o&list=PLOJjn67NeYg9cWA4hyIWcxfaeX64pwo1c&ab_channel=chshersh
[slides]: https://slides.com/haskellbeginners2022
[exercises]: https://github.com/haskell-beginners-2022/exercises

The course is entirely free!

<hr>

Below you can find the plan for each individual lecture with the
corresponding links to learning materials.

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
  * Types of booleans, numbers, and functions
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
  * Pattern-matching pitfalls
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

📽 Video: [Haskell Beginners 2022: Lecture 2](https://www.youtube.com/watch?v=rf-lie7U04Q)

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
* Why Purity + Laziness is a problem for side effects?
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

## What's next?

After you've finished the course, you may be interested in the
following resources to continue your FP and Haskell journey:

* [Learn Haskell by building a blog generator](https://lhbg-book.link/):
  A project-based course that teaches pragmatic Haskell by building a
  blog generator from scratch.
* [Haskell in Depth](https://www.manning.com/books/haskell-in-depth):
  A book about intermediate Haskell topics such as Monad Transformers,
  metaprogramming, testing, logging, and performance analysis.
* [Functional Design and Architecture ](https://www.manning.com/books/functional-design-and-architecture):
  Design patterns and architectures for building production quality
  applications using functional programming, with examples in Haskell
  and other FP languages.
* [Haskell Study Plan](https://github.com/soupi/haskell-study-plan):
  More links on different topics and examples of real-world Haskell
  projects.
* [Awesome List of Haskell mentors](https://github.com/willbasky/Awesome-list-of-Haskell-mentors):
  A list of Haskell projects and mentors willing to help you master Haskell.
