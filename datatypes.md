# python course

## Basic Datatypes



### int
```
Its a data type to represent number without decimal point. 
example: 1,2,3,10,39 etc
```

### float
```
Its a data type to represent number with decimal point.
example: 2.1, 3,14, 9.6 etc
```

### bool
```
Its a data type to True or False
example: True / False
note: Capital first letter
```

### str
```
used to represent strings, and is enclosed in string with single quotes or double quotes
example: 'shireesh', "rinky", 

if string contains single quote, then enclose the string in double quotes and viceversa if your string has double quotes in it
example: 

"I am a string with 'single quotes' in me"
'I am a string with "double quotes" in me'

'I am a string with \'double quotes\' in me'

```

### list
Its a data type that can hold collection of multiple datatypes in the form of array.
Its mutable
```python

a = [1,2,3]
b = [1,"one",True, 1.4]

b[0] = "11"

print(b)
# ["11","one",True, 1.4]
```


### tuple
Its a data type that can hold collection of multiple datatypes in the form of array.
Its immutable ie you cannot change the data in tuple like we do in list.
```python

a = (1,2,3)
b = (1,"one",True, 1.4)

b[0] = "11"
# gives error, cannot change tuple
```

### dict
Its a key value data type. you can store values for a key, ref example

```python

a = { 1: "one", 2: "two", 3: "three", "name": "master", "class" : "10th" }
print(a[1], a[2], a["name"])
# prints: one two master

```

## for more data types and practice refer.
https://www.w3schools.com/python/python_datatypes.asp

## practice

open python interactive shell, 

```
python3
```
to check type of a variable or value itself use type function type(val)

```python
type(10) == int
type(10.1) == float
type(True) == type(False) == bool
type("string val") == str
```
