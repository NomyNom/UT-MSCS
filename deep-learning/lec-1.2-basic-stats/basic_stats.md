## Probability

```
P(X = a)

X = random variable
a = outcome
(X = a) = event
```

## Probability Density

A way to describe probabilities that dont fall into categories like heads or tails

```
P(Y = alpha)

NOT DEFINED
```

So a good example:

- what is the probability of a coin landing at a certain angle



## Cumulative Probability

BUT we can describe the probabilty through a certain range, sinc we can describe the probability of the exact angle of how the coin will land

```
P(alpha1 < Y < alpha2)
```

```
p(Y = alpha) = P((alpha - e <= Y < alpha + e)) / 2e
```

## What is P?
- a function
- Discrete P : {c1, c2, ... , cn} -> [0,1]
- Continuous P : R -> R

```
Discrete P : Summation of P(x) * f(x)

Continuous P : Integral of P(x) * f(x) dx
```

## Expectation
The long-term average or center of mass of a random variable's possible outcomes

It is linear so:
```
E[f(x) + g(x)] = E[f(x)] + E[g(x)]

E[alpha * f(x)] = alpha * E[f(x)]
```

you can also compute MEAN and VARIANCE, im too lazy to write out the formulas

---
# Unified notations: a word of warning

Discrete distribution:

- Variance is always finite
- P(X) ALWAYS less than 1

<br>

Continuous distribution:

- Variance is always infinite
- P(X) CAN be LARGER than 1
---


