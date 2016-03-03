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
 - We learned about the meaning ofpredicate logic.
 - We also discussed what a quantifier is and its two types.
 - I had a hard time understanding the statements including two types of quantifiers - universal and existensial.
 
#Week 3
- Sir taught us about the Rules of Inference.
- In line with this, we talked about the meaning of an argument.
- I had fun in distinguishing if an argument is valid or not.
- We applied our previous learnings about logical connectives in proving if an argument is valid or not.
- We can also use truth table by verfying if the argumant is a tautology.
- We have learned that the validity doesn't depend on the truth of the premises. To remember this, he gave an example about Luis being a girl, which is obviuosly False, but the argument is still valid.


#Week 4
- We are alraedy talking about the meaning of a proof and a disproof.
- We discussed several methods of proving theorems.
- The first one is a direct proof where you assume that the first statement (p) is true, then prove that the second statement(q) is also true.
- The second one is the proof by contraposition where you assume that the negation of q is true then prove that the negation of p is also true.
- The next two are proof by Vacuous and Trivial. These two are easy to remember because they are patterned in the logical connective p → q. When p is F, p → q is automatically T (Vacuous), and when q is T, p → q is automatically T (Trivial).
- I was really confused while studying this topic and I can't understand it immediately and need to have more examples.
- 

#Week 5
- This week, we continued the discussion of methods of proving.
- The proof by contradiction was introduced to us.
- This method of proving is different form the previous methods because it is not dependent on the format of implication. All you have to do is prove that the negation of the premise is T. If it is not then the original premise is T.
- The combination of direct and direct proof is use in proof by Equivalence.
- I am sometimes confused in which method should I use. 
- I am also confused in how should I prove that a statement is true by assuming that the other statement is true.
- But sir told us a "tip": assign the goal and that is what you want to show.
- We were also able to discuss Mathematical Induction in which at first, I am having a hard time to understand.
