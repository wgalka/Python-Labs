

```python
var1 = "Hello\tWorld!
print(var1)

>>> Hello  World!
```
 
'r' przed łańcuchem znaków ignoruje znak ucieczki

```python
var2 = r"Hello\tWorld!"
print(var2)

>>> Hello\tWorld!
```
    
'f' przed łańcuchem znaków pozwala na formatowanie(wywołanie funkcji format())
```python
var_ = "World"
var3 = f"Hello {var_}!"
print(var3)

>>> Hello  World!
```

Podzielić zdanie na słowa można wykorzystując funkcję split(sep=' ') gdzie parametr sep jest znakiem według którego podzielimy zdanie na słowa.
```python
var_str = "Hello world"

var_list = var_str.split(' ')
print(var_list)
```


---
<sub>Python 3.10</sub>
