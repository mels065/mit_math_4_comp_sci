# Lecture 1: Introduction and Proofs

## Proofs

A method for ascertaining the truth.

### How to ascertain truth?

* Experimentation & observation
* Sampling & counter examples
* Judge & jury
* Word of God
* Boss
* Conviction

A <ins>***mathematical proof***</ins> is a verification of a <ins>***proposition***</ins> by a chain of logical deductions from a set of <ins>***axioms***</ins>.

*Def:* A proposition is a statement that is either true or false

*Ex.* **2 + 3 = 5**

*Ex.* **$\forall$n$\in$$\mathbb{N}$, n<sup>2</sup>+n+41** is a prime number

**$\forall$** = For all

**$\mathbb{N}$ = {0, 1, 2, 3, ...}** (Natural Numbers)

n<sup>2</sup>+n+41** is a prime number = Predicate

*Predicate*: proposition whose truth depends on the value of variable(s).

| **n** | **n<sup>2</sup>+n+41** | prime |
| ----- | ---------------------- | ----- |
| **0** | **41**                 | Y     |
| **1** | **43**                 | Y     |
| **2** | **47**                 | Y     |
| **3** | **53**                 | Y     |
| ...   | ...                    | ...   |
| **20**| **401**                | Y     |
| ...   | ...                    | ...   |
| **39**| **1601**               | Y     |
| **40**| **1681**               | N     |


**40<sup>2</sup>+40+41=1681**

*Ex.* **a<sup>4</sup>+b<sup>4</sup>+c<sup>4</sup>=d<sup>4</sup>** has no positive integer solutions.

a = **95,800**
b = **217,519**
c = **414,560**
d = **422,481**

*Revision:* **$\exists$a,b,c,d$\in$$\mathbb{N}$<sup>+</sup>, a<sup>4</sup>+b<sup>4</sup>+c<sup>4</sup>=d<sup>4</sup>**

**$\exists$** = There exists

$\mathbb{N}$<sup>+</sup>: Positive natural numbers

*Ex.* **313(x<sup>3</sup>+y<sup>3</sup>=z<sup>3</sup>** has no positive integer solutions (**False**)

We need to figure out proofs because security depends on effective cryptography.

*Ex.* The regions in any map can be colored in 4 colors so that adjacent regions have different colors. (conjectured by Guthrie in *1853*; proved by Appel & Haken in 1977)

*Ex.* Every even integer but 2 is the sum of two primes.

**24=11+13**

**$\forall$ $\in$ $\mathbb{Z}$, n $\geq$ 2 $\rightarrow$ n<sup>2</sup> $\geq$ 4**

$\mathbb{Z}$ = Integers

*Def.* An *implication* **p $\rightarrow$ q** is true if p is false or q is true

p | q | p $\rightarrow$ q| q $\leftrightarrow$ p | p $\leftrightarrow$ q |
--|---|------------------|-----------------------|-----------------------|
T | T | T                | T                     | T
T | F | F                | T                     | F
F | T | T                | F                     | F
F | F | T                | T                     | T

pigs fly $\rightarrow$ I'm king = True

Ex. **$\forall$n$\in$$\mathbb{Z}$, n $\geq$  2 $\leftrightarrow$ n<sup>2</sup> $\geq$** 4 (False)

*Def:* An axiom is a proposition that is "assumed" to be true.

*Ex.* If **a=b & b=c, a=c**

*Euclidean Geometry:* Given a line L & a pt. p not on L, there is a line through p parallel to L.

*Spherical Geometry*: Not such line.

*Hyperbolic Geometry*: There are infinitely many lines.

Axioms should be:
1. Consistent
2. Complete

*Def.* A set of axioms is *consistent* if no proposition can be proved to be both T & F.

Def. A set of axioms is said to be *complete* if it can be used to prove every proposition is either T or F.
