---
title: Computation time
excerpt: A trick to improve computation time when working with lists.
---

## Context : Verify if an element is in a list.

**Naive solution** : `x in L` takes $O(\mid L \mid)$ operations, i.e. it's proportional to the length of L.

If you have a lot of verifications to do and/or big lists, computation time can grow quickly.

**Trick**: Using a dictionary instead of a list reduce the number of operations for a verification. Verifying a key takes $O(1)$ operations, i.e. the number of operations is constant, it doesn't depend on the length of the dictionary.

_Time comparison:_
For a list of 10<sup>6</sup> elements

```python
L = np.random.uniform(size=1000000)
d = {key:None for key in L}
```
```python
# Naive solution
%%timeit
if 0.5 in L:
    pass
else:
    pass

# 329 µs ± 22.4 µs per loop (mean ± std. dev. of 7 runs, 1000 loops each)
```
```python
# Trick
%%timeit
try:
    d[0.5]
except KeyError:
    pass

# 256 ns ± 44.8 ns per loop (mean ± std. dev. of 7 runs, 1000000 loops each)
```

## Documentation
<https://wiki.python.org/moin/TimeComplexity>