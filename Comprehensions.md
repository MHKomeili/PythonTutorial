- List Comprehension

```python
l = []
for i in range(0, 100, 2): # start / stop / step
	l.append(i)

#for i in range(0, 50):
#	l.append(i*2)
```

```python
l = [i for i in range(0, 100, 2)]

l = [i*2 for i in range(0, 50)]

```

```python

l = [i for i in range(0, 100, 2) if i%3 != 0]

```

```python
l = [i if i%3 != 0 else 'NO' for i in range(0, 100, 2)]

```

```python
hopp = [i if i % 5 != 0 else 'HOPP' for i in range(1, 101)]
```


- Dictionaries

```python
d = dict()
# d = {}
for i in range(10):
	d[i] = i**2
```

```python
d = {i : i**2 for i in range(10)}
```

```python
l1 = ['a', 'c', 'd', 'f', 'r', 't', 'u', 'w']
l2 = [2, 5, 8, 1, 4, 3, 1, 2]

#d = {l1[i]: l1[i]*l2[i] for i in range(len(l1))}

d = {val: val*l2[index] for index, val in enumerate(l1)}


```

- Set Comprehension

```python
l2 = [2, 5, 8, 1, 4, 3, 1, 2]
s = {i for i in l2}

print(s)
# >>
```