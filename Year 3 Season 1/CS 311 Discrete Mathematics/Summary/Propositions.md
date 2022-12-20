**Propositions** is the basic building blocks of logic, usually a declarative sentence that is either true or false.

## Logical Operators

### Negations (¬)

| p   | ¬p  |
| --- | --- |
| T   | F   |
| F   | T   |

### Conjunction (∧)

| p   | q   | p ∧ q |
| --- | --- | --- |
| T   | T   | T   |
| T   | F   | F   |
| F   | T   | F   |
| F   | F   | F   |

### Disjunction (∨)

| p   | q   | p ∨ q |
| --- | --- | --- |
| T   | T   | T   |
| T   | F   | T   |
| F   | T   | T   |
| F   | F   | F   |

### Exclusive OR (⊕)

| p   | q   | p ⊕ q |
| --- | --- | --- |
| T   | T   | F   |
| T   | F   | T   |
| F   | T   | T   |
| F   | F   | F   |

### Conditional Statements / Implications (→)

| p   | q   | p → q |
| --- | --- | --- |
| T   | T   | T   |
| T   | F   | F   |
| F   | T   | T   |
| F   | F   | T   |

In conditional statement p → q, **p** is called hte hypothesis (or antecedent or premise) and **q** is called the conclusion (or consequence).

A conditional statement is also called implication.

![[Screenshot_78.png]]

### Contrapositive

Contrapositive of p → q is the ¬q → ¬p

### Converse

The proposition q → p is called the the converse of p → q

### Inverse

The proposition ¬p → ¬q is called the inverse of p → q

### Bi-Conditional Statement (↔)

| p   | q   | p ↔ q |
| --- | --- | ----- |
| T   | T   | T     |
| F   | T   | F     |
| T   | F   | F     |
| F   | F   | T     |
Only true if p and q are the same truth value.

p ↔ q is the proposition "p if and only if q." or "p is necessary and sufficient for q." or "p iff q."

#### Order of operations

| Operator | Precedence |
| -------- | ---------- |
| ¬        | 1          |
| ∧        | 2          |
| ∨        | 3          |
| →        | 4          |
| ↔        | 5          |

