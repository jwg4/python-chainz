Chainz
======

Chainz is a lightweight library to provide chaining, functional methods to
iterables.

```python
Chain(xrange(10))\
    .map(lambda x: x + 1)\
    .filter(lambda x: x % 2 == 0)\
    .omit(lambda x: x % 3 == 0)\
    .reduce(lambda x, y: x + y)
# 30
```
