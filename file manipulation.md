```python

file = open(file_name, mode)

text = file.read()

print(text)

file.close()
```

Using  ```with``` keyword:

```python
with open(file_name, mode) as file:
	text = file.read()
	print(text)
```

```python
with open(file_name, mode) as file:
	text = file.read(10)
	print(text)
```

```python
with open(file_name, mode) as file:
	text = file.readline()
	print(text)
```

```python
with open(file_name, mode) as file:
	text = file.readlines()
	print(text)
```


modes:
- r -> read
- w -> write
- a -> append

- b -> binary