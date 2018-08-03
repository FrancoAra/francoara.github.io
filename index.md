---
layout: default
---

Welcome!
=================

I am a functional programmer located in the Amsterdam area. I run Purely Typed a software development consulting company specialized in distributed systems. I make efforts to train people in the fine arts of functional programming and mathematics for systems design.  And I work as much as possible on solving [another significant issue](https://medium.com/@franciscoarmburo/decision-systems-a-critical-challenge-be4bb1434fd1).

FP Academy
=======================

This section contains tables categorized by level, where each column represents a topic that hopefully can be presented and practiced in 2 hours. Each level has a soft dependency on the previous ones, and sometimes each topic as well.

*Free Trainings:* Each week depending on popular demand I give a 2-hour session through a meetup and teach 1 topic with exercises and lots of opportunities for questions, if you are interested in learning or reviewing one of the topics below please contact me through LinkedIn or [Meetup.com](https://www.meetup.com/FP-Academy-Ams).

### Example of topics per level

| Topic 1 - 2 hours session | Topic 2 - 2 hours session | Topic 3 - 2 hours session |
| --------- | --------- | --------- |
| sub topic 1 | sub topic 1 | sub topic 1 |
| sub topic 2 | sub topic 2 | sub topic 2 |
| sub topic 3 | sub topic 3 | sub topic 3 |

Functional Programming Techniques Level 1
----------

| Introduction to FP (Theory) | Introduction to FP (Practice) | Type Classes |
| --------------------------- | ----------------------------- | ------------ |
| Function composition | Immutable data / algebraic data types | Definition |
| Referential transparency and totality | Pattern matching | Usage |
| Equational reasoning and abstract algebras | Construction and deconstruction | Implicit resolution |
| | First order functions, lambdas and recursion | Recursive resolution |

Functional Programming Techniques Level 2
----------

| Core Typeclasses | Monad Hierarchy 1 | Monad Hierarchy 2 |
| ---------------- | ----------------- | ----------------- |
| Eq, Show, Order  | Functor | Higher Kinded Types |
| Semigroup, Monoid | Applicative | Functor, Applicative and Monad typeclasses |
| | Monad | MonadError and beyond |

.

| [Optics](https://github.com/julien-truffaut/Monocle) | [Property Based Testing](https://www.scalacheck.org/) |
| - | - |
| Isomorphisms | Properties |
| Lenses | Generators |
| Prisms | Testing with scalatest |


Functional Programming Techniques Level 3
----------

| More Monads | Effect Types 1 | Effect Types 2 |
| - | - | - |
| State Monad | Referential transparency | Typeclasses |
| Reader Monad | Sync, Async, Effect | Ref, MVar, Semaphore |
| Writer Monad | Fibers | An IO interpreter |
| Typeclasses | | |

.

| Tagless Final | Free Monad | Variance and Functors |
| - | - | - |
| Free algebras | Free algebras | Subtyping and variance in Scala |
| Interpreters | Interpreters | A small peek on category theory |
| Program optimization | Program optimization | Variance in functors and why subtyping sucks |

Functional Programming Techniques Level 4
----------

| FP System Architecture 1 | Introduction to Dependent Types | F-Algebras with [Matryoshka](https://github.com/slamdata/matryoshka) |
| - | - | - |
| Design for change | Core concept | Recursive algebras |
| Decrease possible incorrect programs | Singleton Types | Fixed point types |
| Identify mathematical properties of the system | Typeclasses and equational resolution | Interpreting the algebra and recursion schemes |
