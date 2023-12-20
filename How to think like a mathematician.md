## Sets and Functions

* A set is a well-defined collection of objects.
* The empty set ($\varnothing$) has no elements.
* The cardinality of a finite set is the number of elements in the set.
* The set $Y$ is a subset of $X$ ($X\subseteq Y$) if every element of $Y$ is in $X$.
* A subset $Y$ of $X$ is a proper subset if it is not equal to $X$.
* The union of $X$ and $Y$ ($X\cup Y$) is the collection of elements that are in $X$ or $Y$.
* The intersection of $X$ and $Y$ ($X\cap Y$) is the collection of elements that are in both $X$ and $Y$.
* The product of $X$ and $Y$ is the set of all pairs $(x, y)$ where $x\in X$ and $y\in Y$.
* A function assigns elements of one set to another.
* The codomain is the set of values which a function could map to but doesn't necessarily (because the domain is restricted).

## Reading Mathematics

* Read with a purpose.
* Read actively. Have pen and paper with you.
* You do not have to read in sequence but read systematically.
* Ask questions.
* Read the definitions, theorems and examples first. The proofs can come later.
* Check the text by applying formulas, etc.
* Do exercises and problems.
* Move on if you are stuck.
* Write a summary.
* Reflect - What have you learned?

## Writing Mathematics 1

* Write in simple, punctuated sentences.
* Keep it simple.
* Explain what you are doing.
* Explain you assertions.
* Say what you mean.
* In general, use words rather than symbols.
* Use equals properly - equals means equals.
* Don't draw arrows everywhere - use symbols or numbers to identify equations.
* Proof read.
* Reflect.

## Writing Mathematics 2

* If you use if, then use then.
* Not everything is a formula. Call things by their correct name.
* Don't use the word 'it'.
* Avoid decimal approximations in pure mathematics.
* Don't begin sentences with a symbol.
* Use the implication symbol, $\Longrightarrow$, correctly.
* Use common symbols and notation and define them first.
* Use connecting phrases and synonyms.

## How to Solve Problems

* Use Polya’s four point plan.
* Understand all the words in the problem.
* Guess.
* Write down what you know about the hypothesis and conclusion.
* Work backwards and forwards.
* Work with initial, special and concrete cases.
* Draw a picture.
* Think about a similar problem.
* Find an equivalent problem.
* Solve an easier problem.
* Rewrite in symbols or words.
* Break the problem into pieces.
* Find the right level.
* Give things names.
* Systematically choose a method.
* Check each step.
* Check the answer.
* Find another solution.
* Reflect.

### Exercises 5.2

* How many zeros are at the end of $100!$.
	* Number of multiples of 5 up to 100.
		* $100/5=20$.
	* Number of multiples of 25 up to 100.
		* $100/25=4$.
	* Therefore the number of zeros is 24.
* Find a formula that relates $|X|$, $|Y|$, $|X\cup Y|$, and $|X\cap Y|$.

### Exercises 5.3

1. Show that $\frac{a+b}{2} \ge \sqrt{ab}$ for $0<a\le b$.
	* $a+b\ge \sqrt{4ab}$
	* $a^2 + 2ab + b^2 \ge 4ab$
	* $a^2 - 2ab + b^2 \ge 0$
	* $(a-b)^2\ge 0$
1. Show that $a^2+b^2+c^2\ge ab+bc+ca$ for all positive integers $a$, $b$, and $c$.
1. Let $f(x)=1/(1-x)$. Define the function $f^r$ to be $f^r(x)=f(f(f(…f(f(x)))))$, where $f$ is repeated $r$ times. Find $f^{653}(56)$.
	* $f^1(x) = \frac1{1-x}$
	* $f^2(x)=\frac1{1-\frac1{1-x}}= \frac{1-x}{(1-x)-1}=1-\frac1x$
	* $f^3(x)=\frac1{1-(1-\frac1x)}= x$
	* $\therefore f^n(x)\equiv f^{n+3}(x)$
	* $654\equiv 0 \mod 3$
	* $653\equiv 2\mod 3$
	* $\therefore f^{653}(x)\equiv f^2(x)$
	* $f^2(56)=1-\frac{1}{56}=\frac{55}{56}$
1. Show that
	1. $\sqrt[7]{7!}\lt \sqrt[8]{8!}$
		* $\sqrt[7]{7!} < \sqrt[8]{8} \sqrt[8]{7!}$
		* $(7!)^{\frac17}<8^{\frac 18}\cdot(7!)^{\frac18}$
		* $(7!)^8<8^7\cdot(7!)^7$
		* $\frac{(7!)^8}{(7!)^7}<8^7$
		* $7!<8^7$
		* $2^4\cdot3^2\cdot5\cdot7<2^{21}$
		* $315 < 2^{9}\cdot2^{8}$
		* $315 < 512\cdot 256$
	1. $\sqrt{100001}-\sqrt{100000} \lt \frac1{2\sqrt{100000}}$
		* $\sqrt{100001}\sqrt{100000}-100000<\frac12$
		* $100001\cdot100000<\frac{200001^2}{4}$
		* $200002\cdot200000<200001^2$
		* $(200001+1)(200001-1)<200001^2$
		* $200001^2-1<200001^2$
		* $-1<0$

