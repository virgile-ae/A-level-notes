## 4.1 Binomial Expansion

### Integer Powers

$$
{n \choose r} =\frac{n!}{r!(n-r)!}
$$

$$
(a+bx)^n=a^n+ {n\choose 1}a^{n-1}bx+\cdots+{n\choose n-1}a(bx)^{n-1}+(bx)^n
$$

The general term for $(a+b)^n$ is given by ${n\choose r}a^{n-r}b^r$.

### Negative or Fractional Powers

$(1+x)^n=1+nx+\frac{n(n-1)}{2!}x^2+\cdots+\frac{n(n-1)\dots(n-r+1)}{r!}x^r + \cdots$

* This is an infinite series and is valid iff $|x|<1, n\in\R$.
* Approximations are more accurate when
    * More terms in the expansion are used.
    * The value of $x$ are closer to 0.
* The expansion of $(1+bx)^n$ is valid iff $|bx|<1$.
* To expand $(a+bx)^n$, you convert it into the form $a^n(1+\frac bax)^n$.
    * This is valid iff $|\frac b ax|<1$.

### Binomial Estimation

For $(a+bx)^n$

* If $|x|<1$, then $x^n$ gets smaller as $n$ gets bigger.
* Therefore we can ignore larger powers for an estimate.
* Including more terms increases accuracy.
* The closer $x$ is to $0$, the more accurate the estimation.

## 4.2 Sequences

* **Increasing sequences** have terms which increase in magnitude. $u_{n+1}\ge u_n$ for all $n\in\mathbb{N}$.
* **Decreasing sequences** have terms which decrease in magnitude. $u_{n+1}\le u_n$ for all $n\in\mathbb{N}$.
* **Strictly** increasing or decreasing sequences have $u_{n+1}>u_n$ and $u_{n+1}<u_n$ for all $n\in\mathbb{N}$, respectively.
* **Periodic sequences** have terms which repeat periodically. There is a $k\in\mathbb{N}$ such that $u_{n+k}=u_n$ for all $n\in\mathbb{N}$. $k$ is called the **order** of the sequence.

## 4.3 Sigma Notation for Sums of Series

$$
\sum_{i=1}^{n}f(i)\equiv f(1)+f(2)+f(3) + ... + f(n-1) + f(n)
$$

## 4.4 Arithmetic Sequences and Series

In an arithmetic sequence, the difference between consecutive terms is constant.

$$
u_n=a +(n-1)d
$$

### Recurrence relation

$$
u_{n+1}=u_n+d\\u_1=a
$$

**Where**

* $u_n$ is the $n$th term of the sequence.
* $a$ is the first term.
* $d$ is the common difference between terms.

### Series

An arithmetic series is the sum of the terms of an arithmetic sequence.

$$
S_n=\frac n2[2a+(n-1)d]\\S_n=\frac n2(a_1+a_n)
$$

## 4.5 Geometric Sequences

A geometric sequence has a common ration between two terms.

$$
u_n=ar^{n-1}
$$

**Where**

* $u_n$ is the $n$th term of the sequence.
* $a$ is the first term.
* $r$ is the common ratio ($r\ne1$).

### Recurrence relation

$$
u_{n+1}=a_nr\\u_1=a
$$

### Geometric Series

$$
S_n=\frac{a(1-r^n)}{1-r}=\frac{a(r^n-1)}{r-1}, \space r\ne1
$$

### Sum to Infinity

$$
S_\infty=\frac{a}{1-r}
$$

* This only works for series which converge (i.e. approach a value as the series continues).
* This is only true for $|r| < 1$.

## 4.6 Sequences and Series for Modelling