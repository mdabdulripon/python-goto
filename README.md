# python-goto


## String

### Q. Print length of a String
```py
  name = "riyan"
  print(len(name))
```
Output:
```
  5
```

### Q. String Interpolation
```py
  name = "John"
  strInterpolation = f"Hello {name}"
  print(strInterpolation) 
```
Output:
```
  Hello John
```
### Q. String template format
```py
  name = "John"
  greet_format = "Hello {}"
  formatted = greet_format.format(name)
  print(formatted)
```
Output:
```
  Hello John
```


### Q. String split methods 
```py 
  name = "riyan"
  age = 2
  name = f"{ name } is awesome, he is { age } old"
  print(name.split())
  print(name.split(', '))
```
Output:
```
  ['riyan', 'is', 'awesome,', 'he', 'is', '2', 'old']
  ['riyan is awesome', 'he is 2 old']
```


### Q. String capitalize, upper & lower methods 
```py 
  greet = "hello world!"
  print('Capitalize: ', greet.capitalize())
  print('Upper:', greet.upper())
  print('Lower', greet.lower())
```
Output:
```
  Capitalize:  Hello world!
  Upper: HELLO WORLD!
  Lower hello world!
```

## Integer
### Q. Print length of a Number
```py
  num = 123456
  print(len(str(123456)))
```
Output:
```
  6
```