## Making a Statement

* A statement is a sentence that is either true or false - but not both.
* Law of excluded middle: Statements are true or false; there is no in-between.
* The negation of statement A is the statement that is false when A is true.
* Statements can be constructed using the connectives 'or' and 'and'.
* Two statements are equivalent if they have the same truth table.
* $¬(A\land B)\equiv (¬A) \lor (¬B)$.
* $¬(A\lor B)\equiv(¬A)\land(¬B)$.

## Implications

* In the statement '$A\Longrightarrow$ B' statement $A$ is called the hypothesis or assumption, and statement $B$ is called the conclusion.
* '$A\Longrightarrow B$' can be written as 'If $A$, then $B$'.
* '$A$ implies $B$' means that if $A$ is true, then $B$ is true. Nothing else. If $A$ is false, then $B$ may be true or false.
* The negation of $A\Longrightarrow B$ is the same as '$(¬A) \lor B$'
* '$A$ only if $B$' is the same as '$A\Longrightarrow B$'.
* '$B$ if $A$' is the same as '$A\Longrightarrow B$'.

## Finer Points concerning Implications

* The inverse of '$A\Longrightarrow B$' is '$¬A \Longrightarrow ¬B$'.
* '$A\Longrightarrow B$' true does not mean that '$¬A\Longrightarrow¬B$' is true.
* '$A$ is necessary for $B$' is equivalent to '$B\Longrightarrow A$'.
* '$A$ is sufficient for $B$' is equivalent to '$A\Longrightarrow B$'.
* The contrapositive of '$A\Longrightarrow B$' is '$¬B\Longrightarrow ¬A$'.
* An implication and its contrapositive are equivalent.

## Converse and Equivalence

* Using statements $A$ and $B$, we can combine $¬$ and $\Longrightarrow$ in four ways:
	* $A\Longrightarrow B$,
	* $B\Longrightarrow A$, the converse,
	* $¬A\Longrightarrow¬B$, the inverse,
	* $¬B\Longrightarrow ¬A$, the contrapositive.
* If $A\Longrightarrow B$ is true, then the contrapositive is true.
* If $A\Longrightarrow B$ is true, then the inverse and converse may be true or false.
* If $A\Longrightarrow B$ and $B\Longrightarrow A$, then we say that $A$ and $B$ are equivalent and write $A\iff B$.
* 'iff' is an abbreviation of 'if and only if'.

## Quantifiers - For All and There Exists

* 'For all' is the universal quantifier, denoted $\forall$.
* 'There exists' is the existential quantifier, denoted $\exists$.
* Quantifiers can be combined but order is important.

### Exercises 10.11

* $\forall x \in \mathbb{Z}(x = 0 \lor x = 1\mod 2)$
* $\exists x,y (x + y \text{ is prime})$.
* $\exists x\in \mathbb{R} (x>\sqrt{2})$.
* $\forall x\in\mathbb{R}(x^2 > x)$

## Complexity and Negation of Quantifiers

* The number of quantifiers is a rough measure of the complexity of a statement.
* To show $\forall x\space P(x)$, imagine someone gives you an $x$ and you have to show $P(x)$.
* To show $\exists x\space P(x)$, you have to find (any) $x$ that satisfies $P(x)$.
* To negate a quantified sentence $P$ (i.e. $Q_1x_1Q_2x_2\dots Q_nx_n\space P(x_1, x_2,\dots, x_n)$), change every $\forall$ to $\exists$ and every $\exists$ into $\forall$ and replace $P$ by its negation.

## Examples and Counterexamples

* Create your own examples.
* Collect examples.
* A counterexample is an example that shows that a statement is false.
* Only one counterexample is needed to show that a statement is false.
* Always try to show that a statement is false.

## Definitions, theorems and proofs

* Definition: explains the mathematical meaning of a word.
* Theorem: a very important true statement.
* Proposition: a less important but nonetheless interesting true statement.
* Lemma: a true statement used in proving other true statements.
* Corollary: a true statement that is a simple deduction from a theorem or proposition.
* Proof: the explanation of why a statement is true.
* Conjecture: a statement believed to be true, but for which we have no proof.
* Axiom: a basic assumption about a mathematical situation.

* A definition explains the meaning of a word.
* Theorems, propositions, lemmas and corollaries are all true statements.
* A proof is the explanation of why a statement is true.
* A conjecture is a statement believed to be true, but for which no proof is known.
* An axiom is a basic assumption about a mathematical situation.

## How to read a definition

* 