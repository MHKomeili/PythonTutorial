```python
s = {1, 5, 7, 2, 8, 7}

print(s) 
# >> {1, 2, 5, 7, 8}

print(s[1]) # -> TypeError 
```

```python
s = {}
print(type(s))
# >> <class 'dict'>

s1 = set()
```

```python
for x in s:
	print(x)
```

> Once a set is created, you cannot change its items, but you can add new items.

```python
s = {1, 5, 7, 2, 8, 7}

s.remove(5) # OK
s.remove(7) # OK
s.remove(13) # KeyError

s.discard(1) # OK
s.discard(13) # OK. Nothing will be discarded

```

```python
s = {1, 5, 7, 7}
s.pop() # > return 1 and remove from set
s.pop() # > return 5 and remove from set
s.pop() # > return 7 and remove from set
s.pop() # KeyError. 'pop from an empty set'


s.clear()
```

```
s1 = {1, 2, 2, 5}
s2 = {3, 6, 4, 4}
```