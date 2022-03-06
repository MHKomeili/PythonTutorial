every item in dictionary has 2 things:
* key
* value

```python
empt = dict()
empty_dict = {}

my_dict = {1:'one', 2:'two', 3:'three'}
my_dict[0] # --> Key Error : 0
my_dict[1] # --> 'one'


gifts = {'ali':['clothes', 'game'],
		 'reza':['game', 'chips'],
		 'hamid':['socks', 'shoes'],
		 'dariush':['PS5'],
		 'Salar':['Ipad', 'note book','pen']}

gifts['ali'] #--> ['clothes', 'game']

gifts['ahmad'] = ['Chocolate']

gifts['ali'] = ['game']
```

```python
l = [1, 2, 3]
l[0] # --> 1 
```

method:

```python
dictionary = {"saturday":0, 
			  'sunday':1,
			  'monday':2}
dictionary.keys()
dictionary.values()
dictionary.items()

dictionary['monday'] = 3


```

```python
a = {'a': 1, 'b':2, 'c':3, 'b':5, 'b':12, 'a':2555}

print(a)
print(*a)
# >> {'a': 2555, 'b': 12, 'c': 3} 
```

#### Methods:
```python
print(a['d']) #--> Key Error ('d' does not exist)

dictionary.get('b')
dictionary.get('e')

dictionary.setdefault('a', 100)
dictionary.setdefault('d', 10)

dictionary.clear()

a.pop('d') #--> return value of d then remove

d1 = {'hello': 5, 'hi': 2, 'enthusiast':10}
d2 = {'every': 5, 'good': 4, 'worst': 5}

d1.update(d2)

d3 = d1 | d2
```

```python
d = {i:i**2 for i in range(5)}

print(d)
# >> {0: 0, 1: 1, 2: 4, 3: 9, 4: 16}

```

```python

```