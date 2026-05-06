# Question-Based Pedagogy: Sets and Relations

## Objective
To master the formal language of Set Theory, understand algebraic operations on sets, and transition into the study of Relations and their properties, providing a foundation for Functions and Calculus.

---

## Phase 1: Foundation (The Basics of Sets)

- **Q1.1:** Consider the following: "The collection of all intelligent students in your class." Is this a set? Why or why not?
- **Q1.2:** If $S$ is the collection of all vowels in the English alphabet, write $S$ in Roster form.
- **Q1.3:** Express the set $A = \{x : x \in \mathbb{Z}, -3 < x \leq 4\}$ in Roster form.
- **Q1.4:** Convert $B = \{1, 4, 9, 16, 25, \dots\}$ into Set-builder notation.
- **Q1.5:** What is the cardinality $|A|$ of the set $A = \{x : x \text{ is a letter in the word 'MATHEMATICS'}\}$?
- **Q1.6:** Is the set of all concentric circles in a plane finite or infinite?
- **Q1.7:** Consider $A = \phi$ (the empty set). What is $|A|$? Is $\phi = \{0\}$?
- **Q1.8:** Define a Singleton set. Give an example using set-builder notation.
- **Q1.9:** If $A = \{1, 2, 3\}$ and $B = \{3, 2, 1\}$, are $A$ and $B$ equal? Does the order of elements matter?
- **Q1.10:** If $C = \{1, 2, 2, 3, 3, 3\}$, what is $|C|$? Do repeated elements increase cardinality?
- **Q1.11:** If $x \in A$ implies $x \in B$ for every $x$, what is the relationship between $A$ and $B$? Use the symbol $\subseteq$.
- **Q1.12:** For $A = \{1, 2\}$, list all possible subsets of $A$. Don't forget the empty set!
- **Q1.13:** What is a 'Proper Subset'? Is $A$ a proper subset of $A$?
- **Q1.14:** Let $P(A)$ be the Power Set of $A$. If $|A| = n$, prove or verify that $|P(A)| = 2^n$ using $A = \{1, 2, 3\}$.
- **Q1.15:** What is the Universal Set $U$ in the context of the set of all integers and the set of all rational numbers?

**Concept Takeaway:** A set is a **well-defined** collection of distinct objects. The cardinality $|A|$ counts these objects. Subsets represent "parts" of a set, and the Power Set $P(A)$ contains all possible parts, with total count $2^{|A|}$.

---

## Phase 2: Concept Building (Set Operations & Laws)

