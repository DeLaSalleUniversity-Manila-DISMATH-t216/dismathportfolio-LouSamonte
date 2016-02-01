# dismathportfolio-LouSamonte
# Weekly Learnings
# Week 1
- We were introduced to the subject DISMATH, which is, I think a hard and weird subject.
- As I remembered, DISMATH, that stands for Discrete Mathematics, is more on logical reasoning than Math.
- I understood the meaning of a proposition but I am having a hard time identifying if one statement is a proposition or not.
- Sir Melvin thought us the first four types of logical connectives: negation, conjunction, disjunction, exclusive or.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |

- I learned how to prove using a truth table.
- I learned some keywords that can help me remember the differences among the four connectives: Negation (not) - opposite, Conjunction (and) - minimum, Disjunction (or) - maximum, Exclusive Or - cannot be BOTH.

# Week 2
- I learned about the last two logical connectives - conditional and biconditional.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- I learned that conditional statement is like a promise.
- Two 'shortcuts' I learned about conditional statement 1) If p is false, then (p → q) true. 2) If p is true, then (p → q) true.
- We cannot interchange the variables in a conditional statement (e.g. (p → q) ≠ (q → p))
- We learned the mathematical laws that we can use in proving.

 | Logical Symbol  |  Logical Equivalences |
 | :-------: | :-------: |
 | Identity Laws | p v F ≡ p ; p ∧ T ≡ p|
 | Domination Laws | p v T ≡ F ; p ∧ F ≡ F|
 | Negation Laws | p v (¬p) ≡ T ;  p ∧ (¬p) |
 | Double Negation Law | ¬(¬p) ≡ p |
 | Idempotent Laws | p v p ≡ p ; p ∧ p ≡ p |
 | Cummutative Laws | p v q ≡ q v p ; p ∧ q ≡ q ∧ p |
 | Associative Laws | (p v q) v r ≡ p v (q v r) ; (p ∧ q) ∧ r ≡ p ∧ (q ∧ r) | 
 | Distributive Laws | p v (q ∧ r) ≡  (p v q) ∧ (p v q) ; p ∧ (q v r) ≡  (p ∧ q) v (p ∧ q) |  
 | De Morghan's Laws | ¬(p ∧ q) ≡ ¬p v ¬q |  
 | Absorption Laws | p v (p ∧ q) ≡ p ; p ∧ (p v q) |    
 
 - We were able to prove that ¬(p v (¬p ∧  q)) and ¬p ∧ ¬q are logically equal.
 - While proving the abovementioned example, I learned that quantities "()" are important and disregarding them will lead you to wrong answers.
 - I had some difficulties in identifying which law should I use.
 - But I am starting to love proving... :)
 - I learned the difference between Propositional Logic and Predicate Logic.
 - I learned that there are Quantifiers (Existential and Universal) in Predicate Logic to set the Domain of Discourse.
 - Existential Quantifier (∃x): "there exist"
 - Universal Quantifier (∀x): "for all"
