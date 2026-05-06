# Solution Key: Sets and Relations

This document provides step-by-step solutions for the problems presented in the Question-Based Pedagogy module for Sets and Relations.

---

## Phase 1: Foundation (The Basics of Sets)

**Q1.1: "The collection of all intelligent students in your class." Is this a set? Why or why not?**
- **Solution:** No, it is **not a set**.
- **Reason:** A set must be a *well-defined* collection. The term "intelligent" is subjective and lacks a precise, objective criterion for inclusion. Different people might include different students, meaning the collection is not well-defined.

**Q1.2: If $S$ is the collection of all vowels in the English alphabet, write $S$ in Roster form.**
- **Solution:** $S = \{a, e, i, o, u\}$

**Q1.3: Express the set $A = \{x : x \in \mathbb{Z}, -3 < x \leq 4\}$ in Roster form.**
- **Solution:** The integers greater than $-3$ and less than or equal to $4$ are:
- $A = \{-2, -1, 0, 1, 2, 3, 4\}$

**Q1.4: Convert $B = \{1, 4, 9, 16, 25, \dots\}$ into Set-builder notation.**
- **Solution:** Each element is a perfect square of a natural number ($1^2, 2^2, 3^2, \dots$).
- $B = \{x : x = n^2, n \in \mathbb{N}\}$

**Q1.5: What is the cardinality $|A|$ of the set $A = \{x : x \text{ is a letter in the word 'MATHEMATICS'}\}$?**
- **Step 1:** List the distinct letters: M, A, T, H, E, I, C, S.
- **Step 2:** Count them: There are 8 distinct letters.
- **Solution:** $|A| = 8$

**Q1.6: Is the set of all concentric circles in a plane finite or infinite?**
- **Solution:** **Infinite**.
- **Reason:** For a fixed center, a circle can be drawn for any real number radius $r > 0$. Since there are infinitely many real numbers, there are infinitely many such circles.

**Q1.7: Consider $A = \phi$ (the empty set). What is $|A|$? Is $\phi = \{0\}$?**
- **Solution:** $|A| = 0$.
- **No**, $\phi \neq \{0\}$. $\phi$ contains no elements, whereas $\{0\}$ is a singleton set containing the number zero.

**Q1.8: Define a Singleton set. Give an example using set-builder notation.**
- **Definition:** A set containing exactly one element.
- **Example:** $A = \{x : x \in \mathbb{N}, 1 < x < 3\} = \{2\}$

**Q1.9: If $A = \{1, 2, 3\}$ and $B = \{3, 2, 1\}$, are $A$ and $B$ equal? Does the order of elements matter?**
- **Solution:** Yes, $A = B$.
- **Order:** No, the order of elements does not matter in a set.

**Q1.10: If $C = \{1, 2, 2, 3, 3, 3\}$, what is $|C|$? Do repeated elements increase cardinality?**
- **Solution:** $|C| = 3$.
- **Repeated Elements:** No, repeated elements are counted only once in a set.

**Q1.11: If $x \in A$ implies $x \in B$ for every $x$, what is the relationship between $A$ and $B$? Use the symbol $\subseteq$.**
- **Solution:** $A \subseteq B$ ($A$ is a subset of $B$).

**Q1.12: For $A = \{1, 2\}$, list all possible subsets of $A$. Don't forget the empty set!**
- **Solution:** $\phi, \{1\}, \{2\}, \{1, 2\}$

**Q1.13: What is a 'Proper Subset'? Is $A$ a proper subset of $A$?**
- **Definition:** $A$ is a proper subset of $B$ (written $A \subset B$) if $A \subseteq B$ and $A \neq B$.
- **Solution:** No, $A$ is not a proper subset of itself.

**Q1.14: Let $P(A)$ be the Power Set of $A$. If $|A| = n$, prove or verify that $|P(A)| = 2^n$ using $A = \{1, 2, 3\}$.**
- **Step 1:** $|A| = 3$, so $n=3$.
- **Step 2:** List subsets: $\phi, \{1\}, \{2\}, \{3\}, \{1, 2\}, \{1, 3\}, \{2, 3\}, \{1, 2, 3\}$.
- **Step 3:** Count: Total 8 subsets.
- **Verification:** $2^n = 2^3 = 8$. Since $8=8$, the formula is verified.

