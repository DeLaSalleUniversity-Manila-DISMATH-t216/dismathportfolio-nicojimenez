# dismathportfolio-nicojimenez
dismathportfolio-nicojimenez created by Classroom for GitHub

#WEEK 1
* First day of school. First subject = __DISMATH__ (Discrete Mathematics)
* I heard a lot about this subject. Some say it's as simple as 1 + 1, some also say its mind-blowing.
* When Sir Cabatuan introduced DISMATH, I thought it was going to be like 3rd year Geometry with the conditional statements and 4th year Physics with the logic gates.
* He also introduced us to words like Propositions, Logical Deduction, Axioms.
* Sir Cabatuan also said that in DISMATH, emotions should not get in the way of logic.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

#WEEK 2
* I was re-enlightened with the topic about Logical Connectives/Logical Operators.
* Although I already had a background regarding this topic, it seems a bit more complicated.
* The Logical Connectives are Negation, Conjunction, Disjunction, Exclusive Or, Conditional, and Biconditional.
* Sometimes, I get lost when Sir gives us complex examples because I let my brain think about it which just makes things harder to reason out.
* I also learned the different Logical Equivalences.

|                           Equivalence                          |         Name        |
|:--------------------------------------------------------------:|:-------------------:|
|                      p ∧ T ≡ p  //     p v F ≡ p               |    Identity laws    |
|                       p v T ≡ T  //    p ∧ F ≡ F               |   Domination laws   |
|                       p v p ≡ p //     p ∧ p ≡ p               |   Idempotent laws   |
|                            ¬(¬p) ≡ p                           | Double negation law |
|                   p v q ≡ q v p // p ∧ q ≡ q ∧ p               |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) // (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) //  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q // ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p // p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T // p ∧ ¬p ≡ F                   |    Negation laws    |

#WEEK 3
* We were taught about Predicate Logic, and Quantifiers.
* Universal Quantifiers = "For All"
* Existential Quantifiers = "There Exists"
* I also learned more about the Biconditional statement.
* The Biconditional is A ↔ B ≡ (A → B) ∧ (B → A)
* One is that "if", "only if", and "if and only if" are different.
* "A if B" = B → A
* "A only if B" = A → B
* "A if and only if B" = A ↔ B


|         Name         |   Rule of Inference  |            Tautology           |
|:--------------------:|:--------------------:|:------------------------------:|
|    Modus Ponens      |      p, p→q ∴q       |        (p ∧ (p → q)) → q       |
|      Modus Tollens   |     ¬q, p→q ∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
|Hypothetical Syllogism|     p→q, q→r ∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|Disjunctive Syllogism |      p∨q, ¬p ∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|      Addition        |       p ∴p ∨ q       |           p → (p ∨ q)          |
|      Simplication    |       p ∧ q ∴p       |           (p ∧ q) → p          |
|       Conjunction    |      p, q ∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|      Resolution      | p ∨ q, ¬p ∨ r ∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

#WEEK 4
* This week I have learned about the Different Methods of Proof
* I. **Direct Proof**.
* Steps:
  *   1. Assume *p* is T.
  *   2. Show that *q* is also T.
* II. **Proof by Contraposition**.
* Steps:
  *   1. Assume *¬q* is T
  *   2. Show that *¬p* is also T.
* III. **Vacuous Proof**.
* Which is basically ¬p → (p→q)
* Steps:
  *   1. Show that *¬p* is T **OR** *p* is F.
  *   2. *p→q* is T when *¬p* is **OR** *p* is F.
* IV. **Trivial Proof**
* Basically, q → (p→q)
* Steps:
  *   1. Show that *q* is T.
  *   2. p→q is therefore T when *q* is T
* V. **Proof by Contradiction**
* Prove that the premises will end up FALSE or in Contradiction
* Steps:
  *   1. Assume **ALL PREMISES** to be FALSE.
  *   2. Show that these premises will end up in a Contradiction.

#WEEK 5
* This week I have learned about **Proof by Equivalence**.
* VI. **Proof by Equivalence**
* This is usually used for proving Biconditional Statements.
* Steps:
  *   1. Show that (p→q) is T.
  *   2. Show that (q→p) is also T.
