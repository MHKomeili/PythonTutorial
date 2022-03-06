جستجوی خطی 
```python
numbers = [1 , 5 , 74, 1255, 25, 12, 63, 20]

minimum = numbers[0]
index = 0
length = len(numbers)
i = 1
while i < length:
	if numbers[i] < minimum:
		minimum = numbers[i]
		index = i
	i += 1
	
print("The minimum of numbers is: ", minimum, "occured in: ", index)
```
n --> خطی
n ^ 2 --> درجه دو
‍‍‍‍‍
```python
numbers = [1 , 5 , 74, 1255, 25, 12, 63, 20]
print(max(numbers))

print(min(numbers))
```

```python
list1 = [1, 3, 5, 7, 9, 11, 13, 15, 17, 19]
list2 = [0, 2, 4, 6, 8, 10, 12, 14, 16, 18]

length = len(list2)
i = 0
while i < length:
	list1.append(list2[i])
	
print(list1)


list1.extend(list2)
```

