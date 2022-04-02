

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
***
Python 3.10
