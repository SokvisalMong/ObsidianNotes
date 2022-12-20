# Predicates
a property that the subject of the statement *can* have.
    : a sentence which becomes a statements upon substituting values in the domain.

Basically statements involving variables
Example: "computer x is under attacked by an intruder"

"x is greater than 3"
can be denoted by p(x) where *p* denotes "is greater than 3" and is x is the var.

### Pre Conditions & Post Conditions
*PreConditions* are statements that describes valid inputs.
*PostConditions* are statements that describes a valid output.

### N-ary Predicate
A statement involving n varialbes x<sub>1,2,3...n</sub>
can be denoted by p(x<sub>1</sub>, x<sub>2</sub>, ..., x<sub>n</sub>)

p(x<sub>1</sub>, x<sub>2</sub>, ..., x<sub>n</sub>) is value of the propositional function p at n-tuple (x<sub>1</sub>, x<sub>2</sub>, ..., x<sub>n</sub>)

p is also called n-ary predicate / n-place predicate

# Quantifiers

Expresses the extent to which a predicate is true i.e. All, Some, Many, None, Few

There are 2 types:
- Universal (∀): a predicate is true for every element under consideration
- Existential (∃): a predicate is true for atleast 1 element under consideration.

*Predicate Calculus* is logic that deals with predicates and quantifiers.

## Universal (∀)

Domain of discourse is the particular domain in which mathematical statements are true for all values of the domain.

Domain of discourse, or domain, is basically the domain of x, for example X = {1, 2, 3, 4} where p(x) is always true.

If all elements can be listed x<sub>1, 2, ..., n</sub>
Thus, ∀xp(x) = p(x<sub>1</sub>) <tag>&and;</tag> p(x<sub>2</sub>) ... <tag>&and;</tag> p(x<sub>n</sub>)

An element x for which p(x) is false is called a *counter example* of ∀x p(x).

## Existential (∃)

Existential Quantification are mathmatical statements in which there is an element with a certain property.

Or, it is true if atleast one element is true.

If all elements can be listed x<sub>1, 2, ..., n</sub>
Thus, ∃xp(x) = p(x<sub>1</sub>) <tag>&or;</tag> p(x<sub>2</sub>) ... <tag>&or;</tag> p(x<sub>n</sub>)

## Uniqueness Quantifier (∃! or ∃<sub>1</sub>)

There exists a unique x such that p(x) is true ∃!p(x)

or simply

THere is exactly 1 x that p(x) is true.

#### Precedence
These 2 quantifiers have higher precedences than all others.

### Binding Variables
A variable is free, unless it is bound by a qunaitifer.

A *scope* is the part of a logical expression which a quantifer is applied.

Basically anything attached to the ∃ or ∀ is bound

## Logical Equivalences Involving Quantifiers
2 statements involving predicates and quantifers are logically equiv iff they have the same truth value no matter which predicates are substituted.

Denoted by S ≡ T to indicate statements S and T are logically equiv

## Logic Programming

Prolog (Programming in Logic) is the use of a type of programming language designed to reason using rules of predicates.

Prolog programs include 2 types of statement to be declared:
- Facts: Define predicates specifying elements it satisfies.
- Rules: Define new predicates using ones already defined by Facts