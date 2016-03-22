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

#Week 5
- This week, we continued the discussion of methods of proving.
- The proof by contradiction was introduced to us.
- This method of proving is different form the previous methods because it is not dependent on the format of implication. All you have to do is prove that the negation of the premise is T. If it is not then the original premise is T.
- The combination of direct and direct proof is use in proof by Equivalence.
- I am sometimes confused in which method should I use. 
- I am also confused in how should I prove that a statement is true by assuming that the other statement is true.
- But sir told us a "tip": assign the goal and that is what you want to show.
- We were also able to discuss Mathematical Induction in which at first, I am having a hard time to understand.
- Mathematical Induction has two steps: 
 - Basis Step in which you have to show that P(n) to be true.
 - Inductive Step in which you have to show that P(n+1) is also true.
- Recursive induction was also discussed and it is quite easy to understand given a simple function.

#Week 6
- We had an introduction about set theory in which we tackled about the meaning of some familiar terms such as:
 - Set -  an unordered collection of distinct objects, which may be anything (including other sets).
 - Subset - A set S is a subset of a set T (denoted S ⊆ T) if all elements of S are also elements of T.
 - Cardinality - The cardinality of a set is the number of elements it contains.
- I learned that two sets may be equivalent regardless of the order and repetitions of the elements inside it.
- Some set operations were also tackled namely:
 - Union
 - Intersection
 - Set Difference 
 - Symmetric Difference
- We also learned that the cardinality of natural numbers (which is infinity) is actually called "aleph-zero", "alephnought", or "alephnull".
- We talked about Set Identities which is also patterned from Logical Equivalences.

#Week 7
- We had an introduction about Functions which is defined as the assignment of exactly one element of B to each element of A. (Let A and B be sets)
- I am still having a hard time in distinguishing the function's domain and codomain. 
- Sir told us that the range are the values that actually come out.
- We dicussed about the different types of functions:
  - One-to-one Function (Injective) - Functions that never assign the same value to two different domain elements; No value in the range is used by more than one value in the domain.
  - Onto Function (Surjective) - Functions have equal range and codomain; For every value in the codomain, there is a value in the domain that is mapped to it.
  - One-to-one Correspondence (Bijection) - If a function f is both one-to-one and onto, then it is a one-to-one correspondence.
- I learned that a function such as f(x)=x^2 can be one type or another depending on the domain given (e.g. set of integers or set of positive integers)

#Week 8
- Sir introduced us to algorithms which is defined as a finite set of precise instructions for performing a computation or for solving a problem.
- I think this topic is one of the most confusing topics in this subject since we are like programming without using any programming language.
- We also learned what a pseudocode is and Sir told us that when the problem in the quiz states that we should "define" the algorithm, he is asking for the pseudocode :)
- A Precondition is a statement that describe valid input.
- A Postcondition is a condition that the output should satisfy when the program has run.
- There are 6 properties of algorithms:
 - Input 
 - Output
 - Definiteness
 - Correctness
 - Finiteness
 - Generality
- Searching Algorithm is defined as the problem of locating an element in an ordered  list.
- There are two types of Seaching algorithms discussed: Linear and Binary.
- We also discussed the two types of Sorting Algorithms: Bubble Sort and Insertion Sort.
- I am having a hard time understanding and making the pseudocode when I am not using a programming language to check it.
- So as an alternative, Sir told us to use an iteration table which, I think, will be helpful during our quiz.

#Week 9
- Sir taught us what a greedy algorithm is : selecting the best choice at each step instead of considering all sequences of steps that may lead to an optimal solution.
- Growth of functions is used to know the number of algorithms a program has.
- It is useful to know which algorithm (same program, different algorithm) is better -- the smaller the value, the better.
- Big O notation was described as the upper bound of the function.
- In Big O notation, the constants C and K (witnesses) are necessary.
- Big O will be useless without the witnesses because the CORRECT witnesses will be helpful in making the g(x) become the upper bound of the f(x).
- I learned that the witnesses cannot be negative because if they are negative, there would be no growth anymore.
- I also learned that C is the multiplier of the function and k is the value of input where the overtaking started.
- Common Big-O estimates was further discussed and I learned that Big-O doesn't provide a lower bound for the size of f(x).
- We were introduced to Big Omega and Big Theta.
- Big Omega provides the lower bound while Big Theta provides both upper and lower bound.
- Using Big Theta is more desirable because it only gives us one answer, while Big O and Big Omega can give us multiple answers.

#Week 10
- Time complexity was discussed and it's really hard to understand.
- It can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
		
  | Complexity | Terminology |
  | :---: | :---: |
  | ϴ(1) | constant complexity |
  | ϴ(log n) | log complexity |
  | ϴ(n) | linear complexity |
  | ϴ(n log n) | n log n complexity |
  | ϴ(n^b) | polynomial complexity |
  | ϴ(b^n) | exponential complexity |
  | ϴ(n!) | factorial complexity |

- Time complexity is dependent on the number of comparisons an algorithm have.
- Getting the time complexity is confusing so Sir used an iteration table to be able to explain how to get the number of comparisons.
