```python
b = tuple()
a = ()

a = (1, 2)

a[1] = 3 # Error : Immutable

b = (5)
type(b)

c = (2)


d = (2, 5, 7) + (8,) + (9, 12, 17)
```

```python
t = tuple((1, 2, 2, 3, 3, 3))

t.count(3) # -> 3
t.count(2) # -> 2
t.count('hi') # -> 0


t.index(1) # -> 0
t.index(3) # -> 3
t.index(5) # -> Value Error

```