* I also learned about Mathematical Induction
* Steps for Mathematical Induction:
  *   1. SUBSTITUTION.
  *   2. DIRECT PROOF.

#WEEK 6
* PROGRAM CORRECTNESS
  * Hoare Triple
  * p{S}q - A program, S, is said to be partially correct with respect to the initial assertion p and the final assertion q if whenever p is true for the input values of S and S terminates, then q is true for the output values of S.

#WEEK 7
* INTRODUCTION TO SET THEORY
  * Empty Set
  * ↳ { } = ∅
  * Set Builder Notation
  * {x | some property x satisfies}
* VENN DIAGRAMS
  * UNION 
   * A ⋃ B ≡ (x ∈ A) ∧ (x ∈ B) 
  * INTERSECTION
   * A ⋂ B ≡ (x ∈ A) ∨ (x ∈ B) 
  * DIFFERENCE
   * A - B
  * DIFFERENCE
   * A \ B ≡ (x ∈ A) ∧ (x ∉ B)
  * SYMMETRIC DIFFERENCE
   * A ∆ B ≡ {x | (x ∈ A) ∧ (x ∉ B) ∨ (x ∈ B) ∧ (x ∉ A)}

### Week 8:

* **ALGORITHMS**
    - A finite set of precise instructions for performing a computation or for solving a problem.
    - **Properties of Algorithms**: </br>
        ⇾ _Input_ - has input values from a specified set </br>
        ⇾ _Output_ - solution to the problem </br>
        ⇾ _Definiteness_ - defined precisely </br>
        ⇾ _Correctness_ - produce the correct output values </br>
        ⇾ _Finiteness_ - produce the desired output </br>
        ⇾ _Effectiveness_ - perform exactly and in a finite amount of time </br>
        ⇾ _Generality_ - applicable for all problems of the desired form
* **PSEUDOCODE**
    - high - level desciption of an algorithm that uses the structural conventions of a programming language 
    - intended for human reading
    - **Preconditions** - describe valid input
    - **Postconditions** - conditions that the output should satisfy
___

### Week 9:

- For this week, we discussed the types of algorithm procedures that we can use when writing a pseudocode

* **SEARCHING ALGORITHMS** </br>
    ↳ Problem of locating an algorithm in an ordered list
    - **Binary Search** - comparing the middle values of a list then repeated until the desired output is found.

* **SORTING ALGORITHMS** </br>
    ↳ Problem of assorting elements into increasing order

* **GREEDY ALGORITHMS** </br>
    ↳ Algorithms that make what seems to be the "best" choice at each step.

- We also started on the **Growth of Functions** (Big-O Notation)
___

### Week 10:


* **Big-O Notation**
* **Big-Omega and Big-Theta Notation**</br>
        ↳ **Big-Omega** (Big-Ω) - lower bound </br>
        ↳ **Big-Theta** (Big-Θ) - both upper and lower bound

### Week 12:
- GRAPH THEORY
  - "connecting dots"
  - V = vertices, nodes, entities, people
  - E = edges, connections, route, relationships
  - G = {V, E}
- BASICS:
  - Degree - number of edges incident with vertices
- HANDSHAKING THEOREM = 2e = ∑deg(v)
- EULER CIRCUIT - passes through every edge and goes back to the starting point.
- EULER PATH - passes through every edge without the need to go back to the starting point.
- HAMILTON CIRCUIT - passes through each vertex and goes back to the starting point.
- HAMILTON PATH - passes through each vertex without the need to go back to the starting point.
- PLANAR GRAPH - no edges cross/overlap each other
  - Euler's formula: r = e - v + 2
   - where:
    - r = regions
    - e = edges
    - v = vertices

### Week 13:
- GRAPH COLORING
  - assign color to each vertex where no two vertices have the same color.
  - Chromatic number - least number of colors needed to color the graph.
  - Four Color Theorem - a planar graph's chromatic number will not be greater than four.
- TREES
  - representation of data structures
  - Forest - multiple trees (NO JOKE)
- TREE COMPONENTS
  - Leaves - nodes that do not have children
  - Children/Grandchildren - descendants
  - Ancestors - nodes on top
- M-ary TREE - each vertex of an m-ary tree has m number of descendants.
