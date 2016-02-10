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

