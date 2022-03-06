data type --> نوع داده
int, float, str
---
data structure --> داده ساختار
List
```python
grades = [5, 15, 20, 17, 16, 19.5]

ages = [13, 25, 17, 44, 20, 'unk', 28]

absence = [['ali', True], ['reza', False]]
```
پیدا کردن تعداد عناصر یک لیست: 
```python
len(absence)

output: 2

```
دسترسی به هر عنصر از لیست:
```python
absence[1]

output: ['reza', False]
```

```python
		 0	 1	   2	   3	  4
list1 = [1, 52, 'salam', 45.5, [1, 2]]
‍‍		  -5  -4	 -3		 -2	   -1
```

```python
list1[2] = 25
```

برشی از لیست:
```python
list2 = [1, 2, 3, 4, 5, 12, 13, 14, 15, 20]
slice1 = list2[0:5] # --> [0, 5)
slice2 = list2[5:9] # --> [5, 9)
```

سوال:
```python
list5 #['ali', 'rezaei', 5, 235436, 52.2, 'alireza', 'fazli', 4, 543561, 41.3,
'asd', 'asd', 5, 543543, 43.6]

list6 #[['ali', 'rezaei', 5, 235436, 52.2,], ['alireza', 'fazli', 4, 543561, 41.3], ['asd', 'asd', 5, 543543, 43.6]]
```

اضافه کردن یک عنصر به یک لیست:
```python
list1 = [1, 3, 5]
list1.append(2) # --> [1, 3, 5, 2]
list2 = []
```


```python
nums = [1, 2, 3, 4]
other = [8, 7, 6, 5]

num.extend(other)

# nums -> [1, 2, 3, 4, 8, 7, 6, 5]
# other -> [8, 7, 6, 5]
```

عضویت

```python
l = [1, 2, 3, 4]
1 in l # >>> True
5 in l # >>> False
```

وارد کردن عنصر

```python
li = [1, 3, 5]
li.insert(1, 2)

# li -> [1, 2, 3, 5]

li.insert(3, 4)

# li -> [1, 2, 3, 4, 5]

li.insert(-1, 'Danger')

# li -> [1, 2, 3, 4, 'Danger', 5]
```

حذف عنصر

```python
nums = [1, 2, 3, 4, 5]
li.pop() # --> return 5 (deleted element)

# li -> [1, 2, 3, 4]

li.pop(0) # return -> 1

# li -> [2, 3, 4]
```

del

```python
list1 = [1, 2, 3, 4]

print(list1)

# output: [1, 2, 3, 4]

del(list1)

#print(list1)

# output: NameError: name 'li' is not defined

```

```python
li = [1, 3, 9, 27, 81]
li.clear()

# li -> []
```

```python
li = [1, 3, 9, 27, 81, 3, 81]

li.remove(3)

# li -> [1, 9, 27, 81, 3, 81]

li.remove(2)

# ValueError: list.remove(x): x not in list 
```

```python
li = [1, 2, 3, 4, 5]
li1 = li

li.append(6)

# li -> [1, 2, 3, 4, 5, 6]
# li1 -> [1, 2, 3, 4, 5, 6]

li1.remove(2)


# li -> [1, 3, 4, 5, 6]
# li1 -> [1, 3, 4, 5, 6]
```

``` python
li = [1, 2, 3, 4, 5]
li1 = li.copy()

li.append(6)

# li -> [1, 2, 3, 4, 5, 6]
# li1 -> [1, 2, 3, 4, 5]

li1.remove(2)


# li -> [1, 2, 3, 4, 5, 6]
# li1 -> [1, 3, 4, 5]
```

```python
li = [1, 2, 3, 5, 5, 6, 8, 5, 3, 2, 5, 1]
li.count(5)

# return -> 4
```

```python
li = [1, 2, 3, 5, 5, 6, 8, 5, 3, 2, 5, 1]
li.reverse()


# li ->[1, 5, 2, 3, 5, 8, 6, 5, 5, 3, 2, 1]

```

```python

li = [1, 2, 3, 2, 5, 7, 2]

li.index(2)

# return -> 1

li.index(8)

# ValueError: 8 is not in list
```

```python
li = [1, 8, 9, 5, 2, 4, 3, 0, 7, 6]

sorted(li)

# retrun -> [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
# li -> [1, 8, 9, 5, 2, 4, 3, 0, 7, 6]

li.sort()

# li -> [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]


```


method

built-in function
https://docs.python.org/3/library/functions.html

