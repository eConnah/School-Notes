# Quantifiers
$\forall x$ - This means 'for all x'.
$\exists x$ - This means 'there exists an x'

# For All - $\forall$
$\forall x \in S (P(x))$ - This means for all $x$'s in the set $S$ the property $P(x)$ is true. It can also be written as $\forall x ( x \in S \rightarrow P(x))$. The implication $x \in S \rightarrow P(x)$ ensures we only care about the $x$'s that are a member of $S$.
So as an example $\forall x \in \mathbb{N} (x > 0)$ which means for all x's (numbers) in natural numbers x > 0. Can also be written as $\forall x (x \in \mathbb{N} \rightarrow x > 0)$.

# There Exists - $\exists$
$\exists x \in S(P(x))$ - This means there is at least on $x$ in the set $S$ such that $P(x)$ is true. It can also be written as $\exists x (x \in S \land P(x))$.
As an example $\exists x \in \mathbb{Z}(x^{2} = 4)$ or also written as $\exists x (x \in \mathbb{Z} \land x^{2} = 4$)$.

# Nested Quantifiers
When quantifiers are nested, the leftmost quantifier applies first, and the rightmost quantifier depends on the previous ones. For example:
- $\forall x \exists y (...)$ means "For every x, there exists a y (which may depend on x) such that..."
- $\exists y \forall x (...)$ means "There exists a y (fixed) such that for all x..."

## Example 1
Statement 1: $\forall x \exists y(y = x + 1)$
Translation: "For every number x, there exists a number y such that y is x + 1."
Meaning: Every x has a successor (y). True for integers or real numbers.

Statement 2: $\exists y \forall x(y = x + 1)$
Translation: "There exists a single y such that y = x + 1 for all x."
Meaning: A single y works for all x. False, since y would need to be x+1 for every x, which is impossible.

## Example 2
Statement 1: $\forall x \exists y Loves(y, x)$
Translation: "Everyone is loved by someone.
Meaning: Different people might have different lovers.

Statement 2: $∃y∀x Loves(y, x)$
Translation: "There is someone who loves everyone."
Meaning: A single person (y) loves all others.

## Example 3
"Every person has a friend."
Answer: $\forall x \exists y (Person(x) \rightarrow (Person(y) \land Friend(y, x)))$

"There is a language understood by everyone."
Answer: $\exists y \forall x (Language(y) \land (Person(x) \rightarrow Understands(x, y)))$

## Example 4
"Every two people have a common friend."  
$\forall x \forall y \exists z(Person(x) \land Person(y)\rightarrow Friend(z,x) \land Friend(z,y))$

"There exist two distinct primes."
$\forall x \exists y(Prime(x) \land Prime(y) \land x \neq y)$