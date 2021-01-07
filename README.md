# Python-overview
## Data types
```python
string = "I am a string"
int = 5
set = {"element1", "element2"}
object = {"property": "value"}
tuple = ("element1", "element2")
list = ["element1", "element2"]
```

## Statements
### if, elif and else
```python
a = 5
if a == 1:
  #a is 1
elif a == 5:
  #a is 5
else:
  #a is not 1 or 5 
```

## loops
### for loop
```python
# loop 5 times
for i in range(5):
  #statement
```
``` python
# print all elements in a list
elements = ["apple", "pear", "banana"]
for element in elements:
  print(element)
```
output
```
apple
pear
banana
```
### while loop
```python
# loop 5 times
i = 0
while i < 5:
  #statement
  i += 1
```

## Functions
### Defining a function
```python
def function_name(argument1, argument2):
  #statement
```
### Defining a recursive function
```python
def function_name(argument1, argument2):
  #statement
  function_namme(argument1, argument2)
```
Recursive function to calculate 3 to the power n
```python
def three_to_the_power(n, current_value=1):
  if n == 0:
      return current_value

  current_value = current_value * 3

  return three_to_the_power(n-1, current_value)
  
```
