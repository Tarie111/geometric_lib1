
# Описание функций

### circle.py


```python
def area(r):
    '''на вход функции подается радиус круга r, выводит площадь'''
    return math.pi * r * r

def perimeter(r):
    '''на вход функции подается радиус круга r, выводит периметр'''
    return 2 * math.pi * r
```

area(10) -> 100π <br>
area(5) -> 25π   <br>
perimeter(10) -> 20π <br>
perimeter(5) -> 10π 

### rectangle.py

```python
def area(a, b):
    '''на вход функции подаются стороны прямоугольника a, b, выводит площадь'''
    return a * b

def perimeter(a, b):
    '''на вход функции подаются стороны прямоугольника a, b, выводит периметр'''
    return 2 * (a + b)
```

area(10, 5) -> 50 <br>
area(13, 2) -> 26   <br>
perimeter(13, 2) -> 30 <br>
perimeter(10, 5) -> 30 


### square.py

```python
def area(a):
    '''на вход функции подается сторона квадрата a, выводит площадь'''
    return a * a

def perimeter(a):
    '''на вход функции подается сторона квадрата a, выводит периметр'''
    return 4 * a
```
area(10) -> 100 <br>
area(5) -> 25   <br>
perimeter(10) -> 40 <br>
perimeter(5) -> 20

### triangle.py

```python
def area(a, h):
    '''на вход функции подается сторона a и высота треугольника h, опущенная к ней, выводит площадь'''
    return (a * h) / 2

def perimeter(a, b, c):
    '''на вход функции подаются стороны a, b, c, выводит периметр'''
    return a + b + c
```

area(10, 5) -> 25 <br>
area(5, 20) -> 50   <br>
perimeter(3, 4, 5) -> 12 <br>
perimeter(12, 5, 13) -> 30  

