## POPL Day 2


## Notes from POPL Day 2

## Keynote 
## Type Soundness Theorem - Derek Dreyer

<img src="/images/popl_2/popl_001.png" width="400">

- Rob Milner: Theory of Type Polymorphism in Programming
  "well-typed programs cannot go wrong"
- Andrew Wright, Matthias
  "syntactic approach to type soundness"
  - well-typed programs can't get stuck
- Progress and Preservation
  - Progress: future state or valid terminal state
  - Preservation
- Limits:
  - Limit 1: Data Abstraction
  - Limit 2: Unsafe Features: See "Pre-pooping your pants with Rust (Alexis Beingessner, Leakpocalypse)
  
<img src="/images/popl_2/popl_002.png" width="400">

- Landmark Semantic Soundness
  - Milner (1978): used a "logical-relations" model based on denotational semantics. Didn't scale to 
    richer type systems (eg. ML)
  - Appel, McAllester (2001): introduced a "step-indexed" logical-relations model of recursive types
    using operational semantics 
  - Ahmed (2004) : Scaled "step-indexed" model to handle higher-order state using recursive Kripke structures
- Iris - implement in Coq system
- Higher-Order Hoare Logic : If P holds initially, then e is safe to excecute.
  Bind Rule
- Iris's Monadic Bind Blue
<img src="/images/popl_2/popl_003.png" width="400">

- Separation Logic
- Concurrent Separation Logic
- Perfect for modelling concurrent languages with substructural type systems like Rust 
- Persistent vs Ephemeral
  - Ephemeral: value can change: we assume a type, but may change as we step through programme
- Proving that ADT is semantically well-typed
- Ghost-state: logical state in proof but not physical state in programme
- PCM: partial commutative monad
Takeaway: Good type systems support data abstraction and safe encapsulation of unsafe features

## Linear Haskell
( This talk was OK: I wish it were longer, more detailed, and the points not as trivialized)
( Intersestingly, my friend, Ben, also agreed with me). 

<img src="/images/popl_2/popl_004.png" width="400">

- Higher Order Constrained Horn Clauses for Verification
- Jones: Optimal Partial Evaluation
- Wadler: Linear Types
  - Linear types seem to require deep changes to the language
- ```f::A->B```
  - If f U is consumed exactly once, then U is consumed exactly once
  - Polymorphic foldl instead of linear foldl
  - Linearity Polymorphism (no subtyping)
 
<img src="/images/popl_2/popl_005.png" width="400">
  
## Polyvariadic Approximations: Fibrations and Intersection Types
(This was definitely not clear to me, so the notes are very short-ended.) 

- Calculus as Cat-operands
- a 2-morphism between multi-morphisms is a cut-elimination path
- Approximate presheaf: An approximate on MELL defines the approximation presheaf
- The Groethendieck construction: subject reduction: subject reduction/ subject expansion
- The fundamental theorem of intersection types (Mazza, Pellisier, Vial)
- If A compose G have properties relative to 
  - a family of Reductions R_s
  - a strategy R_w
  - then we can go from a weak to a strong type (I drew the diagram for this)
- Coppo-Dezani idempotent type system
  - de Carvalho's System R
  - Kesner-Vial's system for the lambda u - calculus and gets their normalization properties
    and reduction strategies
    
## Unifying Analytic and Statically Typed Quasiquotes
- Analytic Quasiquotes - code as data 
  (I've heard of code as data in Clojure.spec, but not familiar with quasiquotes)
  - Statically-typed quasiquotes
  
## Lunch Break :D

<img src="/images/popl_2/popl_006.png" width="400">

<img src="/images/popl_2/popl_007.png" width="400">

## Safety and Conservativity for HOL and Isabelle / HOL (Andrei Popescu)

- Implementation bug 
  
  


