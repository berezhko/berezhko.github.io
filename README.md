## Добро пожаловать на мою GitHub страницу!

Если:
```
def complex(r, i):
    return lambda f: f(r, i)
```
то, тогда:
```
def real(c):
    return c(lambda r, i: r)

def imag(c):
    return c(lambda r, i: i)
```