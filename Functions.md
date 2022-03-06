### Why we Use Functions?
- stop repetition
- ease the debugging process
- add scalability to our code
- add readability to our code


```python
print('hello')

```

```python
a = int(input())
print(a**2)
```

```python
def say_hello():
	print('hello')
```

```python
def square(a):
	print(a**2)
```

```python
def square(a):
	return a**2
```

### How to Use Functions?
- Define a function with given structure
	- use ```def``` to indicate a dunction
	- give your function a name
	- add pranthesis at the end
	- give required arguments in paranthesis 
	- add colon to start the scope of the function
	- write code in the function
- Call the function with proper arguments


> Prime Numbers Function

```python
def is_prime(number):
	for i in range(2, int(number**(1/2)+1)):
		if number % i == 0:
			return False
	return True
```