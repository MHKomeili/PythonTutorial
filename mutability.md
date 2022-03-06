the ability to change a single item or a part of a variable

```python
l = [1, 2, 2]
l[2] = 3

# --> l would be [1, 2, 3]
```

lists are mutable

```python
gifts = {'ali':['clothes', 'game'],
		 'reza':['game', 'chips'],
		 'hamid':['socks', 'shoes'],
		 'dariush':['PS5'],
		 'Salar':['Ipad', 'note book','pen']}


gifts['ali'] = ['game']
```

dicts are mutable

```python
st = 'Cython'
st[0] = 'P' ## this raise an error

# str object doesn't suppurt item assignment
```

strings are immutable