- **Q2.1:** If $A = \{1, 2, 3\}$ and $B = \{3, 4, 5\}$, find the Union $A \cup B$. What does the "$\cup$" operation represent intuitively?
- **Q2.2:** For the same $A$ and $B$, find the Intersection $A \cap B$. What does the "$\cap$" operation represent?
- **Q2.3:** If $A \cap B = \phi$, what are these sets called? Give a real-world example of two such sets.
- **Q2.4:** Let $U = \{1, 2, 3, \dots, 10\}$ and $A = \{2, 4, 6, 8, 10\}$. Find $A'$ (the complement of $A$). What is $A \cup A'$?
- **Q2.5:** Define the Difference $A - B$. If $A = \{1, 2, 3, 4\}$ and $B = \{3, 4, 5, 6\}$, what is $A - B$?
- **Q2.6:** In Q2.5, find $B - A$. Is $A - B = B - A$?
- **Q2.7:** The Symmetric Difference is defined as $A \Delta B = (A - B) \cup (B - A)$. Find $A \Delta B$ for $A = \{1, 2, 3\}$ and $B = \{2, 3, 4\}$.
- **Q2.8:** Verify the Commutative Law: $A \cup B = B \cup A$ and $A \cap B = B \cap A$.
- **Q2.9:** Verify the Associative Law: $(A \cup B) \cup C = A \cup (B \cup C)$.
- **Q2.10:** Verify the Distributive Law: $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$.
- **Q2.11:** Using a Venn Diagram, shade the region representing $(A \cap B)'$.
- **Q2.12:** Now shade the region for $A' \cup B'$. Are they the same? (De Morgan's First Law).
- **Q2.13:** Verify De Morgan's Second Law: $(A \cup B)' = A' \cap B'$.
- **Q2.14:** What is $(A')'$?
- **Q2.15:** If $|A| = 10, |B| = 15,$ and $|A \cap B| = 5$, find $|A \cup B|$ using the formula $|A \cup B| = |A| + |B| - |A \cap B|$.
- **Q2.16:** Derive the formula for $|A \cup B \cup C|$. How many intersections must be subtracted and added back?
- **Q2.17:** In a class of 50 students, 30 like Cricket, 25 like Football, and 10 like both. How many like neither?
- **Q2.18:** Define the Cartesian Product $A \times B$. If $A = \{a, b\}$ and $B = \{1, 2, 3\}$, list all ordered pairs in $A \times B$.
- **Q2.19:** Does $A \times B = B \times A$? Under what condition would they be equal?
- **Q2.20:** If $|A| = m$ and $|B| = n$, what is $|A \times B|$?

**Concept Takeaway:** Set operations ($\cup, \cap, -, \Delta$) allow us to combine and compare collections. **De Morgan's Laws** link union, intersection, and complementation. The **Cartesian Product** $A \times B$ generates ordered pairs, forming the basis for coordinate geometry and relations.

---

## Phase 3: Advanced Application (Relations)

- **Q3.1:** A **Relation** $R$ from $A$ to $B$ is any subset of $A \times B$. If $|A| = 2$ and $|B| = 3$, how many possible relations exist?
- **Q3.2:** Let $A = \{1, 2, 3\}$ and $R = \{(1, 1), (1, 2), (2, 3)\}$. What is the **Domain** of $R$?
- **Q3.3:** For the same $R$ in Q3.2, what is the **Range** of $R$?
- **Q3.4:** What is the **Codomain** of a relation from $A$ to $B$? How does it differ from the Range?
- **Q3.5:** A relation $R$ on set $A$ is **Reflexive** if $(a, a) \in R$ for every $a \in A$. If $A = \{1, 2\}$, is $R = \{(1, 1), (2, 2), (1, 2)\}$ reflexive?
- **Q3.6:** What is the smallest reflexive relation on $A = \{1, 2, 3\}$? This is often called the **Identity Relation** $I_A$.
- **Q3.7:** A relation is **Symmetric** if $(a, b) \in R \Rightarrow (b, a) \in R$. Is $R = \{(1, 2), (2, 1), (1, 1)\}$ on $A = \{1, 2\}$ symmetric?
- **Q3.8:** Give an example of a relation that is symmetric but not reflexive.
- **Q3.9:** A relation is **Transitive** if $(a, b) \in R$ and $(b, c) \in R \Rightarrow (a, c) \in R$. If $R = \{(1, 2), (2, 3), (1, 3)\}$, is it transitive?
- **Q3.10:** Consider the "less than" relation ($<$) on $\mathbb{R}$. Is it reflexive? Symmetric? Transitive?
- **Q3.11:** What do we call a relation that is Reflexive, Symmetric, and Transitive?
- **Q3.12:** Prove that the relation "is parallel to" on the set of all lines in a plane is an **Equivalence Relation**. (Assume a line is parallel to itself).
- **Q3.13:** A relation is **Anti-symmetric** if $(a, b) \in R$ and $(b, a) \in R \Rightarrow a = b$. Is the "subset" relation ($\subseteq$) on $P(U)$ anti-symmetric?
- **Q3.14:** For an equivalence relation $R$ on $A$, the **Equivalence Class** $[a]$ is the set $\{x \in A : (a, x) \in R\}$. If $R$ is "congruence modulo 2" on $\mathbb{Z}$, what are the equivalence classes?
- **Q3.15:** Let $R$ be a relation from $A$ to $B$ and $S$ be a relation from $B$ to $C$. Define the **Composition** $S \circ R$. If $R = \{(1, a), (2, b)\}$ and $S = \{(a, \alpha), (b, \beta)\}$, find $S \circ R$.

**Concept Takeaway:** A relation is a structured way to link elements of sets. **Equivalence Relations** are particularly powerful as they partition a set into disjoint **Equivalence Classes**, effectively grouping elements that are "the same" under a specific criteria.