**Q1.15: What is the Universal Set $U$ in the context of the set of all integers and the set of all rational numbers?**
- **Solution:** A suitable Universal Set would be $\mathbb{Q}$ (the set of all rational numbers), $\mathbb{R}$ (real numbers), or $\mathbb{C}$ (complex numbers). In this specific context, $\mathbb{Q}$ is the smallest common universal set.

---

## Phase 2: Concept Building (Set Operations & Laws)

**Q2.1: If $A = \{1, 2, 3\}$ and $B = \{3, 4, 5\}$, find the Union $A \cup B$. What does the "$\cup$" operation represent intuitively?**
- **Solution:** $A \cup B = \{1, 2, 3, 4, 5\}$
- **Intuition:** The union represents the collection of elements that are in $A$ OR in $B$ (or both).

**Q2.2: For the same $A$ and $B$, find the Intersection $A \cap B$. What does the "$\cap$" operation represent?**
- **Solution:** $A \cap B = \{3\}$
- **Intuition:** The intersection represents the collection of elements that are in BOTH $A$ AND $B$.

**Q2.3: If $A \cap B = \phi$, what are these sets called? Give a real-world example of two such sets.**
- **Solution:** They are called **Disjoint Sets**.
- **Example:** The set of all humans currently in Asia and the set of all humans currently in North America.

**Q2.4: Let $U = \{1, 2, 3, \dots, 10\}$ and $A = \{2, 4, 6, 8, 10\}$. Find $A'$ (the complement of $A$). What is $A \cup A'$?**
- **Solution:** $A' = \{1, 3, 5, 7, 9\}$
- **Property:** $A \cup A' = U = \{1, 2, 3, \dots, 10\}$

**Q2.5: Define the Difference $A - B$. If $A = \{1, 2, 3, 4\}$ and $B = \{3, 4, 5, 6\}$, what is $A - B$?**
- **Definition:** $A - B$ is the set of elements that are in $A$ but NOT in $B$.
- **Solution:** $A - B = \{1, 2\}$

**Q2.6: In Q2.5, find $B - A$. Is $A - B = B - A$?**
- **Solution:** $B - A = \{5, 6\}$
- **Conclusion:** No, $A - B \neq B - A$ (Set difference is not commutative).

**Q2.7: The Symmetric Difference is defined as $A \Delta B = (A - B) \cup (B - A)$. Find $A \Delta B$ for $A = \{1, 2, 3\}$ and $B = \{2, 3, 4\}$.**
- **Step 1:** $A - B = \{1\}$
- **Step 2:** $B - A = \{4\}$
- **Step 3:** $A \Delta B = \{1, 4\}$

**Q2.8: Verify the Commutative Law: $A \cup B = B \cup A$ and $A \cap B = B \cap A$.**
- **Verification:** Since order doesn't matter in sets, the collection of elements in $A$ or $B$ is identical to the collection in $B$ or $A$. Similarly for intersection.

**Q2.9: Verify the Associative Law: $(A \cup B) \cup C = A \cup (B \cup C)$.**
- **Verification:** Both sides represent the set of elements belonging to at least one of the sets $A, B$, or $C$.

**Q2.10: Verify the Distributive Law: $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$.**
- **Verification:** An element $x$ is in $A \cap (B \cup C)$ if $x \in A$ AND ($x \in B$ OR $x \in C$). This is logically equivalent to saying ($x \in A$ AND $x \in B$) OR ($x \in A$ AND $x \in C$), which is the definition of $(A \cap B) \cup (A \cap C)$.

**Q2.11: Using a Venn Diagram, shade the region representing $(A \cap B)'$.**
- **Solution:** Shade everything in the Universal set EXCEPT for the overlapping region where $A$ and $B$ meet.

