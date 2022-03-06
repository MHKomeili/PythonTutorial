```python
while condition:
	statement
	
while شرط:
	دستور

	
for element in iterable:
	statement
	
for شمارنده in range(len (چیز قابل شمارش)):
	دستور
```


```python
list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

i = 0
l = len(list1)
while i < l: 
	list1[i] = list1[i] + 25
	i += 1 
	
print(list1)
```


```python
list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for number in list1:
	number = number + 25
	print(number)
```


```python
list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for i in range(0, len(list1)):
	list1[i] = list1[i] + 25
	
print(list1)
```

range


range(10) --> 0, 1, 2, 3, ... , 9
range(2, 15) --> 2, 3, 4, 5, ... , 14 
range(5, 25, 5) --> 5, 10, 15, 20 

range( start, end, step)


2 2 3 3  1 55 85 8 5 2 0 1 5 8 4

list_ = [1 , 2 , ... 10]

حلقه بینهایت

```python
while 1:
	# do sth
	

while 2:
	# do sth
	
	
while 'hello':
	# do sth
	

while [1]:
	# do sth
	
	
while True:
	# do sth

```

break , continue


```python
li = [1, 2, 3, 4, 5]

i = 0
while i != len(li):
	print(li[i])
	i += 1

```

```python
li = [1, 2, 3, 4, 5]

i = 0
while i != len(li):
	if i == len(li) // 2 + 1:
		break
	print(li[i])
	i += 1

```

```python
li = [1, 2, 3, 4, 5]

i = 0
while i != len(li):
	if i == len(li) // 2 + 1:
		continue
	print(li[i])
	i += 1

```