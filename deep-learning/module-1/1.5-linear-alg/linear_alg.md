
**Linear Algebra in Deep Learning servers one very purpose**

- express many mathematical operations at once

---

## Vectors

- An arrary of numbers or list of nums in python

- 1D array of nums 

```
Vector operations:

v + w = [ v1 + w1 ]
        [   ...   ]

- for vectors w/ the same dim.

- also True for: - , * , /


Vector transpose:
- literally becomes verticle or horizontal since its 1D
```

So we can have n values where it can reach millions of n values and we can simply notate it this way


## Matix

- A 2D array of numbers

```
Matrix Operations:

Transpose:
 - when you transpose a matrix:
    - mirroring it along its diagonal


** look up matrix mul. or div. **
** too lazy to write out notation **

```

### you can do operations with matrices and vectors together as well

** look it up as well **

## Example 

Given a_1, a_2, ..., a_n compute:

- b_i = a_i - u_a
- where u_a = (1/n) * summation(n, i=1) * a_n

```
w/o linear alg

# assume a = [a_1, a_2, ...] is given
----------------------
S = 0
for v in a:
    S += v

mean = S / len(a)
b = []

for v in a:
    b.append(v - mean)
----------------------

with linear alg
----------------------
b = a - a.dot(torch.ones_like(a)) / len(a)
----------------------

with pytoch
----------------------
b = a - a.mean()
----------------------
```