**Q2.12: Now shade the region for $A' \cup B'$. Are they the same? (De Morgan's First Law).**
- **Solution:** Yes, the shaded region for $A' \cup B'$ (everything not in $A$ plus everything not in $B$) is identical to $(A \cap B)'$. This confirms $(A \cap B)' = A' \cup B'$.

**Q2.13: Verify De Morgan's Second Law: $(A \cup B)' = A' \cap B'$.**
- **Verification:** $(A \cup B)'$ is everything outside the union. $A' \cap B'$ is the intersection of everything outside $A$ and everything outside $B$. Both describe the region outside both circles.

**Q2.14: What is $(A')'$?**
- **Solution:** $A$. The complement of the complement is the original set.

**Q2.15: If $|A| = 10, |B| = 15,$ and $|A \cap B| = 5$, find $|A \cup B|$ using the formula $|A \cup B| = |A| + |B| - |A \cap B|$.**
- **Step 1:** $|A \cup B| = 10 + 15 - 5$
- **Step 2:** $|A \cup B| = 25 - 5 = 20$

**Q2.16: Derive the formula for $|A \cup B \cup C|$. How many intersections must be subtracted and added back?**
- **Formula:** $|A \cup B \cup C| = |A| + |B| + |C| - (|A \cap B| + |B \cap C| + |C \cap A|) + |A \cap B \cap C|$
- **Subtract:** 3 pair-wise intersections.
- **Add back:** 1 triple-wise intersection.

**Q2.17: In a class of 50 students, 30 like Cricket, 25 like Football, and 10 like both. How many like neither?**
- **Step 1:** Find students who like at least one: $|C \cup F| = 30 + 25 - 10 = 45$.
- **Step 2:** Subtract from total students: $50 - 45 = 5$.
- **Solution:** 5 students like neither.

**Q2.18: Define the Cartesian Product $A \times B$. If $A = \{a, b\}$ and $B = \{1, 2, 3\}$, list all ordered pairs in $A \times B$.**
- **Definition:** $A \times B = \{(a, b) : a \in A, b \in B\}$
- **Solution:** $A \times B = \{(a, 1), (a, 2), (a, 3), (b, 1), (b, 2), (b, 3)\}$

**Q2.19: Does $A \times B = B \times A$? Under what condition would they be equal?**
- **Solution:** Generally, **No**. $(a, 1) \neq (1, a)$.
- **Condition:** $A \times B = B \times A$ if and only if $A = B$ or if at least one of the sets is empty ($\phi$).

**Q2.20: If $|A| = m$ and $|B| = n$, what is $|A \times B|$?**
- **Solution:** $|A \times B| = m \times n$.

---

## Phase 3: Advanced Application (Relations)

**Q3.1: A Relation $R$ from $A$ to $B$ is any subset of $A \times B$. If $|A| = 2$ and $|B| = 3$, how many possible relations exist?**
- **Step 1:** $|A \times B| = 2 \times 3 = 6$.
- **Step 2:** A relation is a subset of $A \times B$. The number of subsets is $2^{|A \times B|}$.
- **Solution:** $2^6 = 64$ possible relations.

**Q3.2: Let $A = \{1, 2, 3\}$ and $R = \{(1, 1), (1, 2), (2, 3)\}$. What is the Domain of $R$?**
- **Definition:** The set of all first elements of the ordered pairs.
- **Solution:** Domain $= \{1, 2\}$

**Q3.3: For the same $R$ in Q3.2, what is the Range of $R$?**
- **Definition:** The set of all second elements of the ordered pairs.
- **Solution:** Range $= \{1, 2, 3\}$

**Q3.4: What is the Codomain of a relation from $A$ to $B$? How does it differ from the Range?**
- **Solution:** The Codomain is the entire set $B$. The Range is the set of elements in $B$ that are actually mapped to by elements in $A$ (Range $\subseteq$ Codomain).

**Q3.5: A relation $R$ on set $A$ is Reflexive if $(a, a) \in R$ for every $a \in A$. If $A = \{1, 2\}$, is $R = \{(1, 1), (2, 2), (1, 2)\}$ reflexive?**
- **Check:** For $A=\{1, 2\}$, we need $(1, 1) \in R$ and $(2, 2) \in R$.
- **Solution:** **Yes**, it is reflexive.

**Q3.6: What is the smallest reflexive relation on $A = \{1, 2, 3\}$? This is often called the Identity Relation $I_A$.**
- **Solution:** $I_A = \{(1, 1), (2, 2), (3, 3)\}$

**Q3.7: A relation is Symmetric if $(a, b) \in R \Rightarrow (b, a) \in R$. Is $R = \{(1, 2), (2, 1), (1, 1)\}$ on $A = \{1, 2\}$ symmetric?**
- **Check:** $(1, 2) \in R \implies (2, 1) \in R$. $(1, 1)$ is its own reverse.
- **Solution:** **Yes**, it is symmetric.

**Q3.8: Give an example of a relation that is symmetric but not reflexive.**
- **Example:** $A = \{1, 2\}$, $R = \{(1, 2), (2, 1)\}$. It is symmetric, but $(1, 1) \notin R$ and $(2, 2) \notin R$.

**Q3.9: A relation is Transitive if $(a, b) \in R$ and $(b, c) \in R \Rightarrow (a, c) \in R$. If $R = \{(1, 2), (2, 3), (1, 3)\}$, is it transitive?**
- **Check:** $(1, 2)$ and $(2, 3)$ are in $R$. We need $(1, 3)$ to be in $R$. It is.
- **Solution:** **Yes**, it is transitive.

**Q3.10: Consider the "less than" relation ($<$) on $\mathbb{R}$. Is it reflexive? Symmetric? Transitive?**
- **Reflexive:** No, $x < x$ is false.
- **Symmetric:** No, $x < y \not\implies y < x$.
- **Transitive:** Yes, $x < y$ and $y < z \implies x < z$.

**Q3.11: What do we call a relation that is Reflexive, Symmetric, and Transitive?**
- **Solution:** An **Equivalence Relation**.

**Q3.12: Prove that the relation "is parallel to" on the set of all lines in a plane is an Equivalence Relation. (Assume a line is parallel to itself).**
- **Reflexive:** $L || L$ (given).
- **Symmetric:** If $L_1 || L_2$, then $L_1$ and $L_2$ have the same slope, so $L_2 || L_1$.
- **Transitive:** If $L_1 || L_2$ and $L_2 || L_3$, then $L_1$ and $L_3$ share the same slope as $L_2$, so $L_1 || L_3$.
- **Conclusion:** It is an equivalence relation.

**Q3.13: A relation is Anti-symmetric if $(a, b) \in R$ and $(b, a) \in R \Rightarrow a = b$. Is the "subset" relation ($\subseteq$) on $P(U)$ anti-symmetric?**
- **Solution:** **Yes**. If $A \subseteq B$ and $B \subseteq A$, then by definition $A = B$.

**Q3.14: For an equivalence relation $R$ on $A$, the Equivalence Class $[a]$ is the set $\{x \in A : (a, x) \in R\}$. If $R$ is "congruence modulo 2" on $\mathbb{Z}$, what are the equivalence classes?**
- **Solution:** There are two equivalence classes:
- $[0] = \{x \in \mathbb{Z} : x \equiv 0 \pmod 2\} = \{\dots, -4, -2, 0, 2, 4, \dots\}$ (Even integers)
- $[1] = \{x \in \mathbb{Z} : x \equiv 1 \pmod 2\} = \{\dots, -3, -1, 1, 3, 5, \dots\}$ (Odd integers)

**Q3.15: Let $R$ be a relation from $A$ to $B$ and $S$ be a relation from $B$ to $C$. Define the Composition $S \circ R$. If $R = \{(1, a), (2, b)\}$ and $S = \{(a, \alpha), (b, \beta)\}$, find $S \circ R$.**
- **Definition:** $S \circ R = \{(x, z) : \exists y \text{ s.t. } (x, y) \in R \text{ and } (y, z) \in S\}$
- **Step 1:** $1 \xrightarrow{R} a \xrightarrow{S} \alpha$, so $(1, \alpha) \in S \circ R$.
- **Step 2:** $2 \xrightarrow{R} b \xrightarrow{S} \beta$, so $(2, \beta) \in S \circ R$.
- **Solution:** $S \circ R = \{(1, \alpha), (2, \beta)\}$
